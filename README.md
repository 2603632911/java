# java
java第四次实验  
#接口异常处理实验  
# 接口异常处理
## 实验目的
掌握java中抽象类和抽象方法的定义；    
掌握jiava中接口的定义，熟练掌握接口的定义形式，以及接口的实现方式，       
了解异常的处理方式，并在程序中根据输入情况做异常处理     
## 实验过程  
创建class Teacher  
创建教师管理接口 设置性别，姓名，薪水变量，设置形参并将其实例化  
创建class student  
创建学生管理接口 设置性别，姓名，年龄，薪水变量，设置形参并将其实例化
创建class test  
利用try-catch语句判断变量输入是否符合规定的类型，并给出相应的报错
## 核心方法  
创建老师管理接口     
interface TeacherManage {  
    void setsalary(int salary);  
    int getsalary();  
}    
核心方法1       
public class Teacher implements TeacherManage{  
	String sex;   
    String name;  
    int age;  
    int salary;  
创建学生管理接口  
interface StudentManage {  
    void setfee(int fee);  
    int getfee();    
核心方法2  
public class Students implements StudentManage,TeacherManage{
    String sex;   
    String name;  
    int age;  
    int spending;  
    int salary;  


## 实验结果
![](https://github.com/2603632911/java/blob/main/第四次实验.png)
## 实验感想
通过这次接口异常处理实验，让我对异常的输入数据的报错，这一类的程序的结构设计有了实践，实际操作了创建接口和实例化接口，同时在报错方面，运用了try-catch语句，让我对各种类型的错误有了了解，在编写程序时，要考虑到可能出现的错误类型，并给出提示，同时，在设置变量类型的时候，也要根据不同情况而考虑
