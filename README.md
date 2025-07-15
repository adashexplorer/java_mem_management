# Java Memory Management
Project learner to deep dive into following concepts.

- Java Virtual Machine (JVM)
- Java Development Kit (JDK)
- Java Runtime Environment (JRE)

# JDK
- Stands for Java Development Kit.
- A **cross platformed software development environment.**
- Combination of development tools + libs to create/develop java programs.
- It is platform dependent i.e different `Operating System (OS)` will have different JDK of its own.
- It works in following ways <br>
   i. Programmer writes code & save it in .java file. (Ex - `Employee.java`)  (Source file creation)<br>
   ii. The source file gets compiled by the `Java Compiler` (part of JDK) into byte code which is stored in .class file. (Ex - `Employee.class`) <br>
   iii. The bytecode is executed by the JVM which interprets the byte code & runs the program. <br>
- JVM + JRE (JVM is part of JRE) = JDK

## JRE


NOTE -
 It is often confused by developers between JDK & JRE. If you are only interested in executing Java programs then JRE is the one. But, if you would want to 
 develop a Java based software application then along with JRE you would need JDK as well.


Java memory management is a fundamental concept that involves the automatic allocation and de-allocation of objects, managed by the Java Virtual Machine (JVM). 
The JVM uses a garbage collector to automatically remove unused objects, freeing up memory in the background. 
This eliminates the need for developers to manually handle memory management.

Ideally all the memory management is done by JVM via `garbage collector`. But, not all memory are managed automatically. So, YES there is a need for the programmer to
understand the **Memory Management**.


```
 class Employee {
     private String employeeName;
     
     public Employee() {
        super();
     }
 }
```