# Java Basics Interview Questions

## 1- What is Java?
Java is the high-level, object-oriented, robust, secure programming language, platform-independent, high performance, Multithreaded, and portable programming language. It was developed by James Gosling in June 1991. It can also be known as the platform as it provides its own JRE and API.

## 2- What are the differences between C++ and Java?
The differences between **C++** and **Java** are given in the following table.
| **Comparison Index**      | C++ | Java |
| ----------- | ----------- | ----------- |
| **Platform-independent** | C++ is platform-dependent. | Java is platform-independent. |
| **Mainly used for** | C++ is mainly used for system programming. | Java is mainly used for application programming. It is widely used in window, web-based, enterprise and mobile applications. |
| **Design Goal**	| **C++** was designed for systems and applications programming. It was an extension of **C** programming language. | **Java** was designed and created as an interpreter for printing systems but later extended as a support network computing. It was designed with a goal of being easy to use and accessible to a broader audience. |
| **Goto** | C++ supports the _**goto**_ statement. | Java doesn't support the _**goto**_ statement. |
| **Multiple inheritance** | C++ supports multiple inheritance. | Java doesn't support multiple inheritance through class. It can be achieved by _**interfaces in java.**_ |
| **Operator Overloading** | C++ supports **_operator overloading.**_ | Java doesn't support operator overloading. |
| **Pointers** | C++ supports _**pointers.**_ You can write pointer program in C++. | Java supports pointer internally. However, you can't write the pointer program in java. It means java has restricted pointer support in Java. |
| **Compiler and Interpreter** | C++ uses compiler only. C++ is compiled and run using the compiler which converts source code into machine code so, C++ is platform dependent. | Java uses compiler and interpreter both. Java source code is converted into bytecode at compilation time. The interpreter executes this bytecode at runtime and produces output. Java is interpreted that is why it is platform independent. |
| **Call by Value and Call by reference** | C++ supports both call by value and call by reference. | Java supports call by value only. There is no call by reference in java. |
| **Structure and Union** | C++ supports structures and unions. | Java doesn't support structures and unions. |
| **Thread Support** | C++ doesn't have built-in support for threads. It relies on third-party libraries for thread support. | Java has built-in thread support. |
| **Documentation comment** | C++ doesn't support documentation comment. | Java supports documentation comment (/** ... */) to create documentation for java source code. |
| **Virtual Keyword** | C++ supports virtual keyword so that we can decide whether or not override a function. | Java has no virtual keyword. We can override all non-static methods by default. In other words, non-static methods are virtual by default. |
| **unsigned right shift >>>** | C++ doesn't support >>> operator. | Java supports unsigned right shift >>> operator that fills zero at the top for the negative numbers. For positive numbers, it works same like >> operator. |
| **Inheritance Tree** | C++ creates a new inheritance tree always. | Java uses a single inheritance tree always because all classes are the child of Object class in java. The object class is the root of the inheritance tree in java. |
| **Hardware** | C++ is nearer to hardware. | Java is not so interactive with hardware. |
| **Object-oriented** | C++ is an object-oriented language. However, in C language, single root hierarchy is not possible. | Java is also an object-oriented language. However, everything (except fundamental types) is an object in Java. It is a single root hierarchy as everything gets derived from java.lang.Object. |

## 3- List the features of Java Programming language.
There are the following features in Java Programming Language.

- _**Simple:**_ Java is easy to learn. The syntax of Java is based on C++ which makes easier to write the program in it.

- _**Object-Oriented:**_ Java follows the object-oriented paradigm which allows us to maintain our code as the combination of different type of objects that incorporates both data and behavior.

- _**Portable:**_ Java supports read-once-write-anywhere approach. We can execute the Java program on every machine. Java program (.java) is converted to bytecode (.class) which can be easily run on every machine.

- _**Platform Independent:**_ Java is a platform independent programming language. It is different from other programming languages like C and C++ which needs a platform to be executed. Java comes with its platform on which its code is executed. Java doesn't depend upon the operating system to be executed.

- _**Secured:**_ Java is secured because it doesn't use explicit pointers. Java also provides the concept of ByteCode and Exception handling which makes it more secured.

- _**Robust:**_ Java is a strong programming language as it uses strong memory management. The concepts like Automatic garbage collection, Exception handling, etc. make it more robust.

- _**Architecture Neutral:**_ Java is architectural neutral as it is not dependent on the architecture. In C, the size of data types may vary according to the architecture (32 bit or 64 bit) which doesn't exist in Java.

- _**Interpreted:**_ Java uses the Just-in-time (JIT) interpreter along with the compiler for the program execution.

- _**High Performance:**_ Java is faster than other traditional interpreted programming languages because Java bytecode is "close" to native code. It is still a little bit slower than a compiled language (e.g., C++).

- _**Multithreaded:**_ We can write Java programs that deal with many tasks at once by defining multiple threads. The main advantage of multi-threading is that it doesn't occupy memory for each thread. It shares a common memory area. Threads are important for multi-media, Web applications, etc.

- _**Distributed:**_ Java is distributed because it facilitates users to create distributed applications in Java. RMI and EJB are used for creating distributed applications. This feature of Java makes us able to access files by calling the methods from any machine on the internet.

- _**Dynamic:**_ Java is a dynamic language. It supports dynamic loading of classes. It means classes are loaded on demand. It also supports functions from its native languages, i.e., C and C++.

## 4- What do you understand by Java virtual machine?
Java Virtual Machine is a virtual machine that enables the computer to run the Java program. JVM acts like a run-time engine which calls the main method present in the Java code. JVM is the specification which must be implemented in the computer system. The Java code is compiled by JVM to be a Bytecode which is machine independent and close to the native code.

## 5- What is the difference between JDK, JRE, and JVM?

**JVM** is an acronym for Java Virtual Machine; it is an abstract machine which provides the runtime environment in which Java bytecode can be executed. It is a specification which specifies the working of Java Virtual Machine. Its implementation has been provided by Oracle and other companies. Its implementation is known as JRE.

JVMs are available for many hardware and software platforms (so JVM is platform dependent). It is a runtime instance which is created when we run the Java class. There are three notions of the JVM: specification, implementation, and instance.

**JRE** stands for Java Runtime Environment. It is the implementation of JVM. The Java Runtime Environment is a set of software tools which are used for developing Java applications. It is used to provide the runtime environment. It is the implementation of JVM. It physically exists. It contains a set of libraries + other files that JVM uses at runtime.

**JDK** is an acronym for Java Development Kit. It is a software development environment which is used to develop Java applications and applets. It physically exists. It contains JRE + development tools. JDK is an implementation of any one of the below given Java Platforms released by Oracle Corporation:

- Standard Edition Java Platform
- Enterprise Edition Java Platform
- Micro Edition Java Platform

## 6- What is JIT compiler?
Just-In-Time(JIT) compiler: It is used to improve the performance. JIT compiles parts of the bytecode that have similar functionality at the same time, and hence reduces the amount of time needed for compilation. Here the term ???compiler??? refers to a translator from the instruction set of a Java virtual machine (JVM) to the instruction set of a specific CPU.

## 7- What is the platform?
A platform is the hardware or software environment in which a piece of software is executed. There are two types of platforms, software-based and hardware-based. Java provides the software-based platform.

## 8- What gives Java its 'write once and run anywhere' nature?
The bytecode. Java compiler converts the Java programs into the class file (Byte Code) which is the intermediate language between source code and machine code. This bytecode is not platform specific and can be executed on any computer.

## 9- What is classloader?
Classloader is a subsystem of JVM which is used to load class files. Whenever we run the java program, it is loaded first by the classloader. There are three built-in classloaders in Java.

- _**Bootstrap ClassLoader:**_ This is the first classloader which is the superclass of Extension classloader. It loads the **rt.jar** file which contains all class files of Java Standard Edition like **java.lang package classes, java.net package classes, java.util package classes, java.io package classes, java.sql package classes, etc.**
- _**Extension ClassLoader:**_ This is the child classloader of Bootstrap and parent classloader of System classloader. It loads the jar files located inside **$JAVA_HOME/jre/lib/ext directory.**
- _**System/Application ClassLoader:**_ This is the child classloader of Extension classloader. It loads the class files from the classpath. By default, the classpath is set to the current directory. You can change the classpath using **"-cp"** or **"-classpath"** switch. It is also known as Application classloader.

## 10- What if I write static public void instead of public static void?
The program compiles and runs correctly because the order of specifiers doesn't matter in Java.

## 11- What is the default value of the local variables?
The local variables are not initialized to any default value, neither primitives nor object references.

## 12- What are the various access specifiers in Java?
In Java, access specifiers are the keywords which are used to define the access scope of the method, class, or a variable. In Java, there are four access specifiers given below.

- **Public** The classes, methods, or variables which are defined as public, can be accessed by any class or method.
- **Protected** Protected can be accessed by the class of the same package, or by the sub-class of this class, or within the same class.
- **Default** Default are accessible within the package only. By default, all the classes, methods, and variables are of default scope.
- **Private** The private class, methods, or variables defined as private can be accessed within the class only.

## 13- What is the purpose of static methods and variables?
The methods or variables defined as static are shared among all the objects of the class. The static is the part of the class and not of the object. The static variables are stored in the class area, and we do not need to create the object to access such variables. Therefore, static is used in the case, where we need to define variables or methods which are common to all the objects of the class.

For example, In the class simulating the collection of the students in a college, the name of the college is the common attribute to all the students. Therefore, the college name will be defined as **static.**

## 14- What are the advantages of Packages in Java?
There are various advantages of defining packages in Java.

- Packages avoid the name clashes.
- The Package provides easier access control.
- We can also have the hidden classes that are not visible outside and used by the package.
- It is easier to locate the related classes.

## 15- What is the output of the following Java program?
```
class Test   
{  
    public static void main (String args[])   
    {  
        System.out.println(10 + 20 + "Javatpoint");   
        System.out.println("Javatpoint" + 10 + 20);  
    }  
}  
```
**The output of the above code will be**
```
30Javatpoint
Javatpoint1020  
```
**Explanation**

In the first case, 10 and 20 are treated as numbers and added to be 30. Now, their sum 30 is treated as the string and concatenated with the string **Javatpoint.** Therefore, the output will be **30Javatpoint.**

In the second case, the string Javatpoint is concatenated with 10 to be the string **Javatpoint10** which will then be concatenated with 20 to be **Javatpoint1020.**

## 16- What is object-oriented paradigm?
It is a programming paradigm based on objects having data and methods defined in the class to which it belongs. Object-oriented paradigm aims to incorporate the advantages of modularity and reusability. Objects are the instances of classes which interacts with one another to design applications and programs. There are the following features of the object-oriented paradigm.

- Follows the bottom-up approach in program design.
- Focus on data with methods to operate upon the object's data
- Includes the concept like Encapsulation and abstraction which hides the complexities from the user and show only functionality.
- Implements the real-time approach like inheritance, abstraction, etc.
- The examples of the object-oriented paradigm are C++, Simula, Smalltalk, Python, C#, etc.

## 17- What is an object?
The Object is the real-time entity having some state and behavior. In Java, Object is an instance of the class having the instance variables as the state of the object and the methods as the behavior of the object. The object of a class can be created by using the new keyword.

## 18- What is the difference between an object-oriented programming language and object-based programming language?
There are the following basic differences between the object-oriented language and object-based language.

- Object-oriented languages follow all the concepts of OOPs whereas, the object-based language doesn't follow all the concepts of OOPs like inheritance and polymorphism.
- Object-oriented languages do not have the inbuilt objects whereas Object-based languages have the inbuilt objects, for example, JavaScript has window object.
- Examples of object-oriented programming are Java, C#, Smalltalk, etc. whereas the examples of object-based languages are JavaScript, VBScript, etc.

## 19- What will be the initial value of an object reference which is defined as an instance variable?
All object references are initialized to null in Java.

## 20- What is the constructor?
The constructor can be defined as the special type of method that is used to initialize the state of an object. It is invoked when the class is instantiated, and the memory is allocated for the object. Every time, an object is created using the new keyword, the default constructor of the class is called. The name of the constructor must be similar to the class name. The constructor must not have an explicit return type.

## 21- How many types of constructors are used in Java?
Based on the parameters passed in the constructors, there are two types of constructors in Java.

- **Default Constructor:** default constructor is the one which does not accept any value. The default constructor is mainly used to initialize the instance variable with the default values. It can also be used for performing some useful task on object creation. A default constructor is invoked implicitly by the compiler if there is no constructor defined in the class.

- **Parameterized Constructor:** The parameterized constructor is the one which can initialize the instance variables with the given values. In other words, we can say that the constructors which can accept the arguments are called parameterized constructors.

## 22- What is the purpose of a default constructor?
The purpose of the default constructor is to assign the default value to the objects. The java compiler creates a default constructor implicitly if there is no constructor in the class.

## 23- Does constructor return any value?
Yes, The constructor implicitly returns the current instance of the class (You can't use an explicit return type with the constructor)

## 24- Is constructor inherited?
No, The constructor is not inherited.

## 25- Can you make a constructor final?
No, the constructor can't be final.

## 26- Can we overload the constructors?
Yes, the constructors can be overloaded by changing the number of arguments accepted by the constructor or by changing the data type of the parameters.

## 27- What are the differences between the constructors and methods?
There are many differences between constructors and methods. They are given below.

| Java Constructor | Java Method |
| ----------- | ----------- |
| A constructor is used to initialize the state of an object. | A method is used to expose the behavior of an object. |
| A constructor must not have a return type. | A method must have a return type. |
| The constructor is invoked implicitly. | The method is invoked explicitly. |
| The Java compiler provides a default constructor if you don't have any constructor in a class. | The method is not provided by the compiler in any case. |
| The constructor name must be same as the class name. | The method name may or may not be same as class name. |

## 28- What is the static variable?
The static variable is used to refer to the common property of all objects (that is not unique for each object), e.g., The company name of employees, college name of students, etc. Static variable gets memory only once in the class area at the time of class loading. Using a static variable makes your program more memory efficient (it saves memory). Static variable belongs to the class rather than the object.

## 29- What is the static method?
- A static method belongs to the class rather than the object.
- There is no need to create the object to call the static methods.
- A static method can access and change the value of the static variable.

## 30- What are the restrictions that are applied to the Java static methods?
Two main restrictions are applied to the static methods.

- The static method can not use non-static data member or call the non-static method directly.
- this and super cannot be used in static context as they are non-static.

## 31- Why is the main method static?
Because the object is not required to call the static method. If we make the main method non-static, JVM will have to create its object first and then call main() method which will lead to the extra memory allocation.

## 32- Can we override the static methods?
No, we can't override static methods.

## 33- What is the static block?
Static block is used to initialize the static data member. It is executed before the main method, at the time of classloading.

## 34- Can we execute a program without main() method?
Ans) No, It was possible before JDK 1.7 using the static block. Since JDK 1.7, it is not possible.

## 35- What if the static modifier is removed from the signature of the main method?
Program compiles. However, at runtime, It throws an error "NoSuchMethodError."

## 36- What is the difference between static (class) method and instance method?
| static or class method | instance method |
| ----------- | ----------- |
| 1)A method that is declared as static is known as the static method. | A method that is not declared as static is known as the instance method. |
| 2)We don't need to create the objects to call the static methods. | The object is required to call the instance methods. |
| 3)Non-static (instance) members cannot be accessed in the static context (static method, static block, and static nested class) directly. | Static and non-static variables both can be accessed in instance methods. |
| 4)For example: public static int cube(int n){ return n*n*n;} | For example: public void msg(){...}. |

## 37- Can we make constructors static?
As we know that the static context (method, block, or variable) belongs to the class, not the object. Since Constructors are invoked only when the object is created, there is no sense to make the constructors static. However, if you try to do so, the compiler will show the compiler error.

## 38- Can we make the abstract methods static in Java?
In Java, if we make the abstract methods static, It will become the part of the class, and we can directly call it which is unnecessary. Calling an undefined method is completely useless therefore it is not allowed.

## 39- Can we declare the static variables and methods in an abstract class?
Yes, we can declare static variables and methods in an abstract method. As we know that there is no requirement to make the object to access the static context, therefore, we can access the static context declared inside the abstract class by using the name of the abstract class. Consider the following example.

## 40- What is _this_ keyword in java?
The this keyword is a reference variable that refers to the current object. There are the various uses of this keyword in Java. It can be used to refer to current class properties such as instance methods, variable, constructors, etc. It can also be passed as an argument into the methods or constructors. It can also be returned from the method as the current class instance.

## 41- What are the main uses of this keyword?
There are the following uses of _**this**_ keyword.

- **this** can be used to refer to the current class instance variable.
- **this** can be used to invoke current class method (implicitly)
- **this()** can be used to invoke the current class constructor.
- **this** can be passed as an argument in the method call.
- **this** can be passed as an argument in the constructor call.
- **this** can be used to return the current class instance from the method.

## 42- Can we assign the reference to this variable?
No, this cannot be assigned to any value because it always points to the current class object and this is the final reference in Java. However, if we try to do so, the compiler error will be shown. Consider the following example.

## 43- Can this keyword be used to refer static members?
Yes, It is possible to use this keyword to refer static members because this is just a reference variable which refers to the current class object. However, as we know that, it is unnecessary to access static variables through objects, therefore, it is not the best practice to use this to refer static members. Consider the following example.

## 44- How can constructor chaining be done using this keyword?
Constructor chaining enables us to call one constructor from another constructor of the class with respect to the current class object. We can use this keyword to perform constructor chaining within the same class. Consider the following example which illustrates how can we use this keyword to achieve constructor chaining.

## 45- What are the advantages of passing this into a method instead of the current class object itself?
As we know, that this refers to the current class object, therefore, it must be similar to the current class object. However, there can be two main advantages of passing this into a method instead of the current class object.

- this is a final variable. Therefore, this cannot be assigned to any new value whereas the current class object might not be final and can be changed.
- this can be used in the synchronized block.

## 46- What is the Inheritance?
Inheritance is a mechanism by which one object acquires all the properties and behavior of another object of another class. It is used for Code Reusability and Method Overriding. The idea behind inheritance in Java is that you can create new classes that are built upon existing classes. When you inherit from an existing class, you can reuse methods and fields of the parent class. Moreover, you can add new methods and fields in your current class also. Inheritance represents the IS-A relationship which is also known as a parent-child relationship.

There are five types of inheritance in Java.

- Single-level inheritance
- Multi-level inheritance
- Multiple Inheritance
- Hierarchical Inheritance
- Hybrid Inheritance

Multiple inheritance is not supported in Java through class.

## 47- Why is Inheritance used in Java?
There are various advantages of using inheritance in Java that is given below.

- Inheritance provides code reusability. The derived class does not need to redefine the method of base class unless it needs to provide the specific implementation of the method.
- Runtime polymorphism cannot be achieved without using inheritance.
- We can simulate the inheritance of classes with the real-time objects which makes OOPs more realistic.
- Inheritance provides data hiding. The base class can hide some data from the derived class by making it private.
- Method overriding cannot be achieved without inheritance. By method overriding, we can give a specific implementation of some basic method contained by the base class.

## 48- Which class is the superclass for all the classes?
The object class is the superclass of all other classes in Java.

## 49- Why is multiple inheritance not supported in java?
To reduce the complexity and simplify the language, multiple inheritance is not supported in java. Consider a scenario where A, B, and C are three classes. The C class inherits A and B classes. If A and B classes have the same method and you call it from child class object, there will be ambiguity to call the method of A or B class.

Since the compile-time errors are better than runtime errors, Java renders compile-time error if you inherit 2 classes. So whether you have the same method or different, there will be a compile time error.

## 50- What is aggregation?
Aggregation can be defined as the relationship between two classes where the aggregate class contains a reference to the class it owns. Aggregation is best described as a **has-a** relationship. For example, The aggregate class Employee having various fields such as age, name, and salary also contains an object of Address class having various fields such as Address-Line 1, City, State, and pin-code. In other words, we can say that Employee (class) has an object of Address class. Consider the following example.

## 51- What is composition?
Holding the reference of a class within some other class is known as composition. When an object contains the other object, if the contained object cannot exist without the existence of container object, then it is called composition. In other words, we can say that composition is the particular case of aggregation which represents a stronger relationship between two objects. Example: A class contains students. A student cannot exist without a class. There exists composition between class and students.

## 52- What is the difference between aggregation and composition?
Aggregation represents the weak relationship whereas composition represents the strong relationship. For example, the bike has an indicator (aggregation), but the bike has an engine (composition).

## 53- Why does Java not support pointers?
The pointer is a variable that refers to the memory address. They are not used in Java because they are unsafe(unsecured) and complex to understand.

## 54- What is super in java?
The super keyword in Java is a reference variable that is used to refer to the immediate parent class object. Whenever you create the instance of the subclass, an instance of the parent class is created implicitly which is referred by super reference variable. The super() is called in the class constructor implicitly by the compiler if there is no super or this.

## 55- What are the main uses of the super keyword?
There are the following uses of super keyword.

- **super** can be used to refer to the immediate parent class instance variable.
- **super** can be used to invoke the immediate parent class method.
- **super()** can be used to invoke immediate parent class constructor.

## 56- What are the differences between this and super keyword?
There are the following differences between this and super keyword.

- The **super** keyword always points to the parent class contexts whereas this keyword always points to the current class context.
- The **super** keyword is primarily used for initializing the base class variables within the derived class constructor whereas this keyword primarily used to differentiate between local and instance variables when passed in the class constructor.
- The **super** and this must be the first statement inside constructor otherwise the compiler will throw an error.

## 57- Can you use this() and super() both in a constructor?
No, because this() and super() must be the first statement in the class constructor.

## 58- What is object cloning?
The object cloning is used to create the exact copy of an object. The clone() method of the Object class is used to clone an object. The java.lang.Cloneable interface must be implemented by the class whose object clone we want to create. If we don't implement Cloneable interface, clone() method generates CloneNotSupportedException.

## 59- What is method overloading?
Method overloading is the polymorphism technique which allows us to create multiple methods with the same name but different signature. We can achieve method overloading in two ways.

- By Changing the number of arguments
- By Changing the data type of arguments
Method overloading increases the readability of the program. Method overloading is performed to figure out the program quickly.

## 60- Why is method overloading not possible by changing the return type in java?
In Java, method overloading is not possible by changing the return type of the program due to avoid the ambiguity.

## 61- Can we overload the methods by making them static?
No, We cannot overload the methods by just applying the static keyword to them(number of parameters and types are the same). Consider the following example.

## 62- Can we overload the main() method?
Yes, we can have any number of main methods in a Java program by using method overloading.

## 63- What is method overriding:
If a subclass provides a specific implementation of a method that is already provided by its parent class, it is known as Method Overriding. It is used for runtime polymorphism and to implement the interface methods.

**Rules for Method overriding**

- The method must have the same name as in the parent class.
- The method must have the same signature as in the parent class.
- Two classes must have an IS-A relationship between them.

## 63- Can we override the static method?
No, you can't override the static method because they are the part of the class, not the object.

## 64- Why can we not override static method?
It is because the static method is the part of the class, and it is bound with class whereas instance method is bound with the object, and static gets memory in class area, and instance gets memory in a heap.

## 65- Can we override the overloaded method?
Yes.

## 66- Difference between method Overloading and Overriding.
| Method Overloading | Method Overriding |
| 1) Method overloading increases the readability of the program. | Method overriding provides the specific implementation of the method that is already provided by its superclass. |
| 2) Method overloading occurs within the class. | Method overriding occurs in two classes that have IS-A relationship between them. |
| 3) In this case, the parameters must be different. | In this case, the parameters must be the same. |

## 67- Can we override the private methods?
No, we cannot override the private methods because the scope of private methods is limited to the class and we cannot access them outside of the class.

## 68- Can we change the scope of the overridden method in the subclass?
Yes, we can change the scope of the overridden method in the subclass. However, we must notice that we cannot decrease the accessibility of the method. The following point must be taken care of while changing the accessibility of the method.

- The private can be changed to protected, public, or default.
- The protected can be changed to public or default.
- The default can be changed to public.
- The public will always remain public.

## 69- Can you have virtual functions in Java?
Yes, all functions in Java are virtual by default.

## 70- What is the _final_ variable?
In Java, the final variable is used to restrict the user from updating it. If we initialize the final variable, we can't change its value. In other words, we can say that the final variable once assigned to a value, can never be changed after that. The final variable which is not assigned to any value can only be assigned through the class constructor.

## 71- What is the final method?
If we change any method to a final method, we can't override it.

## 72- What is the final class?
If we make any class final, we can't inherit it into any of the subclasses.

## 73- What is the final blank variable?
A final variable, not initialized at the time of declaration, is known as the final blank variable. We can't initialize the final blank variable directly. Instead, we have to initialize it by using the class constructor. It is useful in the case when the user has some data which must not be changed by others, for example, PAN Number. 

## 74- Can we initialize the final blank variable?
Yes, if it is not static, we can initialize it in the constructor. If it is static blank final variable, it can be initialized only in the static block.

## 75- Can you declare the main method as final?
Yes, We can declare the main method as public static final void main(String[] args){}.

## 76- Can we declare a constructor as final?
The constructor can never be declared as final because it is never inherited. Constructors are not ordinary methods; therefore, there is no sense to declare constructors as final. However, if you try to do so, The compiler will throw an error.

## 77- Can we declare an interface as final?
No, we cannot declare an interface as final because the interface must be implemented by some class to provide its definition. Therefore, there is no sense to make an interface final. However, if you try to do so, the compiler will show an error.

## 78- What is the difference between the final method and abstract method?
The main difference between the final method and abstract method is that the abstract method cannot be final as we need to override them in the subclass to give its definition.

## 79- What is the difference between compile-time polymorphism and runtime polymorphism?
| SN | compile-time polymorphism | Runtime polymorphism |
| ----------- | ----------- | ----------- |
| 1 | In compile-time polymorphism, call to a method is resolved at compile-time. | In runtime polymorphism, call to an overridden method is resolved at runtime. |
| 2 | It is also known as static binding, early binding, or overloading | It is also known as dynamic binding, late binding, overriding, or dynamic method dispatch. |
| 3 | Overloading is a way to achieve compile-time polymorphism in which, we can define multiple methods or constructors with different signatures. | Overriding is a way to achieve runtime polymorphism in which, we can redefine some particular method or variable in the derived class. By using overriding, we can give some specific implementation to the base class properties in the derived class. |
| 4 | It provides fast execution because the type of an object is determined at compile-time. | It provides slower execution as compare to compile-time because the type of an object is determined at run-time. |
| 5 | Compile-time polymorphism provides less flexibility because all the things are resolved at compile-time. | Run-time polymorphism provides more flexibility because all the things are resolved at runtime. |

## 80- What is Runtime Polymorphism?
Runtime polymorphism or dynamic method dispatch is a process in which a call to an overridden method is resolved at runtime rather than at compile-time. In this process, an overridden method is called through the reference variable of a superclass. The determination of the method to be called is based on the object being referred to by the reference variable.

```
class Bike{  
  void run(){System.out.println("running");}  
}  
class Splendor extends Bike{  
  void run(){System.out.println("running safely with 60km");}  
  public static void main(String args[]){  
    Bike b = new Splendor();//upcasting  
    b.run();  
  }  
} 
```

Output

```
running safely with 60km. 
```
In this process, an overridden method is called through the reference variable of a superclass. The determination of the method to be called is based on the object being referred to by the reference variable.

## 81- Can you achieve Runtime Polymorphism by data members?
No, because method overriding is used to achieve runtime polymorphism and data members cannot be overridden. We can override the member functions but not the data members. Consider the example given below.

```
class Bike{  
 int speedlimit=90;  
}  
class Honda3 extends Bike{  
 int speedlimit=150;  
 public static void main(String args[]){  
  Bike obj=new Honda3();  
  System.out.println(obj.speedlimit);//90  
 }  
 ```
 Output 
 
```
90 
```
 
## 82- What is the difference between static binding and dynamic binding?
In case of the static binding, the type of the object is determined at compile-time whereas, in the dynamic binding, the type of the object is determined at runtime.
**Static Binding**
```
class Dog{  
 private void eat(){System.out.println("dog is eating...");}  
  
 public static void main(String args[]){  
  Dog d1=new Dog();  
  d1.eat();  
 }  
}  
```

**Dynamic Binding**
```
class Animal{  
 void eat(){System.out.println("animal is eating...");}  
}  
  
class Dog extends Animal{  
 void eat(){System.out.println("dog is eating...");}  
  
 public static void main(String args[]){  
  Animal a=new Dog();  
  a.eat();  
 }  
}   
```

## 83- What is the abstraction?
Abstraction is a process of hiding the implementation details and showing only functionality to the user. It displays just the essential things to the user and hides the internal information, for example, sending SMS where you type the text and send the message. You don't know the internal processing about the message delivery. Abstraction enables you to focus on what the object does instead of how it does it. Abstraction lets you focus on what the object does instead of how it does it.

In Java, there are two ways to achieve the abstraction.

- Abstract Class
- Interface

## 84- What is the difference between abstraction and encapsulation?
Abstraction hides the implementation details whereas encapsulation wraps code and data into a single unit.

## 85- What is the abstract class?
A class that is declared as abstract is known as an abstract class. It needs to be extended and its method implemented. It cannot be instantiated. It can have abstract methods, non-abstract methods, constructors, and static methods. It can also have the final methods which will force the subclass not to change the body of the method.

## 86- Can there be an abstract method without an abstract class?
No, if there is an abstract method in a class, that class must be abstract.

## 87- Can you use abstract and final both with a method?
No, because we need to override the abstract method to provide its implementation, whereas we can't override the final method.

## 88- Is it possible to instantiate the abstract class?
No, the abstract class can never be instantiated even if it contains a constructor and all of its methods are implemented.

## 89- What is the interface?
The interface is a blueprint for a class that has static constants and abstract methods. It can be used to achieve full abstraction and multiple inheritance. It is a mechanism to achieve abstraction. There can be only abstract methods in the Java interface, not method body. It is used to achieve abstraction and multiple inheritance in Java. In other words, you can say that interfaces can have abstract methods and variables. Java Interface also represents the IS-A relationship. It cannot be instantiated just like the abstract class. However, we need to implement it to define its methods. Since Java 8, we can have the default, static, and private methods in an interface.

## 90- Can you declare an interface method static?
No, because methods of an interface are abstract by default, and we can not use static and abstract together.

## 91- Can the Interface be final?
No, because an interface needs to be implemented by the other class and if it is final, it can't be implemented by any class.

## 92- What is a marker interface?
A Marker interface can be defined as the interface which has no data member and member functions. For example, Serializable, Cloneable are marker interfaces. The marker interface can be declared as follows.

## 93- What are the differences between abstract class and interface?

| Abstract class | Interface |
| ----------- | ----------- |
| An abstract class can have a method body (non-abstract methods). | The interface has only abstract methods. |
| An abstract class can have instance variables. | An interface cannot have instance variables. |
| An abstract class can have the constructor. | The interface cannot have the constructor. |
| An abstract class can have static methods | The interface cannot have static methods. |
| You can extend one abstract class. | You can implement multiple interfaces. |
| The abstract class **can provide the implementation of the interface.** | The Interface **can't provide the implementation of the abstract class.** |
| The **abstract keyword** is used to declare an abstract class. | The **interface keyword** is used to declare an interface. |
| An **abstract class** can extend another Java class and implement multiple Java interfaces. | An **interface** can extend another Java interface only. |
| An **abstract class** can be extended using keyword **extends** | An **interface class** can be implemented using keyword **implements** |
| A Java **abstract class** can have class members like private, protected, etc. | Members of a Java interface are public by default. |
| **Example:** ```public abstract class Shape{ public abstract void draw(); }``` | **Example:** ```public interface Drawable{ void draw(); }``` |

## 94- Can we define private and protected modifiers for the members in interfaces?
No, they are implicitly public.

## 95- When can an object reference be cast to an interface reference?
An object reference can be cast to an interface reference when the object implements the referenced interface.

## 96- How to make a read-only class in Java?
A class can be made read-only by making all of the fields private. The read-only class will have only getter methods which return the private property of the class to the main method. We cannot modify this property because there is no setter method available in the class. Consider the following example.

## 97- How to make a write-only class in Java?
A class can be made write-only by making all of the fields private. The write-only class will have only setter methods which set the value passed from the main method to the private fields. We cannot read the properties of the class because there is no getter method in this class. 

## 98- What are the advantages of Encapsulation in Java?
There are the following advantages of Encapsulation in Java?

- By providing only the setter or getter method, you can make the class read-only or write-only. In other words, you can skip the getter or setter methods.
- It provides you the control over the data. Suppose you want to set the value of id which should be greater than 100 only, you can write the logic inside the setter method. You can write the logic not to store the negative numbers in the setter methods.
- It is a way to achieve data hiding in Java because other class will not be able to access the data through the private data members.
- The encapsulate class is easy to test. So, it is better for unit testing.
- The standard IDE's are providing the facility to generate the getters and setters. So, it is easy and fast to create an encapsulated class in Java.

## 99- What is the package?
A package is a group of similar type of classes, interfaces, and sub-packages. It provides access protection and removes naming collision. The packages in Java can be categorized into two forms, inbuilt package, and user-defined package. There are many built-in packages such as Java, lang, awt, javax, swing, net, io, util, sql, etc. Consider the following example to create a package in Java.

## 100- What are the advantages of defining packages in Java?
By defining packages, we can avoid the name conflicts between the same class names defined in different packages. Packages also enable the developer to organize the similar classes more effectively. For example, one can clearly understand that the classes present in java.io package are used to perform io related operations.

## 101- How can we access some class in another class in Java?
There are two ways to access a class in another class.

- **By using the fully qualified name:** To access a class in a different package, either we must use the fully qualified name of that class, or we must import the package containing that class.
- **By using the relative path,** We can use the path of the class that is related to the package that contains our class. It can be the same or subpackage.

## 102- Can I import same package/class twice? Will the JVM load the package twice at runtime?
One can import the same package or the same class multiple times. Neither compiler nor JVM complains about it. However, the JVM will internally load the class only once no matter how many times you import the same class.

## 103- What is the static import?
By static import, we can access the static members of a class directly, and there is no to qualify it with the class name.

## 104- How many types of exception can occur in a Java program?
There are mainly two types of exceptions: checked and unchecked. Here, an error is considered as the unchecked exception. According to Oracle, there are three types of exceptions:

- **Checked Exception:** Checked exceptions are the one which are checked at compile-time. For example, SQLException, ClassNotFoundException, etc.

- **Unchecked Exception:** Unchecked exceptions are the one which are handled at runtime because they can not be checked at compile-time. For example, ArithmaticException, NullPointerException, ArrayIndexOutOfBoundsException, etc.

- **Error:** Error cause the program to exit since they are not recoverable. For Example, OutOfMemoryError, AssertionError, etc.

## 105- What is Exception Handling?
Exception Handling is a mechanism that is used to handle runtime errors. It is used primarily to handle checked exceptions. Exception handling maintains the normal flow of the program. There are mainly two types of exceptions: checked and unchecked. Here, the error is considered as the unchecked exception.

## 106- Explain the hierarchy of Java Exception classes?
The java.lang.Throwable class is the root class of Java Exception hierarchy which is inherited by two subclasses: Exception and Error. A hierarchy of Java Exception classes are given below:
![image](https://user-images.githubusercontent.com/16039211/142698075-deb5bdf6-a810-40bf-8a46-6d80b639cc6f.png)

## 107- What is the difference between Checked Exception and Unchecked Exception?
**1) Checked Exception**
The classes that extend Throwable class except RuntimeException and Error are known as checked exceptions, e.g., IOException, SQLException, etc. Checked exceptions are checked at compile-time.

**2) Unchecked Exception**
The classes that extend RuntimeException are known as unchecked exceptions, e.g., ArithmeticException, NullPointerException, etc. Unchecked exceptions are not checked at compile-time.

## 108- What is the base class for Error and Exception?
The Throwable class is the base class for Error and Exception.

## 109- Is it necessary that each try block must be followed by a catch block?
It is not necessary that each try block must be followed by a catch block. It should be followed by either a catch block OR a finally block. So whatever exceptions are likely to be thrown should be declared in the throws clause of the method.

## 110- What is finally block?
The "finally" block is used to execute the important code of the program. It is executed whether an exception is handled or not. In other words, we can say that finally block is the block which is always executed. Finally block follows try or catch block. If you don't handle the exception, before terminating the program, JVM runs finally block, (if any). The finally block is mainly used to place the cleanup code such as closing a file or closing a connection. Here, we must know that for each try block there can be zero or more catch blocks, but only one finally block. The finally block will not be executed if program exits(either by calling System.exit() or by causing a fatal error that causes the process to abort).
![image](https://user-images.githubusercontent.com/16039211/142698541-ec547e55-8c55-4f6d-be9d-b63fcdde408d.png)

## 111- Can finally block be used without a catch?
Yes, According to the definition of finally block, it must be followed by a try or catch block, therefore, we can use try block instead of catch

## 112- Is there any case when finally will not be executed?
Finally block will not be executed if program exits(either by calling System.exit() or by causing a fatal error that causes the process to abort).

## 113- What is the difference between throw and throws?
| throw keyword | throws keyword |
| ----------- | ----------- |
| 1) The **throw** keyword is used to throw an exception explicitly. | The **throws** keyword is used to declare an exception. |
| 2) The checked exceptions cannot be propagated with throw only. | The checked exception can be propagated with throws |
| 3) The **throw** keyword is followed by an instance. | The **throws** keyword is followed by class. |
| 4) The **throw** keyword is used within the method. | The **throws** keyword is used with the method signature. |
| 5) You cannot throw multiple exceptions. | You can declare multiple exceptions, e.g., public void method()throws IOException, SQLException. |

## 114- Can an exception be rethrown?
Yes.

## 115- Can subclass overriding method declare an exception if parent class method doesn't throw an exception?
Yes but only unchecked exception not checked.

## 116- What is exception propagation?
An exception is first thrown from the top of the stack and if it is not caught, it drops down the call stack to the previous method, If not caught there, the exception again drops down to the previous method, and so on until they are caught or until they reach the very bottom of the call stack. This procedure is called exception propagation.

## 117- What is String Pool?
String pool is the space reserved in the heap memory that can be used to store the strings. The main advantage of using the String pool is whenever we create a string literal; the JVM checks the "string constant pool" first. If the string already exists in the pool, a reference to the pooled instance is returned. If the string doesn't exist in the pool, a new string instance is created and placed in the pool. Therefore, it saves the memory by avoiding the duplicacy.
![image](https://user-images.githubusercontent.com/16039211/142699005-1724134f-b2bf-47da-96ed-c9a861ecb2eb.png)

## 118- What is the meaning of immutable regarding String?
The simple meaning of immutable is unmodifiable or unchangeable. In Java, String is immutable, i.e., once string object has been created, its value can't be changed. Consider the following example for better understanding.

## 119- Why are the objects immutable in java?
Because Java uses the concept of the string literal. Suppose there are five reference variables, all refer to one object "sachin". If one reference variable changes the value of the object, it will be affected by all the reference variables. That is why string objects are immutable in java.
![image](https://user-images.githubusercontent.com/16039211/142699062-ba8e5792-db6b-4a42-9388-4a590d47c987.png)

## 120- How many ways can we create the string object?
**1) String Literal**
Java String literal is created by using double quotes. For Example:
```
String s="welcome";  
```  
Each time you create a string literal, the JVM checks the "string constant pool" first. If the string already exists in the pool, a reference to the pooled instance is returned. If the string doesn't exist in the pool, a new string instance is created and placed in the pool. String objects are stored in a special memory area known as the **string constant pool** For example:
```
String s1="Welcome";  
String s2="Welcome";//It doesn't create a new instance
```  
**2) By new keyword**
```
String s=new String("Welcome");//creates two objects and one reference variable
```  
In such case, JVM will create a new string object in normal (non-pool) heap memory, and the literal "Welcome" will be placed in the constant string pool. The variable s will refer to the object in a heap (non-pool).

## 120- How many objects will be created in the following code?
```
String s1="Welcome";  
String s2="Welcome";  
String s3="Welcome";  
``` 
Only one object will be created using the above code because strings in Java are immutable.

## 121- Why java uses the concept of the string literal?
To make Java more memory efficient (because no new objects are created if it exists already in the string constant pool).

## 122- How many objects will be created in the following code?
```
String s = new String("Welcome");
``` 
Two objects, one in string constant pool and other in non-pool(heap).

## 12- What is the output of the following Java program?
```
public class Test   
  
  public static void main (String args[])  
  {  
      String a = new String("Sharma is a good player");  
      String b = "Sharma is a good player";  
      if(a == b)  
      {  
          System.out.println("a == b");  
      }  
      if(a.equals(b))  
      {  
          System.out.println("a equals b");  
      }  
  }  
``` 
Output
```
  a equals b
```
**Explanation:**

The operator == also check whether the references of the two string objects are equal or not. Although both of the strings contain the same content, their references are not equal because both are created by different ways(Constructor and String literal) therefore, **a == b** is unequal. On the other hand, the equal() method always check for the content. Since their content is equal hence, **a equals b** is printed.

## 123- What is the output of the following Java program?
```
  public class Test   
{  
    public static void main (String args[])  
    {  
        String s1 = "Sharma is a good player";  
        String s2 = new String("Sharma is a good player");  
        s2 = s2.intern();  
        System.out.println(s1 ==s2);  
    }  
} 
```
Output
```
  true
```
**Explanation:**

The intern method returns the String object reference from the string pool. In this case, s1 is created by using string literal whereas, s2 is created by using the String pool. However, s2 is changed to the reference of s1, and the operator == returns true.

## 124- What are the differences between String and StringBuffer?
The differences between the String and StringBuffer is given in the table below.
| String | StringBuffer |
| ----------- | ----------- |
| The String class is immutable. | The StringBuffer class is mutable. |
| The String is slow and consumes more memory when you concat too many strings because every time it creates a new instance.	 | The StringBuffer is fast and consumes less memory when you cancat strings.
 |
| The String class overrides the equals() method of Object class. So you can compare the contents of two strings by equals() method.	 | The StringBuffer class doesn't override the equals() method of Object class.
 |

## 125- What are the differences between StringBuffer and StringBuilder?
The differences between the StringBuffer and StringBuilder is given below.
| StringBuffer | StringBuilder |
| ----------- | ----------- |
| StringBuffer is synchronized, i.e., thread safe. It means two threads can't call the methods of StringBuffer simultaneously. | StringBuilder is non-synchronized,i.e., not thread safe. It means two threads can call the methods of StringBuilder simultaneously.
 |
| StringBuffer is less efficient than StringBuilder. | StringBuilder is more efficient than StringBuffer.
 |

## 126- How can we create an immutable class in Java?
We can create an immutable class by defining a final class having all of its members as final. Consider the following example.

```
public final class Employee{  

final String pancardNumber;  
  
public Employee(String pancardNumber){  
this.pancardNumber=pancardNumber;  
}  
  
public String getPancardNumber(){  
return pancardNumber;  
}  
  
} 
```
## 127- What is the purpose of toString() method in Java?
The toString() method returns the string representation of an object. If you print any object, java compiler internally invokes the toString() method on the object. So overriding the toString() method, returns the desired output, it can be the state of an object, etc. depending upon your implementation. By overriding the toString() method of the Object class, we can return the values of the object, so we don't need to write much code. Consider the following example.

```
class Student{  
 int rollno;  
 String name;  
 String city;  
  
 Student(int rollno, String name, String city){  
 this.rollno=rollno;  
 this.name=name;  
 this.city=city;  
 }  
   
 public String toString(){//overriding the toString() method  
  return rollno+" "+name+" "+city;  
 }  
 public static void main(String args[]){  
   Student s1=new Student(101,"Raj","lucknow");  
   Student s2=new Student(102,"Vijay","ghaziabad");  
     
   System.out.println(s1);//compiler writes here s1.toString()  
   System.out.println(s2);//compiler writes here s2.toString()  
 }  
}   
```
**Output:**
```
101 Raj lucknow
102 Vijay ghaziabad
```

## 128- Why CharArray() is preferred over String to store the password?
String stays in the string pool until the garbage is collected. If we store the password into a string, it stays in the memory for a longer period, and anyone having the memory-dump can extract the password as clear text. On the other hand, Using CharArray allows us to set it to blank whenever we are done with the password. It avoids the security threat with the string by enabling us to control the memory.

## 129- Name some classes present in java.util.regex package.
There are the following classes and interfaces present in java.util.regex package.

- MatchResult Interface
- Matcher class
- Pattern class
- PatternSyntaxException class

## 130- How the metacharacters are different from the ordinary characters?
Metacharacters have the special meaning to the regular expression engine. The metacharacters are ^, $, ., *, +, etc. The regular expression engine does not consider them as the regular characters. To enable the regular expression engine treating the metacharacters as ordinary characters, we need to escape the metacharacters with the backslash.

## 131- Write a regular expression to validate a password. A password must start with an alphabet and followed by alphanumeric characters; Its length must be in between 8 to 20.
The regular expression for the above criteria will be: ^[a-zA-Z][a-zA-Z0-9]{8,19} where ^ represents the start of the regex, [a-zA-Z] represents that the first character must be an alphabet, [a-zA-Z0-9] represents the alphanumeric character, {8,19} represents that the length of the password must be in between 8 and 20.

## 132- What are the advantages of Java inner classes?
There are two types of advantages of Java inner classes.

- Nested classes represent a special type of relationship that is it can access all the members (data members and methods) of the outer class including private.
- Nested classes are used to develop a more readable and maintainable code because it logically groups classes and interfaces in one place only.
- **Code Optimization:** It requires less code to write.

## 133- What is a nested class?
The nested class can be defined as the class which is defined inside another class or interface. We use the nested class to logically group classes and interfaces in one place so that it can be more readable and maintainable. A nested class can access all the data members of the outer class including private data members and methods. The syntax of the nested class is defined below
```
class Java_Outer_class{    
 //code    
 class Java_Nested_class{    
  //code    
 }    
} 
```
There are two types of nested classes, static nested class, and non-static nested class. The non-static nested class can also be called as inner-class

## 134- What are the disadvantages of using inner classes?
There are the following main disadvantages of using inner classes.

- Inner classes increase the total number of classes used by the developer and therefore increases the workload of JVM since it has to perform some routine operations for those extra classes which result in slower performance.
- IDEs provide less support to the inner classes as compare to the top level classes and therefore it annoys the developers while working with inner classes.

## 135- What are the types of inner classes (non-static nested class) used in Java?
There are mainly three types of inner classes used in Java.
| Type | Description |
| ----------- | ----------- |
| Member Inner Class | A class created within class and outside method.
 |
| Anonymous Inner Class | A class created for implementing an interface or extending class. Its name is decided by the java compiler.
 |
| Local Inner Class | A class created within the method.
 |
 
## 136- Is there any difference between nested classes and inner classes?
Yes, inner classes are non-static nested classes. In other words, we can say that inner classes are the part of nested classes.

## 137- Can we access the non-final local variable, inside the local inner class?
No, the local variable must be constant if you want to access it in the local inner class.

## 138- How many class files are created on compiling the OuterClass in the following program?
```
public class Person {  
String name, age, address;  
class Employee{  
  float salary=10000;  
}  
class BusinessMen{  
  final String gstin="??4433drt3$";   
}  
public static void main (String args[])  
{  
  Person p = new Person();  
}  
}  
```
3 class-files will be created named as Person.class, Person$BusinessMen.class, and Person$Employee.class.

## 139- Can a class have an interface?
Yes, an interface can be defined within the class. It is called a nested interface.

## 140- Can an Interface have a class?
Yes, they are static implicitly.

## 141- What is Garbage Collection?
Garbage collection is a process of reclaiming the unused runtime objects. It is performed for memory management. In other words, we can say that It is the process of removing unused objects from the memory to free up space and make this space available for Java Virtual Machine. Due to garbage collection java gives 0 as output to a variable whose value is not set, i.e., the variable has been defined but not initialized. For this purpose, we were using free() function in the C language and delete() in C++. In Java, it is performed automatically. So, java provides better memory management.

## 142- What is gc()?
The gc() method is used to invoke the garbage collector for cleanup processing. This method is found in System and Runtime classes. This function explicitly makes the Java Virtual Machine free up the space occupied by the unused objects so that it can be utilized or reused. Consider the following example for the better understanding of how the gc() method invoke the garbage collector.
```
public class TestGarbage1{  

public void finalize(){
    System.out.println("object is garbage collected");
    }  

public static void main(String args[]){  
  TestGarbage1 s1=new TestGarbage1();  
  TestGarbage1 s2=new TestGarbage1();  
  s1=null;  
  s2=null;  
  System.gc();  
 } 
 
} 
}  
```
**Output:**
```
 object is garbage collected
 object is garbage collected  
```

## 143- How is garbage collection controlled?
Garbage collection is managed by JVM. It is performed when there is not enough space in the memory and memory is running low. We can externally call the System.gc() for the garbage collection. However, it depends upon the JVM whether to perform it or not.

## 144- How can an object be unreferenced?
There are many ways:

- By nulling the reference
- By assigning a reference to another
- By anonymous object etc.
- 
![image](https://user-images.githubusercontent.com/16039211/142706376-df05ed94-770d-44fd-b084-a8ba7c633900.png)

**1) By nulling a reference:**
```
Employee e=new Employee();  
e=null;  
```

**2) By assigning a reference to another:**
```
Employee e1=new Employee();  
Employee e2=new Employee();  
e1=e2;//now the first object referred by e1 is available for garbage collection  
```

**3) By anonymous object:**
```
new Employee();  
```

## 145- What is the purpose of the finalize() method?
The finalize() method is invoked just before the object is garbage collected. It is used to perform cleanup processing. The Garbage collector of JVM collects only those objects that are created by new keyword. So if you have created an object without new, you can use the finalize method to perform cleanup processing (destroying remaining objects). The cleanup processing is the process to free up all the resources, network which was previously used and no longer needed. It is essential to remember that it is not a reserved keyword, finalize method is present in the object class hence it is available in every class as object class is the superclass of every class in java. Here, we must note that neither finalization nor garbage collection is guaranteed. Consider the following example.

```
public class FinalizeTest {  
    int j=12;  
    void add()  
    {  
        j=j+12;  
        System.out.println("J="+j);  
    }  
    public void finalize()  
    {  
        System.out.println("Object is garbage collected");  
    }  
    public static void main(String[] args) {  
        new FinalizeTest().add();  
        System.gc();  
        new FinalizeTest().add();  
    }  
}   
```

## 146- Can an unreferenced object be referenced again?
Yes,

## 147- What kind of thread is the Garbage collector thread?
Daemon thread.

## 148- What is the difference between final, finally and finalize?
| final | finally | finalize |
| ----------- | ----------- | ----------- |
| Final is used to apply restrictions on class, method, and variable. The final class can't be inherited, final method can't be overridden, and final variable value can't be changed. | Finally is used to place important code, it will be executed whether an exception is handled or not.	 | Finalize is used to perform clean up processing just before an object is garbage collected.|
| Final is a keyword. | Finally is a block. | Finalize is a method. |

## 149- What is the purpose of the Runtime class?
Java Runtime class is used to interact with a java runtime environment. Java Runtime class provides methods to execute a process, invoke GC, get total and free memory, etc. There is only one instance of java.lang.Runtime class is available for one java application. The Runtime.getRuntime() method returns the singleton instance of Runtime class.

## 150- What do you understand by an IO stream?
The stream is a sequence of data that flows from source to destination. It is composed of bytes. In Java, three streams are created for us automatically.

- System.out: standard output stream
- System.in: standard input stream
- System.err: standard error stream

## 151- What is the difference between the Reader/Writer class hierarchy and the InputStream/OutputStream class hierarchy?
The Reader/Writer class hierarchy is character-oriented, and the InputStream/OutputStream class hierarchy is byte-oriented. The ByteStream classes are used to perform input-output of 8-bit bytes whereas the CharacterStream classes are used to perform the input/output for the 16-bit Unicode system. There are many classes in the ByteStream class hierarchy, but the most frequently used classes are FileInputStream and FileOutputStream. The most frequently used classes CharacterStream class hierarchy is FileReader and FileWriter.

## 152- What are the super most classes for all the streams?
All the stream classes can be divided into two types of classes that are ByteStream classes and CharacterStream Classes. The ByteStream classes are further divided into InputStream classes and OutputStream classes. CharacterStream classes are also divided into Reader classes and Writer classes. The SuperMost classes for all the InputStream classes is java.io.InputStream and for all the output stream classes is java.io.OutPutStream. Similarly, for all the reader classes, the super-most class is java.io.Reader, and for all the writer classes, it is java.io.Writer.

## 153- What are the FileInputStream and FileOutputStream?
**Java FileOutputStream** is an output stream used for writing data to a file. If you have some primitive values to write into a file, use FileOutputStream class. You can write byte-oriented as well as character-oriented data through the FileOutputStream class. However, for character-oriented data, it is preferred to use FileWriter than FileOutputStream. Consider the following example of writing a byte into a file.
```
import java.io.FileOutputStream;   

public class FileOutputStreamExample {    
    public static void main(String args[]){      
           try{      
             FileOutputStream fout=new FileOutputStream("D:\\testout.txt");      
             fout.write(65);      
             fout.close();      
             System.out.println("success...");      
            }catch(Exception e){System.out.println(e);}      
      }      
}    
```

**Java FileInputStream** class obtains input bytes from a file. It is used for reading byte-oriented data (streams of raw bytes) such as image data, audio, video, etc. You can also read character-stream data. However, for reading streams of characters, it is recommended to use FileReader class. Consider the following example for reading bytes from a file.

```
import java.io.FileInputStream;    
public class DataStreamExample {    
     public static void main(String args[]){      
          try{      
            FileInputStream fin=new FileInputStream("D:\\testout.txt");      
            int i=fin.read();    
            System.out.print((char)i);      
    
            fin.close();      
          }catch(Exception e){System.out.println(e);}      
         }      
        }    
```

## 154- What is the purpose of using BufferedInputStream and BufferedOutputStream classes?
Java BufferedOutputStream class is used for buffering an output stream. It internally uses a buffer to store data. It adds more efficiency than to write data directly into a stream. So, it makes the performance fast. Whereas, Java BufferedInputStream class is used to read information from the stream. It internally uses the buffer mechanism to make the performance fast.

## 155- How to set the Permissions to a file in Java?
In Java, FilePermission class is used to alter the permissions set on a file. Java FilePermission class contains the permission related to a directory or file. All the permissions are related to the path. The path can be of two types:

- D:\\IO\\-: It indicates that the permission is associated with all subdirectories and files recursively.
- D:\\IO\\*: It indicates that the permission is associated with all directory and files within this directory excluding subdirectories.

Let's see the simple example in which permission of a directory path is granted with read permission and a file of this directory is granted for write permission.

```
package com.javatpoint;  
import java.io.*;  
import java.security.PermissionCollection;  
public class FilePermissionExample{  
     public static void main(String[] args) throws IOException {  
      String srg = "D:\\IO Package\\java.txt";  
      FilePermission file1 = new FilePermission("D:\\IO Package\\-", "read");  
      PermissionCollection permission = file1.newPermissionCollection();  
      permission.add(file1);  
           FilePermission file2 = new FilePermission(srg, "write");  
           permission.add(file2);  
         if(permission.implies(new FilePermission(srg, "read,write"))) {  
           System.out.println("Read, Write permission is granted for the path "+srg );  
             }else {  
            System.out.println("No Read, Write permission is granted for the path "+srg);            }  
     }   
}     
```
**Outuput**
```
Read, Write permission is granted for the path D:\IO Package\java.txt
```

## 156- What are FilterStreams?
**FilterStream classes** are used to add additional functionalities to the other stream classes. FilterStream classes act like an interface which read the data from a stream, filters it, and pass the filtered data to the caller. The FilterStream classes provide extra functionalities like adding line numbers to the destination file, etc.

## 157- What is an I/O filter?
An I/O filter is an object that reads from one stream and writes to another, usually altering the data in some way as it is passed from one stream to another. Many Filter classes that allow a user to make a chain using multiple input streams. It generates a combined effect on several filters.

## 158- In Java, How many ways you can take input from the console?
In Java, there are three ways by using which, we can take input from the console.

**Using BufferedReader class:** we can take input from the console by wrapping System.in into an InputStreamReader and passing it into the BufferedReader. It provides an efficient reading as the input gets buffered. Consider the following example.
```
import java.io.BufferedReader;   
import java.io.IOException;   
import java.io.InputStreamReader;   
public class Person   
{   
    public static void main(String[] args) throws IOException    
    {   
      System.out.println("Enter the name of the person");  
        BufferedReader reader = new BufferedReader(new InputStreamReader(System.in));   
        String name = reader.readLine();   
        System.out.println(name);           
    }   
}   
```

**Using Scanner class:** The Java Scanner class breaks the input into tokens using a delimiter that is whitespace by default. It provides many methods to read and parse various primitive values. Java Scanner class is widely used to parse text for string and primitive types using a regular expression. Java Scanner class extends Object class and implements Iterator and Closeable interfaces. Consider the following example.
```
import java.util.*;    
public class ScannerClassExample2 {      
      public static void main(String args[]){                         
          String str = "Hello/This is JavaTpoint/My name is Abhishek.";    
          //Create scanner with the specified String Object    
          Scanner scanner = new Scanner(str);    
          System.out.println("Boolean Result: "+scanner.hasNextBoolean());              
          //Change the delimiter of this scanner    
          scanner.useDelimiter("/");    
          //Printing the tokenized Strings    
          System.out.println("---Tokenizes String---");     
        while(scanner.hasNext()){    
            System.out.println(scanner.next());    
        }    
          //Display the new delimiter    
          System.out.println("Delimiter used: " +scanner.delimiter());              
          scanner.close();    
          }      
}  
```
**Using Console class:** The Java Console class is used to get input from the console. It provides methods to read texts and passwords. If you read the password using the Console class, it will not be displayed to the user. The java.io.Console class is attached to the system console internally. The Console class is introduced since 1.5. Consider the following example.
```
import java.io.Console;    
class ReadStringTest{      
public static void main(String args[]){      
Console c=System.console();      
System.out.println("Enter your name: ");      
String n=c.readLine();      
System.out.println("Welcome "+n);      
}      
}  
```

## 159- What is serialization?
Serialization in Java is a mechanism of writing the state of an object into a byte stream. It is used primarily in Hibernate, RMI, JPA, EJB and JMS technologies. It is mainly used to travel object's state on the network (which is known as marshaling). Serializable interface is used to perform serialization. It is helpful when you require to save the state of a program to storage such as the file. At a later point of time, the content of this file can be restored using deserialization. It is also required to implement RMI(Remote Method Invocation). With the help of RMI, it is possible to invoke the method of a Java object on one machine to another machine.

![image](https://user-images.githubusercontent.com/16039211/142707373-119a0935-daae-487a-a3f3-8dcceb09e06e.png)

## 160- How can you make a class serializable in Java?
A class can become serializable by implementing the Serializable interface.

## 161- How can you avoid serialization in child class if the base class is implementing the Serializable interface?
It is very tricky to prevent serialization of child class if the base class is intended to implement the Serializable interface. However, we cannot do it directly, but the serialization can be avoided by implementing the writeObject() or readObject() methods in the subclass and throw NotSerializableException from these methods. Consider the following example.
```
import java.io.FileInputStream;   
import java.io.FileOutputStream;   
import java.io.IOException;   
import java.io.NotSerializableException;   
import java.io.ObjectInputStream;   
import java.io.ObjectOutputStream;   
import java.io.Serializable;   
class Person implements Serializable   
{   
    String name = " ";  
    public Person(String name)    
    {   
        this.name = name;   
    }         
}   
class Employee extends Person  
{   
    float salary;  
    public Employee(String name, float salary)    
    {   
        super(name);   
        this.salary = salary;   
    }   
    private void writeObject(ObjectOutputStream out) throws IOException   
    {   
        throw new NotSerializableException();   
    }   
    private void readObject(ObjectInputStream in) throws IOException   
    {   
        throw new NotSerializableException();   
    }   
        
}   
public class Test   
{   
    public static void main(String[] args)    
            throws Exception    
    {   
        Employee emp = new Employee("Sharma", 10000);   
            
        System.out.println("name = " + emp.name);   
        System.out.println("salary = " + emp.salary);   
            
        FileOutputStream fos = new FileOutputStream("abc.ser");   
        ObjectOutputStream oos = new ObjectOutputStream(fos);   
                
        oos.writeObject(emp);   
                
        oos.close();   
        fos.close();   
                
        System.out.println("Object has been serialized");   
            
        FileInputStream f = new FileInputStream("ab.txt");   
        ObjectInputStream o = new ObjectInputStream(f);   
                
        Employee emp1 = (Employee)o.readObject();   
                
        o.close();   
        f.close();   
                
        System.out.println("Object has been deserialized");   
            
        System.out.println("name = " + emp1.name);   
        System.out.println("salary = " + emp1.salary);   
    } 
 } 
```

## 162- Can a Serialized object be transferred via network?
Yes, we can transfer a serialized object via network because the serialized object is stored in the memory in the form of bytes and can be transmitted over the network. We can also write the serialized object to the disk or the database

## 163- What is Deserialization?
Deserialization is the process of reconstructing the object from the serialized state. It is the reverse operation of serialization. An ObjectInputStream deserializes objects and primitive data written using an ObjectOutputStream.
```
import java.io.*;  
class Depersist{  
 public static void main(String args[])throws Exception{  
    
  ObjectInputStream in=new ObjectInputStream(new FileInputStream("f.txt"));  
  Student s=(Student)in.readObject();  
  System.out.println(s.id+" "+s.name);  
  
  in.close();  
 }  
} 
```
**Output**
```
211 ravi
```

## 164- Give a brief description of Java socket programming?
Java Socket programming is used for communication between the applications running on different JRE. Java Socket programming can be connection-oriented or connectionless. Socket and ServerSocket classes are used for connection-oriented socket programming and DatagramSocket, and DatagramPacket classes are used for connectionless socket programming. The client in socket programming must know two information:

- IP address of the server
- port number

## 165- What is Socket?
A socket is simply an endpoint for communications between the machines. It provides the connection mechanism to connect the two computers using TCP. The Socket class can be used to create a socket.

## 166- What are the steps that are followed when two computers connect through TCP?
There are the following steps that are performed when two computers connect through TCP.

- The ServerSocket object is instantiated by the server which denotes the port number to which, the connection will be made.
- After instantiating the ServerSocket object, the server invokes accept() method of ServerSocket class which makes server wait until the client attempts to connect to the server on the given port.
- Meanwhile, the server is waiting, a socket is created by the client by instantiating Socket class. The socket class constructor accepts the server port number and server name.
- The Socket class constructor attempts to connect with the server on the specified name. If the connection is established, the client will have a socket object that can communicate with the server.
- The accept() method invoked by the server returns a reference to the new socket on the server that is connected with the server.

## 167- Write a program in Java to establish a connection between client and server?
Consider the following program where the connection between the client and server is established.

_File: MyServer.java_
```
import java.io.*;  
import java.net.*;  
public class MyServer {  
public static void main(String[] args){  
    try{  
        ServerSocket ss=new ServerSocket(6666);  
        Socket s=ss.accept();//establishes connection   
        DataInputStream dis=new DataInputStream(s.getInputStream());  
        String  str=(String)dis.readUTF();  
        System.out.println("message= "+str);  
        ss.close();  
            }catch(Exception e){System.out.println(e);}  
        }  
} 
```
_File: MyClient.java_
```
import java.io.*;  
import java.net.*;  
public class MyClient {  
public static void main(String[] args) {  
    try{    
        Socket s=new Socket("localhost",6666);  
        DataOutputStream dout=new DataOutputStream(s.getOutputStream());  
        dout.writeUTF("Hello Server");  
        dout.flush();  
        dout.close();  
        s.close();  
        }catch(Exception e){
            System.out.println(e);
        }  
    }  
} 
```

## 168- How do I convert a numeric IP address like 192.18.97.39 into a hostname like java.sun.com?
By InetAddress.getByName("192.18.97.39").getHostName() where 192.18.97.39 is the IP address. Consider the following example.
```
import java.io.*;    
import java.net.*;    
public class InetDemo{    
public static void main(String[] args){    
    try{    
        InetAddress ip=InetAddress.getByName("195.201.10.8");    

        System.out.println("Host Name: "+ip.getHostName());    
        }catch(Exception e){System.out.println(e);}    
        }    
} 
```

## 169- What is the reflection?
Reflection is the process of examining or modifying the runtime behavior of a class at runtime. The java.lang.Class class provides various methods that can be used to get metadata, examine and change the runtime behavior of a class. The java.lang and java.lang.reflect packages provide classes for java reflection. It is used in:

- IDE (Integrated Development Environment), e.g., Eclipse, MyEclipse, NetBeans.
- Debugger
- Test Tools, etc.

## 170- What is the purpose of using java.lang.Class class?
The java.lang.Class class performs mainly two tasks:

- Provides methods to get the metadata of a class at runtime.
- Provides methods to examine and change the runtime behavior of a class.

## 171- What are the ways to instantiate the Class class?
There are three ways to instantiate the Class class.

**forName() method of Class class:** The forName() method is used to load the class dynamically. It returns the instance of Class class. It should be used if you know the fully qualified name of the class. This cannot be used for primitive types.

**getClass() method of Object class:** It returns the instance of Class class. It should be used if you know the type. Moreover, it can be used with primitives.

**the .class syntax:** If a type is available, but there is no instance then it is possible to obtain a Class by appending ".class" to the name of the type. It can be used for primitive data type also.

## 172- Can you access the private method from outside the class?
Yes, by changing the runtime behavior of a class if the class is not secured.

## 178- What are wrapper classes?
Wrapper classes are classes that allow primitive types to be accessed as objects. In other words, we can say that wrapper classes are built-in java classes which allow the conversion of objects to primitives and primitives to objects. The process of converting primitives to objects is called autoboxing, and the process of converting objects to primitives is called unboxing. There are eight wrapper classes present in **java.lang** package is given below.

| Primitive Type | Wrapper class | 
| ----------- | ----------- |
| boolean | Boolean |
| char | Character |
| byte | Byte |
| short | Short |
| int | Integer |
| long | Long |
| float | Float |
| double | Double |

## 179- What are autoboxing and unboxing? When does it occur?
The autoboxing is the process of converting primitive data type to the corresponding wrapper class object, eg., int to Integer. The unboxing is the process of converting wrapper class object to primitive data type. For eg., integer to int. Unboxing and autoboxing occur automatically in Java. However, we can externally convert one into another by using the methods like valueOf() or xxxValue().

It can occur whenever a wrapper class object is expected, and primitive data type is provided or vice versa.

- Adding primitive types into Collection like ArrayList in Java.
- Creating an instance of parameterized classes ,e.g., ThreadLocal which expect Type.
- Java automatically converts primitive to object whenever one is required and another is provided in the method calling.
- When a primitive type is assigned to an object type.

## 180- What is object cloning?
The object cloning is a way to create an exact copy of an object. The clone() method of the Object class is used to clone an object. The java.lang.Cloneable interface must be implemented by the class whose object clone we want to create. If we don't implement Cloneable interface, clone() method generates CloneNotSupportedException. The clone() method is defined in the Object class. The syntax of the clone() method is as follows:

**protected Object clone() throws CloneNotSupportedException**

## 181- What are the advantages and disadvantages of object cloning?
**Advantage of Object Cloning**

- You don't need to write lengthy and repetitive codes. Just use an abstract class with a 4- or 5-line long clone() method.
- It is the easiest and most efficient way of copying objects, especially if we are applying it to an already developed or an old project. Just define a parent class, implement Cloneable in it, provide the definition of the clone() method and the task will be done.
- Clone() is the fastest way to copy the array.

**Disadvantage of Object Cloning**

- To use the Object.clone() method, we have to change many syntaxes to our code, like implementing a Cloneable interface, defining the clone() method and handling CloneNotSupportedException, and finally, calling Object.clone(), etc.
- We have to implement the Cloneable interface while it does not have any methods in it. We have to use it to tell the JVM that we can perform a clone() on our object.
- Object.clone() is protected, so we have to provide our own clone() and indirectly call Object.clone() from it.
- Object.clone() does not invoke any constructor, so we do not have any control over object construction.
- If you want to write a clone method in a child class, then all of its superclasses should define the clone() method in them or inherit it from another parent class. Otherwise, the super.clone() chain will fail.
- Object.clone() supports only shallow copying, but we will need to override it if we need deep cloning.

## 182- What is a native method?
A native method is a method that is implemented in a language other than Java. Natives methods are sometimes also referred to as foreign methods.

## 183- What is the purpose of the strictfp keyword?
Java strictfp keyword ensures that you will get the same result on every platform if you perform operations in the floating-point variable. The precision may differ from platform to platform that is why java programming language has provided the strictfp keyword so that you get the same result on every platform. So, now you have better control over the floating-point arithmetic.

## 184- What is the purpose of the System class?
The purpose of the System class is to provide access to system resources such as standard input and output. It cannot be instantiated. Facilities provided by System class are given below.

- Standard input
- Error output streams
- Standard output
- utility method to copy the portion of an array
- utilities to load files and libraries
There are the three fields of Java System class, i.e., static printstream err, static inputstream in, and standard output stream.

## 185- What comes to mind when someone mentions a shallow copy in Java?
Object cloning.

## 186- What is a singleton class?
Singleton class is the class which can not be instantiated more than once. To make a class singleton, we either make its constructor private or use the static getInstance method. Consider the following example.
```
class Singleton{  
    private static Singleton single_instance = null;  
    int i;  
     private Singleton ()  
     {  
         i=90;  
     }  
     public static Singleton getInstance()  
     {  
         if(single_instance == null)  
         {  
             single_instance = new Singleton();  
         }  
         return single_instance;  
     }  
}  
public class Main   
{  
    public static void main (String args[])  
    {  
        Singleton first = Singleton.getInstance();  
        System.out.println("First instance integer value:"+first.i);  
        first.i=first.i+90;  
        Singleton second = Singleton.getInstance();  
        System.out.println("Second instance integer value:"+second.i);  
    }  
} 
```
## 187- What is Locale?
A Locale object represents a specific geographical, political, or cultural region. This object can be used to get the locale-specific information such as country name, language, variant, etc.

## 188- What is a JavaBean?
JavaBean is a reusable software component written in the Java programming language, designed to be manipulated visually by a software development environment, like JBuilder or VisualAge for Java. t. A JavaBean encapsulates many objects into one object so that we can access this object from multiple places.

## 189- What is the purpose of using the Java bean?
According to Java white paper, it is a reusable software component. A bean encapsulates many objects into one object so that we can access this object from multiple places. Moreover, it provides the easy maintenance.

## 190- What is RMI?
The RMI (Remote Method Invocation) is an API that provides a mechanism to create the distributed application in java. The RMI allows an object to invoke methods on an object running in another JVM. The RMI provides remote communication between the applications using two objects stub and skeleton.

## 191- What are the steps involved to write RMI based programs?
There are 6 steps which are performed to write RMI based programs.

- Create the remote interface.
- Provide the implementation of the remote interface.
- Compile the implementation class and create the stub and skeleton objects using the rmic tool.
- Start the registry service by the rmiregistry tool.
- Create and start the remote application.
- Create and start the client application.

## 192- What is the use of HTTP-tunneling in RMI?
HTTP tunneling can be defined as the method which doesn't need any setup to work within the firewall environment. It handles the HTTP connections through the proxy servers. However, it does not allow outbound TCP connections.

## 193- What is JRMP?
JRMP (Java Remote Method Protocol) can be defined as the Java-specific, stream-based protocol which looks up and refers to the remote objects. It requires both client and server to use Java objects. It is wire level protocol which runs under RMI and over TCP/IP.

## 194- Can RMI and CORBA based applications interact?
Yes, they can. RMI is available with IIOP as the transport protocol instead of JRMP.











