# javake
java作业
#实验目的  
初步了解分析系统需求，从学生选课角度了解系统中的实体及其关系，学会定义类中的属性以及方法；  
掌握面向对象的类设计方法（属性、方法）；  
掌握类的继承用法，通过构造方法实例化对象；  
学会使用super()，用于实例化子类；  
掌握使用Object根类的toString（）方法,应用在相关对象的信息输出中。  
#实验过程  
1.首先阅读程序要求  
2.定义一个子类（teache xuesheng）和父类（renyuan）  
3.让子类继承父类  
4.运行  
#核心方法  
1.方法1：子类调用父类  
```  
public teacher(int number,String name,String sex,int age) {
		super(number,name,sex,age);  
```  
2.方法2：toString重写  
```  
public String toString() {
		return"教师信息："+super.toString();
	}
```  
3.方法3：声明、调用等功能  
#实验结果  

``` 
教师信息：[编号0,姓名：周周,性别：男,年龄：30]
学生[编号0,姓名：王王,性别：男,年龄：19]课程信息：[课程编号：3546,课程名称：语文,上课时间：8:00,授课老师：周周]

```  
#实验感想  
1.学会了子类父类如何继承  
2.以后编程遇到问题，要学会自己调试  
3.通过编程过程，发现了很多问题，会继续通过课余时间巩固知识点
4.本次实验感觉有些难度，会继续努力学习



