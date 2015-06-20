# core-java-test1-with-answer
answers
Core Java Test Questions and answers:
                                        
Please Answer the below questions briefly:
1.	What is the most important feature of java?
       There are some important features available in java.
They are:
1. WORA is Write once run any ware.
2. platform independent.
3. multithreading
4. security
5. exception handling. 

2.	What do you mean by platform independent?
           Platform independent is we can run java program in any os like,
   Windows, linux, unix and mac etc…

3.	What is the difference between JVM,JDK and JRE?
            JDE is java development kit
            JRE is java runtime environment 
            JVM is java virtual machine 

4.	What is the concept called Pointers? And does java supports Pointer?
             There is no usage of pointers in java..java does not support 
Pointers.
           
5.	What is the base class of all the classes?
             Class is a template or blue print that describers the variables and methods.
Grouping of states and behaviors which comes under the class level. 

6.	What do you mean by local variables?
            Local variables that are stored in stack memory.
We cannot use modifiers in local variables, it can be explicitly 
 And once it declared it automatically destroys himself.
 
7.	What do you mean by Class Variables?
             Class variables are also called as static variable. It used in global level or 
Instance variables that can stored in heap memory and also it has separate static memory its
Creates for entire  object.  Static  variables are common for every object which we are creating in program.

8.	Can you explain: public static void main(String args[])
      It is a main method in java program. Without using this main method we cannot compile
 and execute program. Public is everyone can access,  VOID MAIN is a return_type and any method we can assign and also we have to pass arguments.

9.	Can main method to be overloaded?
         Yes, main method can overload. we can use it in another class level function.
It can be overload in java. 

10.	Can a Class declared as protected?
              No, we can declared in method level and also its like a public.

11.	I don’t want my class to be inherited by other classes. What should I do?
               Final keyword should be used in class name. so no one can be access it in any other program. If final keyword is used then we cannot extends.
 
12.	What is the purpose of declaring variable as final?
          If we declare variable as final we cannot use that variables in any other ways.
Like ex. Instance variable FINAL int y =8; then we cannot create y=7 or 9. Y=8 is final for that program. it can be initialized  by only once.
 
13.	What is the impact of declaring a method as final?
          The impact will be we can’t overridden in subclass. user cannot override in subclass like extends class.

14.	What is an abstract class and what is the purpose?
           If abstract is used in variables or methods we have to given class name as abstract. And (abstract void display();) it can be extended on sub class. it cannot create object for abstract class it must be extended by some other class. and in abstract class it can be overhide it possible in abstract class.
  
15.	Can a abstract class defines as final?
         In java program abstract and final cannot be together.

16.	Can you create object for abstract class?
             No we cannot create object for abstract class we must extend by sub class and then only 
We can create object for it..

17.	What is the use of instance of operator?
          To check the object like which class its stored in that program.

18.	What is an abstract method?
        Abstract method is
    Class add
{
Int =8;
  Abstract void add();
Void sub(){
Int a=8; 
}
Class abstract extends add
{
Int =8;
  Abstract void add()
{
We can override here
}

19.	What are the different types of if statements available?
     There three types;
If(boolen condition)
{
statement
}
Else
{
statement
}
And  if ,else if,else if and else
Last is nested if statement is used ..

20.	Please explain about all access modifiers in java?
         
                                   Same                same package         other package              another package
                                   Class                  outside class         outside class         sub class
         Default               yes                      yes                         no                  no
         Public                 yes                     yes                        yes                 yes
         Private                yes                     no                          no                  no      
        Protected             yes                        yes                        no                  yes       
Please Write Programs for below scenario:
1.Getting three inputs from the user and displaying which one is greater one.
      Class inputs
{
Public static void main(String []args)
{
Int  a, b, c;
Scanner scan = new Scanner (System.in);
System.out.println(“Enter the a value”);
Int a =scan.nextInt();
System.out.println(“ a value is:”+a);
System.out.println(“Enter the b value”);
Int b =scan.nextInt();
System.out.println(“ a value is:”+b);
System.out.println(“Enter the c value”);
Int c =scan.nextInt();
System.out.println(“ a value is:”+c);
If(a>b)
{
System.out.println(“b is greater”+a);
}
Else if(c>a)
{
System.out.println(“c is greater”+a);
}
Else
{
System.ou.println(“code is wrong”);
}
}
}
OUT PUT IS 
Enter value a : 6
Enter value b: 9
Enter value c: 3
 B is  grater is 9. 
2.Student Marks grade system.
import java.util.Scanner;
class ifelse
{
public static void main(String args[])
{
int marks,passmark=40;
Scanner in=new Scanner(System.in);
System.out.println("Enter the phy marks");
int phy=in.nextInt();
System.out.println("phy marks is :"+phy);
System.out.println("Enter the maths marks");
int maths=in.nextInt();
System.out.println("maths marks is :"+maths);
if(phy>passmark)
{
	
System.out.println("s grade");
	
}
else if(phy>80)
{
	System.out.println("a grade ");
}
else if(phy>70)
{
	System.out.println("b grade ");
}
else if(phy>60)
{
	System.out.println("c grade ");
}
else
{
	System.out.println("a grade ");
}

}
}
OUTPUT IS….
Enter the phy marks
70
Phy marks is S grade.
3.sample program for abstract class and method concept?
   abstract class f2
{
int a=3,b=6;
abstract void add();
void sub()
{
int c=a-b;
System.out.println("substraction of a and b is :"+c);
}
}
class d extends f2
{
int a=3,b=6;
void add()
{
int c=a+b;
System.out.println(c);
}
void sub()
{
int c=a-b;
System.out.println("substraction of a and b is :"+c);
}
public static void main(String []args)
{
f2 obj1=new d();
obj1.add();
obj1.sub();
}
}
OUTPUT IS..
9
Subrsction of s and b is :3

4.Sample program for swapping two variables without using third variable?
      Class swapping
{
Public static void main(String []args)
{
Int a=5,b=8;
Void  add ()
{
Int c=a +b;
System.out.print(“swapping  program is :”+c);
}




All the Best!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!



