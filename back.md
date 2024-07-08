### What is Java?

Java is a high-level, object-oriented programming language known for its platform independence and write once, run anywhere (WORA) philosophy. It's widely used for developing backend applications, web servers, and enterprise-level systems.

- Object-Oriented-Programming kieli kaytetty yleensa backendis ja servereissa jne

### What are the main features of Java?

Java features include platform independence, object-oriented programming (OOP), strong type checking, automatic memory management (garbage collection), and robust exception handling.

- OOP, tyyppi checking siks hyva typescriptin kans

### Explain the difference between JDK, JRE, and JVM.

JDK (Java Development Kit) is a software development kit used for developing Java applications. JRE (Java Runtime Environment) is a runtime environment required to run Java applications. JVM (Java Virtual Machine) is an abstract machine that provides a runtime environment for Java bytecode execution.

- JDKlla tehaan java appeja
- JRE pyorittaa java appeja
- JVM tarvitaan vaan et toimii

### What is object-oriented programming (OOP)?

Object-oriented programming is a programming paradigm based on the concept of "objects," which can contain data in the form of fields (attributes or properties) and code in the form of procedures (methods or functions). Java is an object-oriented programming language.

- Kaytetaan paljon objekteja

### Explain the concept of inheritance in Java.

Inheritance is a mechanism in Java where a class (subclass or child class) inherits properties and behaviors (methods) from another class (superclass or parent class). It promotes code reuse and facilitates the creation of hierarchical relationships between classes.

- Perii props muilta luokilta, esim User = username, password ja Extra User = born ja gender

### What is the difference between an abstract class and an interface in Java?

An abstract class can contain both abstract and concrete methods, while an interface can only contain abstract method declarations. A class can implement multiple interfaces but can inherit from only one abstract class.

### What is the purpose of the static keyword in Java?

The static keyword in Java is used to declare members (variables and methods) that belong to the class rather than instances of the class. Static members can be accessed directly using the class name without creating an object.

- kaytetaan niille jotka kuuluu luokkaan ja niita voi kayttaa ilman etta luo objektin

### What are the access modifiers in Java, and what do they mean?

Java access modifiers include public, private, protected, and default (no modifier). They control the visibility and accessibility of classes, variables, methods, and constructors. public members are accessible from any other class, private members are accessible only within the same class, protected members are accessible within the same package or subclass, and default members are accessible within the same package.

- PUBLIC = voidaan kayttaa missa vaan luokassa (CLASS)
- PRIVATE = voidaan kayttaa vaan samassa luokassa (CLASS)
- PROTECTED = samassa packagessa tai subclassissa
- DEFAULT = samassa packagessa

# Explain the difference between ArrayList and LinkedList in Java.

ArrayList is implemented as a dynamic array, allowing fast random access and traversal but slower insertion and deletion of elements. LinkedList is implemented as a doubly linked list, allowing fast insertion and deletion but slower random access.

- ArrayList on nopeempi random access
- LinkedList on nopeempi insert ja delete

### What is the difference between equals() and == in Java?

The equals() method is used to compare the content or value of objects for equality, while the == operator is used to compare object references for equality. In other words, equals() compares the actual contents of objects, whereas == compares whether the two objects point to the same memory location.

- EQUALS() kattoo onks samanlainen
- == onks samassa paikassa muistii

### What is the purpose of the final keyword in Java?

The final keyword in Java is used to make variables, methods, and classes immutable or unchangeable. When applied to variables, it makes them constants that cannot be reassigned. When applied to methods, it prevents method overriding. When applied to classes, it prevents inheritance.

- Sita ei voi vaihtaa

### What is serialization in Java, and why is it used?

Serialization in Java is the process of converting an object into a byte stream, which can be persisted to a file, sent over a network, or stored in a database. It's used for data persistence, communication between distributed systems, and object cloning.

- Muuttaa objectin biteiks minka voi sitte laittaa filee, lahettaa tai tallettaa databaseen

### Explain the concept of exception handling in Java.

Exception handling in Java is the process of managing and responding to runtime errors or exceptional conditions that occur during program execution. It involves using try, catch, finally, and throw keywords to handle exceptions gracefully and maintain program stability.

- Try, Catch, Finally

### What is multithreading in Java, and how is it achieved?

Multithreading in Java is the concurrent execution of multiple threads within a single Java program. It allows for parallelism and improved performance by dividing tasks into smaller, independent units of execution. Multithreading in Java can be achieved by extending the Thread class or implementing the Runnable interface.

- tekee montaa asiaa samaa aikaa, jaetaan juttu pienempiin osmiin

### What is the purpose of the synchronized keyword in Java?

The synchronized keyword in Java is used to control access to critical sections of code by allowing only one thread to execute them at a time. It prevents data corruption and race conditions in multithreaded environments by enforcing mutual exclusion.

- moni ei voi suorittaa sita samaa aikaa

### What are annotations in Java, and how are they used?

Annotations in Java provide metadata about a program that can be processed by tools and frameworks at compile time or runtime. They are used for documentation, code generation, and runtime behavior modification. Examples include @Override, @Deprecated, and @SuppressWarnings.

- esim Spring osaa kattoo ne ja tietaa mita teha

### What is JDBC, and how is it used in Java?

JDBC (Java Database Connectivity) is a Java API for connecting and executing SQL queries against a database. It provides a standard interface for accessing relational databases from Java applications, allowing developers to interact with databases programmatically.

- Sil tehaan SQL hakuja

### What is the difference between String, StringBuilder, and StringBuffer in Java?

String is immutable, meaning its value cannot be changed after creation. StringBuilder and StringBuffer are mutable and can be used to manipulate strings efficiently. StringBuilder is not thread-safe but offers better performance, while StringBuffer is thread-safe but slower due to synchronization.

- STRING arvoo ei voi vaihtaa ku se on tehty
- STRINBUILDER ja STRINGBUFFERII arvoo voi vaihtaa

### Explain the concept of garbage collection in Java.

Garbage collection in Java is the automatic process of reclaiming memory occupied by objects that are no longer in use. It helps prevent memory leaks and ensures efficient memory management by identifying and removing unreachable objects at runtime.

- Vapautaa muistii sielt missa ei oo enaa toimintaa

### How do you handle concurrency issues in Java applications?

Concurrency issues in Java applications can be handled using techniques such as synchronization, thread-safe data structures, locking mechanisms, atomic operations, and thread communication mechanisms like wait and notify. Additionally, using higher-level concurrency utilities provided by the java.util.concurrent package can simplify concurrency management.
