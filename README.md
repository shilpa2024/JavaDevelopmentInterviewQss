# JavaDevelopmentInterviewQss

*********************************************************************************************************

JDBC/DBMS/MYSQL

*********************************************************************************************************

1. **What are Joins?**
   - Joins in SQL are used to combine rows from two or more tables based on a related column between them. They allow you to retrieve data from multiple tables simultaneously by specifying how the tables should be related to each other.

2. **What is Normalization?**
   - Normalization is the process of organizing the attributes and tables of a relational database to minimize redundancy and dependency. It involves breaking down large tables into smaller ones and defining relationships between them to eliminate data duplication and improve data integrity.

3. **SQL syntax for ALTER and SELECT:**
   - Syntax for ALTER:
     ```sql
     ALTER TABLE table_name ADD column_name datatype;
     ```
   - Syntax for SELECT:
     ```sql
     SELECT column1, column2, ...
     FROM table_name;
     ```

4. **Advantages of ResultSet Interface:**
   - The ResultSet interface in JDBC allows for easy traversal and manipulation of data retrieved from a database.
   - It provides methods to access data by column index or name.
   - Supports both forward and backward cursor movements.
   - Efficiently handles large datasets.

5. **execute, executeUpdate, executeQuery:**
   - execute: Executes any SQL statement and returns a boolean indicating the type of the first result.
   - executeUpdate: Executes SQL statements that modify the database (e.g., INSERT, UPDATE, DELETE) and returns the number of affected rows.
   - executeQuery: Executes SQL queries that retrieve data from the database and returns a ResultSet object containing the results.

6. **What is JDBC?**
   - JDBC (Java Database Connectivity) is an API that allows Java applications to interact with databases. It provides methods for querying and updating data in a database.

7. **Steps to perform JDBC:**
   - Load the JDBC driver.
   - Establish a connection to the database.
   - Create a statement object.
   - Execute SQL queries.
   - Process the results.
   - Close the connection.

8. **What are joins?**
   - Joins in SQL are used to combine rows from two or more tables based on a related column between them. They help retrieve data from multiple tables simultaneously.

9
**SQL Commands:** SQL commands are used to interact with databases, including DDL, DML, DCL, and TCL commands for defining, manipulating, controlling, and managing data.

10**File System vs DBMS:** File systems organize data in files and folders without advanced management features, while DBMS provides structured data management with features like data integrity, security, and SQL-based querying.


*********************************************************************************************************
*********************************************************************************************************


11. **Different normal forms in MySQL:**
   - MySQL supports normalization up to BCNF, including 1NF, 2NF, 3NF, and BCNF, aiming to eliminate redundancy and enhance database efficiency. (1 mark)

12. **SQL Commands:**
   - SQL commands encompass DDL, DML, DCL, and TCL commands, facilitating database structure definition, data manipulation, access control, and transaction management. (1 mark)

13. **ACID Properties:**
   - ACID properties (Atomicity, Consistency, Isolation, Durability) ensure transaction reliability, maintaining data integrity despite failures or concurrent access. (1 mark)

14. **Purpose of ALTER command:**
   - ALTER command modifies existing database objects' structure, facilitating operations such as adding, modifying, or dropping columns, constraints, or indexes. (1 mark)

15. **Transaction Management in JDBC:**
   - JDBC supports transaction management through methods like setAutoCommit(), commit(), and rollback(), ensuring atomicity, consistency, isolation, and durability. (1 mark)

16. **Difference between Statement and PreparedStatement:**
   - Statement executes static SQL queries, while PreparedStatement handles parameterized queries with improved security and performance, mitigating SQL injection risks. (1 mark)

17. **Disadvantages of JDBC:**
   - JDBC drawbacks include manual resource management, verbosity, susceptibility to SQL injection, and reliance on platform-specific drivers. (1 mark)

18. **Foreign key:**
   - Foreign key establishes relationships between tables, enforcing referential integrity and maintaining data consistency by referencing primary or unique keys in other tables. (1 mark)

19. **SQL Commands:**
   - SQL commands encompass DDL, DML, DCL, and TCL commands, facilitating database structure definition, data manipulation, access control, and transaction management. (1 mark)

20. **Difference between Truncate, Drop, and Delete:**
    - TRUNCATE swiftly removes all table records, non-logged, and irreversible; DROP eliminates tables with their structure and data; DELETE removes specific records, logged, and rollback capable. (2 marks)


21. **Difference between inner join and Outer join:**
   - Inner join returns rows when there is a match in both tables, while outer join returns all rows from both tables, with unmatched rows filled with NULL values. (2 marks)

22. **What is Normalization?**
   - Normalization is the process of organizing database tables to reduce redundancy and dependency, enhancing data integrity. (1 mark)

23. **Advantages of DBMS:**
   - DBMS offers centralized data management, data integrity, security, concurrent access control, efficient data retrieval, and manipulation through SQL queries. (1 mark)

24. **What are ACID Properties?**
   - ACID properties (Atomicity, Consistency, Isolation, Durability) ensure transaction reliability, maintaining data integrity despite failures or concurrent access. (1 mark)

25. **Real-world examples of DBMS:**
   - Examples include Oracle, MySQL, SQL Server, MongoDB, and PostgreSQL, used in various sectors like banking, healthcare, e-commerce, and education. (1 mark)

26. **Disadvantages of File System:**
   - File systems lack data integrity, security, and concurrent access control, making them inefficient for managing large datasets and prone to data loss. (1 mark)

27. **Syntax to create a table:**
   - Syntax: CREATE TABLE table_name (column1 datatype1, column2 datatype2, ...); (1 mark)

28. **What is the use of JDBC?**
   - JDBC enables Java applications to interact with databases, providing methods for querying and updating data. (1 mark)

29. **Explain about DDL Commands:**
   - DDL (Data Definition Language) commands are used to define database structures, including CREATE, ALTER, DROP, TRUNCATE, and RENAME. (1 mark)

30. **What is StoredProcedure?**
    - A StoredProcedure is a set of SQL statements stored in the database and executed as a single unit, offering better performance and security. (1 mark)

31. **Explain the steps to perform JDBC:**
    - Steps include loading JDBC driver, establishing connection, creating statement, executing queries, processing results, and closing the connection. (1 mark)

32. **What is a subQuery?**
    - A subQuery is a query nested within another query, used to retrieve data based on the result of an outer query. (1 mark)

33. **SQL Commands:**
    - SQL commands encompass DDL, DML, DCL, and TCL commands, facilitating database structure definition, data manipulation, access control, and transaction management. (1 mark)

34. **Name some aggregate functions?**
   - Some aggregate functions include:
     - SUM(): Calculates the sum of values in a column.
     - AVG(): Calculates the average of values in a column.
     - COUNT(): Counts the number of rows.
     - MAX(): Finds the maximum value in a column.
     - MIN(): Finds the minimum value in a column.

35. **What is RDBMS?**
   - RDBMS stands for Relational Database Management System. It is a type of DBMS that stores data in tables and establishes relationships between them based on keys. Examples include MySQL, PostgreSQL, Oracle.

36. **What is DBMS?**
   - DBMS stands for Database Management System. It is a software system that allows users to interact with databases. It facilitates data storage, retrieval, manipulation, and security.

37. **Query to insert values in a table?**
   - Syntax: 
     ```sql
     INSERT INTO table_name (column1, column2, ...) VALUES (value1, value2, ...);
     ```

38. **Difference between 1NF, 2NF, 3NF?**
   - 1NF (First Normal Form): Ensures that each column contains atomic values, and there are no repeating groups.
   - 2NF (Second Normal Form): Eliminates partial dependencies by ensuring that all non-key attributes are fully functionally dependent on the primary key.
   - 3NF (Third Normal Form): Eliminates transitive dependencies by ensuring that all non-key attributes are functionally dependent only on the primary key.

39. **Difference between Primary key and Foreign key?**
   - Primary Key: Uniquely identifies each record in a table. There can be only one primary key in a table, and it cannot have NULL values.
   - Foreign Key: Establishes a relationship between two tables. It is a column or set of columns in one table that refers to the primary key in another table. It ensures referential integrity.

40. **What is Connection Interface?**
   - Connection Interface in JDBC represents a connection with a specific database. It allows Java programs to connect to a database, send SQL queries, and retrieve results.

41. **What are ACID Properties?**
   - ACID properties (Atomicity, Consistency, Isolation, Durability) ensure transaction reliability and data integrity in a database system.

42. **Name some SQL Commands?**
   - Some SQL commands include: SELECT, INSERT, UPDATE, DELETE, CREATE, ALTER, DROP, TRUNCATE, COMMIT, ROLLBACK, GRANT, REVOKE.

43. **Difference between left join and right join?**
    - Left Join: Returns all records from the left table (table1), and the matched records from the right table (table2). Unmatched records in the right table will have NULL values.
    - Right Join: Returns all records from the right table (table2), and the matched records from the left table (table1). Unmatched records in the left table will have NULL values.


44. **Explain about ER Model:**
   - The ER (Entity-Relationship) model is a conceptual data model that depicts the relationships between entities in a database. Entities are represented as rectangles, attributes as ovals, and relationships between entities as diamonds. ER diagrams provide a visual representation of the database structure and help in designing databases.

45. **What are SQL Commands?**
   - SQL (Structured Query Language) commands are used to interact with databases. They include:
     - DDL (Data Definition Language) commands: CREATE, ALTER, DROP, TRUNCATE.
     - DML (Data Manipulation Language) commands: SELECT, INSERT, UPDATE, DELETE.
     - DCL (Data Control Language) commands: GRANT, REVOKE.
     - TCL (Transaction Control Language) commands: COMMIT, ROLLBACK, SAVEPOINT.

46. **Query to insert values in a table:**
   - Syntax:
     ```sql
     INSERT INTO table_name (column1, column2, ...) VALUES (value1, value2, ...);
     ```
   - Example:
     ```sql
     INSERT INTO employees (emp_id, emp_name, emp_salary) VALUES (101, 'John Doe', 50000);
     ```

47. **Disadvantages of JDBC:**
   - JDBC (Java Database Connectivity) drawbacks include manual resource management, verbosity, susceptibility to SQL injection, platform dependency, and boilerplate code for connection handling and query execution. It requires developers to handle connections, statements, and result sets manually, increasing development effort and complexity.

48. **File System vs DBMS:**
   - File System organizes data in files and folders without advanced management features, while DBMS provides structured data management with features like data integrity, security, and SQL-based querying. DBMS offers better data organization, retrieval, and management capabilities compared to a file system.

49. **What is a subQuery?**
   - A subQuery is a query nested within another query, used to retrieve data based on the result of an outer query. Subqueries can be used in WHERE, HAVING, and FROM clauses to filter or manipulate data.

50. **Name some aggregate functions:**
   - Some aggregate functions include:
     - SUM(): Calculates the sum of values in a column.
     - AVG(): Calculates the average of values in a column.
     - COUNT(): Counts the number of rows.
     - MAX(): Finds the maximum value in a column.
     - MIN(): Finds the minimum value in a column.


*********************************************************************************************************
*********************************************************************************************************

*********************************************************************************************************
Core Java:
*********************************************************************************************************



1. **What is Java?**
   - Java is a versatile, object-oriented programming language known for its platform independence and wide usage in developing a variety of software applications.

2. **Features of Java:**
   - Object-oriented
   - Platform independence
   - Simple
   - Secure
   - Robust
   - Multithreaded
   - Architecture-neutral
   - Portable
   - High performance
   - Distributed

3. **Difference between C & Java:**
   - C is a procedural programming language, while Java is an object-oriented programming language.
   - C requires manual memory management, while Java has automatic memory management through garbage collection.
   - Java is platform-independent due to its bytecode compilation, while C code needs to be compiled separately for each platform.

4. **What is meant by OOPs?**
   - OOPs (Object-Oriented Programming) is a programming paradigm based on the concept of objects, which can contain data in the form of fields and code in the form of procedures. It focuses on modularity, reusability, and extensibility of code.

5. **Difference between Class & Object with example:**
   - Class is a blueprint for creating objects, defining attributes (fields) and behaviors (methods) that objects of that class will have.
   - Object is an instance of a class, representing a specific entity in memory.
   - Example: 
     ```java
     class Car {
         String color;
         void start() {
             System.out.println("Car started.");
         }
     }
     // Creating an object of Car class
     Car myCar = new Car();
     ```

6. **Difference between JVM, JRE, JDK:**
   - JVM (Java Virtual Machine) is an abstract machine that provides a runtime environment for executing Java bytecode.
   - JRE (Java Runtime Environment) contains JVM, class libraries, and other supporting files required to run Java applications.
   - JDK (Java Development Kit) includes JRE along with development tools like compilers and debuggers for Java development.

7. **Explain about internal architecture of JVM:**
   - JVM consists of multiple components such as class loader, memory area, execution engine, native interface, and runtime data areas like method area, heap, stack, and PC register.

8. **Commands for compilation & running:**
   - Compilation: `javac YourFileName.java`
   - Running: `java YourFileName`

9. **If a class is declared as public, can a class name & file name be different? (Yes/no)**
   - Yes, the class name and file name can be different, but it's recommended to keep them the same for clarity.

10. **If a class is declared as default, can a class name & file name be different? (Yes/no)**
    - Yes, they can be different.

11. **Difference between static & non-static method:**
    - Static method belongs to the class and can be invoked without creating an instance of the class, whereas non-static method belongs to an instance of the class and requires an object to invoke it.
    - Static methods can access only static variables and methods, while non-static methods can access both static and non-static variables and methods.


12. **What is a constructor?**
   - A constructor is a special type of method in Java that is automatically called when an object of a class is created. It is used to initialize the object's state.

13. **Types of constructors:**
   - Default constructor: Automatically created by the compiler if no constructor is defined.
   - Parameterized constructor: Constructor with parameters to initialize object properties during object creation.
   - Copy constructor: Constructor used to create a new object as a copy of an existing object.

14. **Difference between constructor & method:**
   - Constructor is used to initialize objects of a class, whereas method is used to perform some actions or operations.
   - Constructor has the same name as the class, while method can have any name.
   - Constructor does not have a return type, while method can have a return type or void.

15. **Difference between static, instance & local variables:**
   - Static variables: Belong to the class itself and are shared among all instances of the class.
   - Instance variables: Belong to each instance of the class and have separate copies for each object.
   - Local variables: Declared inside methods or blocks and exist only within the scope of that method or block.

16. **Explain about implicit typecasting:**
   - Implicit typecasting is the automatic conversion of data from one data type to another by the compiler when the destination data type can hold all possible values of the source data type without any data loss.

17. **Explain about explicit typecasting:**
   - Explicit typecasting is the manual conversion of data from one data type to another by the programmer using casting operators. It is done when there is a possibility of data loss or when the compiler cannot perform the conversion automatically.

18. **Why main method should be declared as static?**
   - The main method is declared as static so that it can be called by the JVM without creating an instance of the class. This is because the main method is the entry point of a Java program, and the JVM needs to execute it before creating any objects of the class.

19. **Why main method should be declared as public?**
   - The main method needs to be declared as public so that it can be accessed by the JVM from outside the class.

20. **Why main method should be declared as void?**
   - The main method should be declared as void because it does not return any value.

21. **Difference between for loop and for each loop:**
    - The for loop is a traditional loop used for iterating over a range of values or executing a block of code a fixed number of times.
    - The for each loop (enhanced for loop) is used for iterating over elements of arrays or collections without using an index variable. It provides a simpler syntax and is preferred when you want to iterate through all elements of an array or collection.

22. **Difference between while and do-while:**
    - The while loop executes the code block only if the condition is true. It may not execute at all if the condition is false from the beginning.
    - The do-while loop executes the code block first and then checks the condition. It ensures that the code block is executed at least once, even if the condition is false initially.


23. **Explain about switch case statement:**
   - The switch case statement is a control flow statement used to select one of many code blocks to be executed based on the value of an expression. It provides an alternative to multiple if-else-if statements.
   - Syntax:
     ```java
     switch (expression) {
         case value1:
             // code block
             break;
         case value2:
             // code block
             break;
         // other cases
         default:
             // default code block
     }
     ```

24. **Difference between break and continue:**
   - **break:** Terminates the current loop or switch case statement and transfers control to the statement following the terminated loop or switch.
   - **continue:** Skips the remaining code in the loop and proceeds to the next iteration of the loop.

25. **Difference between void and return:**
   - **void:** Denotes that a method does not return any value.
   - **return:** Used to exit from a method and return a value to the calling method.

26. **What is the this keyword & uses of this keyword:**
   - The `this` keyword in Java refers to the current instance of the class. It can be used to access instance variables and methods of the current object, differentiate between instance variables and method parameters with the same name, and invoke one constructor from another in the same class.

27. **What is an array:**
   - An array is a data structure that stores a fixed-size sequential collection of elements of the same data type. Each element in the array is accessed by its index.

28. **Advantages & disadvantages of an array:**
   - Advantages:
     - Provides random access to elements using indexes.
     - Allows storing multiple values of the same data type in a single variable.
   - Disadvantages:
     - Has a fixed size, making it inflexible for dynamic storage needs.
     - Requires contiguous memory allocation, leading to memory wastage for sparse arrays.

29. **Explain any 2 of the array methods:**
   - `length`: Returns the length of the array.
   - `clone()`: Creates a shallow copy of the array.

30. **What is meant by String Constant Pool (SCP)?**
   - The String Constant Pool is a special area in the Java heap memory where String literals are stored. It allows the JVM to optimize memory usage by reusing String objects with the same value, thus reducing memory consumption.

31. **Difference between == and equals():**
   - `==` compares object references, checking if two references point to the same object in memory.
   - `equals()` is a method used to compare the contents of two objects, typically overridden in classes to define equality based on object attributes.

32. **Explain any 7 String Class methods:**
    - `length()`, `charAt()`, `substring()`, `indexOf()`, `toUpperCase()`, `toLowerCase()`, `equals()`.

33. **Difference between String, StringBuffer, StringBuilder:**
    - **String:** Immutable, thread-safe, and slower. Once created, cannot be modified.
    - **StringBuffer:** Mutable, thread-safe, and slower. Supports modification of contents after creation.
    - **StringBuilder:** Mutable, not thread-safe, and faster. Similar to StringBuffer but not synchronized.


34. **How many ways are there to import a package from another package? What are they?**
   - There are two ways to import a package in Java:
     1. Using the `import` statement followed by the fully qualified name of the package.
     2. Using the wildcard (*) character to import all classes/interfaces of the package.

35. **Difference between this and super:**
   - `this` refers to the current instance of a class.
   - `super` refers to the superclass of the current instance.

36. **Difference between POP and OOP:**
   - **POP (Procedural Oriented Programming):** Focuses on functions or procedures that operate on data.
   - **OOP (Object-Oriented Programming):** Focuses on objects that contain data and methods to manipulate the data.

37. **Explain Encapsulation with a real-time example:**
   - Encapsulation is the mechanism of bundling data (attributes) and methods that operate on the data into a single unit (class). It restricts direct access to some of the object's components and prevents the accidental modification of data.
   - Example: A `Car` class encapsulating attributes like `color`, `speed`, and methods like `accelerate()`, `brake()`, ensures that the speed can only be modified using these methods, maintaining data integrity.

38. **Explain Inheritance and types of inheritance with a real-time example:**
   - Inheritance is a mechanism in which a new class inherits properties and behaviors (methods) from an existing class, promoting code reusability.
   - Types of inheritance: Single, Multilevel, Hierarchical, Multiple (not supported in Java), Hybrid.
   - Example: A `Vehicle` class may have attributes and methods common to all vehicles. A `Car` class can inherit from the `Vehicle` class, gaining all its attributes and methods.

39. **Advantages of Inheritance:**
   - Code reusability
   - Method overriding for polymorphism
   - Organizes classes in a hierarchical manner
   - Allows the addition of new features to existing classes

40. **Can we inherit static methods?**
   - Yes, static methods can be inherited in Java. However, they cannot be overridden. They are resolved at compile-time based on the reference type.

41. **Can we inherit private methods?**
   - No, private methods cannot be inherited in Java because they are not accessible outside the class where they are defined.

42. **Do constructors participate in Inheritance?**
   - Constructors are not inherited, but the constructor of the superclass is called implicitly or explicitly by the constructor of the subclass using `super()`.

43. **Explain Polymorphism:**
    - Polymorphism allows objects of different types to be treated as objects of a common superclass through method overriding. It enables a single interface to represent different forms or behaviors.

44. **Difference between method overloading and method overriding along with real-time examples:**
    - **Method overloading:** Same method name with different parameters in the same class.
      ```java
      class Calculator {
          int add(int a, int b) {
              return a + b;
          }
          double add(double a, double b) {
              return a + b;
          }
      }
      ```
    - **Method overriding:** Same method name and parameters in the superclass and subclass, with the subclass providing its implementation.
      ```java
      class Animal {
          void sound() {
              System.out.println("Animal makes a sound");
          }
      }
      class Dog extends Animal {
          void sound() {
              System.out.println("Dog barks");
          }
      }
      ```


45. **Can we overload static methods?**
   - Yes, static methods can be overloaded in Java. Method overloading is a feature that allows a class to have multiple methods with the same name but with different parameters.

46. **Can we override static methods?**
   - No, static methods cannot be overridden in Java. When a subclass defines a static method with the same signature as a static method in the superclass, it is called method hiding, not method overriding.

47. **Can we overload constructors?**
   - Yes, constructors can be overloaded in Java. Constructor overloading allows a class to have multiple constructors with different parameter lists.

48. **Can we override Constructors?**
   - No, constructors cannot be overridden in Java. Subclasses inherit constructors from their superclass, but they cannot override them.

49. **What is meant by method hiding?**
   - Method hiding occurs when a subclass defines a static method with the same signature as a static method in the superclass. In this case, the static method in the subclass hides the static method in the superclass, and the method to be called is determined by the reference type.

50. **What is Abstraction?**
   - Abstraction is a fundamental principle of object-oriented programming that focuses on hiding the implementation details of a class and only showing the essential features of the object. It allows developers to focus on what an object does rather than how it does it.

51. **What is Interface?**
   - An interface in Java is a reference type that defines a set of abstract methods and constants. It represents a contract that concrete classes must implement, specifying the behavior they must provide.

52. **Difference between class and Interface:**
   - A class can contain both concrete methods and abstract methods, while an interface can only contain abstract methods.
   - A class can have constructors, instance variables, and instance methods, while an interface cannot have constructors or instance variables, only constants.
   - A class can extend only one class, but it can implement multiple interfaces.

53. **Difference between abstract class and Interface:**
   - An abstract class can have both abstract and concrete methods, while an interface can only have abstract methods.
   - An abstract class can have instance variables, constructors, and static methods, while an interface cannot.
   - A class can extend only one abstract class, but it can implement multiple interfaces.

54. **How can we achieve multiple inheritance in Java?**
    - Multiple inheritance is not directly supported in Java due to the "diamond problem" and ambiguity issues. However, it can be achieved through interfaces. A class can implement multiple interfaces, effectively inheriting behavior from multiple sources.

55. **Explain about final keyword, in how many ways we can use it?**
    - The `final` keyword in Java is used to restrict the user. It has several uses:
      - Final variable: A variable that cannot be reassigned once initialized.
      - Final method: A method that cannot be overridden by subclasses.
      - Final class: A class that cannot be subclassed.
      - Final parameter: A parameter that cannot be modified within the method.
      - Finalizer method: A method used for cleanup operations before an object is garbage collected (deprecated in favor of `java.lang.AutoCloseable` and try-with-resources).

56. **Difference between final, finally, finalized():**
   - `final`: `final` is a keyword in Java used to declare constants, methods that cannot be overridden, classes that cannot be subclassed, or variables that cannot be reassigned.
   - `finally`: `finally` is a block associated with a try-catch block in Java. It is used to execute a block of code regardless of whether an exception is thrown or not.
   - `finalized()`: `finalized()` is a method in the `Object` class in Java. It is called by the garbage collector before reclaiming the memory occupied by an object that is eligible for garbage collection.

57. **Difference between throw and throws:**
   - `throw`: `throw` is a keyword in Java used to explicitly throw an exception within a method.
   - `throws`: `throws` is a keyword used in method signatures to declare that the method might throw certain types of exceptions.

58. **What is Garbage collection?**
   - Garbage collection is the process of automatically reclaiming the memory occupied by objects that are no longer reachable or in use by the program. It is an essential feature of Java that helps manage memory efficiently and avoid memory leaks.

59. **What is Exception handling?**
   - Exception handling is a mechanism in Java used to handle runtime errors or exceptional conditions that occur during the execution of a program. It involves catching and handling exceptions using try-catch blocks or propagating them using the throws keyword.

60. **Types of Exceptions:**
   - Checked exceptions: Checked exceptions are checked at compile-time and must be either caught using try-catch blocks or declared in the method signature using the throws keyword.
   - Unchecked exceptions: Unchecked exceptions are not checked at compile-time and typically represent programming errors or unexpected conditions. They are subclasses of `RuntimeException` or `Error`.

61. **Difference between checked and unchecked exceptions:**
   - Checked exceptions must be either caught or declared, while unchecked exceptions do not have this requirement.
   - Checked exceptions represent recoverable conditions, while unchecked exceptions usually represent programming errors or unexpected conditions.

62. **What are custom exceptions?**
   - Custom exceptions, also known as user-defined exceptions, are exceptions created by the programmer to represent specific error conditions in their applications. They are subclasses of the `Exception` class or its subclasses.

63. **What are Wrapper classes?**
   - Wrapper classes in Java are classes that encapsulate primitive data types (such as int, float, boolean) into objects. They provide methods to convert primitive data types into objects and vice versa.

64. **What is AutoBoxing?**
   - AutoBoxing is the automatic conversion of primitive data types into their corresponding wrapper objects when required. For example, converting an int to an Integer object.

65. **What is AutoUnboxing?**
    - AutoUnboxing is the automatic conversion of wrapper objects into their corresponding primitive data types when required. For example, converting an Integer object to an int.

66. **Explain the hierarchy of Collection frameworks:**
    - The Collection Framework in Java provides a unified architecture for representing and manipulating collections of objects. The hierarchy includes:
      - Interfaces: `Collection`, `List`, `Set`, `Queue`, `Deque`, `Map`.
      - Classes: `ArrayList`, `LinkedList`, `HashSet`, `TreeSet`, `HashMap`, `TreeMap`, etc.
      - Utility classes: `Collections`, `Arrays`.
      - Legacy classes: `Vector`, `Stack`, `Hashtable`.
Certainly! Here are the explanations:

67. **Difference between Array and ArrayList:**
   - **Array:** Arrays are fixed in size and can hold elements of the same data type. They provide direct access to elements using index.
   - **ArrayList:** ArrayList is a part of the Collection framework and is dynamic in size. It can hold elements of any data type and provides methods for dynamic resizing, insertion, deletion, etc.

68. **Difference between ArrayList, Vector, LinkedList of List Interface:**
   - **ArrayList:** It is not synchronized by default, grows dynamically, and is fast for retrieval but slower for insertion/deletion.
   - **Vector:** Similar to ArrayList but is synchronized by default, which makes it thread-safe but slower.
   - **LinkedList:** Implements a doubly-linked list, providing fast insertion and deletion but slower retrieval compared to ArrayList.

69. **What is polymorphism?**
   - Polymorphism is a core concept in object-oriented programming where an object can take on multiple forms. It allows objects of different types to be treated as objects of a common superclass through method overriding and method overloading.

70. **What is method Overriding?**
   - Method overriding occurs when a subclass provides a specific implementation for a method that is already defined in its superclass. It allows a subclass to provide its own implementation of inherited methods.

71. **Difference between Class and Interface?**
   - A class can contain both methods and fields, while an interface contains only method signatures and constants.
   - A class can provide a complete implementation, while an interface only defines the structure that a class must follow.

72. **What are memory areas?**
   - In Java, memory is divided into several areas, including:
     - Heap: Memory allocated for objects at runtime.
     - Stack: Memory allocated for method calls and local variables.
     - Method Area: Memory for class structures and method code.
     - PC Register: Program Counter Register.
     - Native Method Stack: Memory for native methods.
     - Runtime Constant Pool: Memory for constant values.

73. **Java 8 Features:**
   - Lambda Expressions
   - Stream API
   - Default and Static Methods in Interfaces
   - Functional Interfaces
   - Optional Class
   - Date-Time API (java.time package)
   - CompletableFuture for asynchronous programming
   - Method References and Constructor References

74. **What is MultiThreading?**
   - Multithreading is a programming concept where a single process contains multiple threads of execution, allowing concurrent execution of tasks. It enables applications to perform multiple tasks simultaneously, improving performance and responsiveness.

75. **What is Garbage Collector?**
   - Garbage Collector is a part of the Java Virtual Machine responsible for reclaiming memory occupied by objects that are no longer in use by the program. It automatically frees up memory by deallocating objects that are no longer reachable.

76. **Command for compilation and running:**
    - To compile: `javac <filename>.java`
    - To run: `java <filename>`
Let's address your questions:

77. **Internal Architecture of JVM:**
   - JVM (Java Virtual Machine) is divided into three main subsystems: Class Loader, Runtime Data Area, and Execution Engine. Class Loader loads class files, Runtime Data Area stores data and instructions, and Execution Engine executes the bytecode.

78. **this and super keyword:**
   - `this`: Refers to the current instance of a class. It is used to access instance variables and methods of the current object.
   - `super`: Refers to the superclass of the current instance. It is used to access superclass members and to call superclass constructors.

79. **Where did we use Interfaces?**
   - Interfaces are used to define a contract for classes to implement. They are commonly used to achieve abstraction and provide a common behavior that multiple classes can adhere to.

80. **What is Encapsulation?**
   - Encapsulation is a fundamental principle of object-oriented programming that involves bundling data and methods that operate on the data into a single unit (class). It hides the internal state of an object and only exposes the necessary functionality through methods.

81. **What is Exception Handling?**
   - Exception handling is a mechanism in Java used to handle runtime errors or exceptional conditions that occur during program execution. It involves catching and handling exceptions using try-catch blocks or propagating them using the throws keyword.

. 82**What is Abstraction?**
   - Abstraction is a fundamental concept in object-oriented programming that involves hiding the implementation details of a class and only showing the essential features of an object. It allows developers to focus on what an object does rather than how it does it.

83. **Difference between String buffer and String builder:**
   - Both `StringBuffer` and `StringBuilder` are classes used to manipulate strings. The main difference is that `StringBuffer` is synchronized (thread-safe) while `StringBuilder` is not.

84. **Difference between ArrayList and Array:**
   - An array is a fixed-size data structure that stores elements of the same type in contiguous memory locations, while an ArrayList is a dynamic-size data structure that can grow or shrink dynamically and can store elements of any type.

85. **Difference between JVM, JRE, JDK:**
   - **JVM (Java Virtual Machine):** Executes Java bytecode. It provides a runtime environment for Java applications.
   - **JRE (Java Runtime Environment):** It includes JVM and libraries required to run Java applications but does not include development tools.
   - **JDK (Java Development Kit):** It includes JRE along with development tools (compilers, debuggers, etc.) needed to develop Java applications.

86. **Explain about encapsulation:**
    - Encapsulation is the process of bundling data (attributes) and methods that operate on the data into a single unit (class). It restricts direct access to some of the object's components and prevents the accidental modification of data.


87. **What is Exception Handling?**
   - Exception handling is a mechanism in programming languages like Java used to handle runtime errors or exceptional conditions that occur during the execution of a program. It involves catching and handling exceptions using try-catch blocks or propagating them using the throws keyword.

88. **What is Optional Class?**
   - `Optional` is a class introduced in Java 8 that is used to represent an optional value that may or may not be present. It helps to avoid null pointer exceptions by providing a more expressive and type-safe way to handle potentially null values.

89. **What is InterThread Communication?**
   - InterThread Communication refers to the mechanism in Java where threads communicate with each other by signaling and waiting for notifications. This is typically achieved using methods like `wait()`, `notify()`, and `notifyAll()` provided by the `Object` class.

90. **What are Java 8 features?**
   - Java 8 introduced several features including lambda expressions, the Stream API, default and static methods in interfaces, functional interfaces, the Optional class, the Date-Time API (java.time package), and more.

91. **What is method hiding?**
   - Method hiding occurs when a subclass defines a static method with the same signature as a static method in its superclass. In this case, the static method in the subclass hides the static method in the superclass.

92. **Method overloading and constructor overloading?**
   - Method overloading: Method overloading is a feature in Java that allows a class to have multiple methods with the same name but with different parameters.
   - Constructor overloading: Constructor overloading is a feature in Java that allows a class to have multiple constructors with different parameter lists.

93. **Name some real-time examples where multiThreading is used?**
   - MultiThreading is used in various real-world scenarios such as web servers handling multiple client requests concurrently, GUI applications where multiple tasks need to be performed simultaneously, simulation software, video game development, and more.

94. **What are features of Java?**
   - Some features of Java include platform independence, object-oriented programming, robustness, security, portability, multi-threading, and dynamic memory allocation (garbage collection).

95. **Difference between Class and Interface?**
   - A class is a blueprint for creating objects and can contain both data members and methods. An interface is a contract that defines a set of abstract methods and constants that implementing classes must adhere to.

96. **What is Inheritance?**
    - Inheritance is a mechanism in object-oriented programming where a class (subclass) inherits properties and behaviors (methods) from another class (superclass). It promotes code reusability and establishes a parent-child relationship between classes.

97. **Explain different types of loops?**
    - Java supports several types of loops including `for`, `while`, `do-while`, and the enhanced `for` loop (also known as the for-each loop). These loops are used to iterate over collections of data or to repeatedly execute a block of code until a condition is met.


98. **What is main method in Java?**
   - The main method is the entry point of a Java program. It is the method where the execution of the program begins. It has a specific signature: `public static void main(String[] args)`.

99. **What is Switch Case Statement?**
   - The switch case statement is a control flow statement in Java used to select one of many code blocks to be executed based on the value of an expression. It provides an efficient way to write multiple if-else statements for multiple conditions.

100. **Difference between Abstraction and Interface?**
   - Abstraction is a concept in object-oriented programming that refers to the process of hiding the implementation details and showing only the essential features of an object. An interface is a Java construct that defines a contract for classes to implement, specifying a set of methods that must be implemented by any class that implements the interface.

101. **Why main method should be declared as static?**
   - The main method should be declared as static because it needs to be accessible to the JVM (Java Virtual Machine) without creating an instance of the class. The static modifier allows the main method to be called directly by the JVM without creating any objects.

102. **What is Inheritance?**
   - Inheritance is a mechanism in object-oriented programming where a class (subclass) inherits properties and behaviors (methods) from another class (superclass). It promotes code reusability and establishes a parent-child relationship between classes.

103. **What is method Overriding?**
   - Method overriding occurs when a subclass provides a specific implementation for a method that is already defined in its superclass. It allows a subclass to provide its own implementation of inherited methods.

104. **What is Object Class?**
   - The Object class is the root class of all Java classes. Every class in Java is a subclass of the Object class either directly or indirectly. It provides several methods like `equals()`, `hashCode()`, `toString()`, etc., which can be overridden by subclasses.

105. **How do you handle exceptions?**
   - Exceptions in Java are handled using try-catch blocks. Code that might throw an exception is placed within the try block, and the catch block catches and handles the exception if it occurs. Optionally, a finally block can be used to execute cleanup code.

106. **What is Multiple Inheritance?**
   - Multiple inheritance refers to the ability of a class to inherit properties and behaviors from more than one superclass. Java does not support multiple inheritance of classes, meaning a class cannot directly extend more than one class. However, it does support multiple inheritance of interfaces.

107. **What is deadlock in MultiThreading?**
    - Deadlock in multithreading occurs when two or more threads are blocked indefinitely, waiting for each other to release resources that they need to proceed. It typically happens when two or more threads acquire locks on resources in a way that leads to circular waiting.

108. **Explain the flow of Java Program?**
    - The flow of a Java program typically involves:
      - Compilation: Source code (.java files) is compiled into bytecode (.class files) using the javac compiler.
      - Loading: Bytecode is loaded by the JVM (Java Virtual Machine).
      - Verification: Bytecode is verified to ensure it follows Java language rules and security constraints.
      - Execution: Bytecode is executed by the JVM, starting with the main method.
Let's address your questions:

109. **How do you handle exceptions?**
   - Exceptions in Java are handled using try-catch blocks. Code that might throw an exception is placed within the try block, and the catch block catches and handles the exception if it occurs. Optionally, a finally block can be used to execute cleanup code.

110. **What is Multiple Inheritance?**
   - Multiple inheritance refers to the ability of a class to inherit properties and behaviors from more than one superclass. In Java, a class cannot directly inherit from more than one class (multiple inheritance of classes is not supported), but it can implement multiple interfaces (multiple inheritance of interfaces is supported).

111. **What is deadlock in MultiThreading?**
   - Deadlock in multithreading occurs when two or more threads are blocked indefinitely, waiting for each other to release resources that they need to proceed. It typically happens when two or more threads acquire locks on resources in a way that leads to circular waiting.

112. **Explain the flow of Java Program?**
   - The flow of a Java program typically involves:
     - Writing Java code in source files (.java).
     - Compiling source files into bytecode (.class) using the Java compiler (javac).
     - Loading bytecode into memory and executing it using the Java Virtual Machine (JVM).
     - During execution, the JVM manages memory, handles exceptions, and executes the program according to the code logic.

113. **What is Garbage Collector?**
   - The Garbage Collector (GC) is a part of the Java Virtual Machine (JVM) responsible for reclaiming memory occupied by objects that are no longer in use by the program. It automatically frees up memory by deallocating objects that are no longer reachable.

114. **What are features of Java?**
   - Some features of Java include platform independence, object-oriented programming, robustness, security, portability, multi-threading, and dynamic memory allocation (garbage collection).

115. **What is Class and Object?**
   - A class is a blueprint for creating objects. It defines the properties (attributes) and behaviors (methods) that objects of the class will have. An object is an instance of a class, created using the `new` keyword, and it represents a specific instance of the class.

116. **Difference between for and while?**
   - The `for` loop is used when the number of iterations is known beforehand, and it consists of three parts: initialization, condition, and increment/decrement.
   - The `while` loop is used when the number of iterations is not known beforehand, and it repeats a block of code as long as the condition is true.

117. **Explain about Abstraction?**
   - Abstraction is a fundamental concept in object-oriented programming that involves hiding the implementation details of a class and only showing the essential features of an object. It allows developers to focus on what an object does rather than how it does it.

118. **What is lambda Expression?**
    - Lambda expressions are a feature introduced in Java 8 that allows you to treat functionality as a method argument or create anonymous functions. They provide a concise way to represent one method interface using an expression. Lambda expressions are commonly used with functional interfaces and the Stream API for functional programming in Java.

**************************************************************************************************************************************************************************************************************************



