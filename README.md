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
Just-In-Time(JIT) compiler: It is used to improve the performance. JIT compiles parts of the bytecode that have similar functionality at the same time, and hence reduces the amount of time needed for compilation. Here the term “compiler” refers to a translator from the instruction set of a Java virtual machine (JVM) to the instruction set of a specific CPU.

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
| **Example:**
```public abstract class Shape{
public abstract void draw();
}``` | **Example:**
```public interface Drawable{
void draw();
}``` |



