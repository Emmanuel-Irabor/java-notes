#### Java

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/4sao67jeqat7heumi2wc.png)

    

##### Table of Contents

- [What is Java?](#what-is-java)
- [How to install Java](#how-to-install-java)
- [To check if you have the java_home set](#to-check-if-you-have-the-java_home-set)
- [Check if Java is installed](#check-if-java-is-installed)
- [How to set Java path](#how-to-set-java-path)
- [Use jshell terminal i.e Java Shell](#use-jshell-terminal-ie-java-shell)
- [Write a Java program](#write-a-java-program)
- [How to compile Java program](#how-to-compile-java-program)
- [How to run Java program](#how-to-run-java-program)
- [Variables](#variables)
- [Reference data types](#reference-data-types)
- [Variable naming conventions](#variable-naming-conventions)
- [Reassigning variables](#reassigning-variables)
- [ Declare multiple variables](#declare-multiple-variables)
- [ Copying variables](#copying-variables)
- [Type casting](#type-casting)
- [Type promotion](#type-promotion)
- [ Type conversion](#type-conversion)
- [String concatenation](#string-concatenation)
- [String comparison](#string-comparison)
- [ String formatting](#string-formatting)
- [NumberFormat](#numberformat)
- [String methods](#string-methods)
- [String escape characters](#string-escape-characters)
- [Type of variables](#type-of-variables)
- [Constants](#constants)
- [Data types](#data-types)
- [Dates classes](#dates-classes)
- [public vs private](#public-vs-private)
- [static vs non-static](#static-vs-non-static)
- [Public vs Static](#public-vs-static)
- [Java.lang package](#java.lang-package)
- [Loops](#loops)
- [ Break and Continue](#break-and-continue)
- [ Loops and Arrays](#loops-and-arrays)
- [Loops and Strings](#loops-and-strings)
- [ Loops using Array streams](#loops-using-array-streams)
- [Decrements and Increments](#decrements-and-increments)
- [Conditional Statements](#conditional-statements)
- [Keywords](#keywords)
- [Arrays](#arrays)
- [Ways of creating an array](#ways-of-creating-an-array)
- [Arrays.toString()](#arraystostring)
- [Array Methods](#array-methods)
- [Arrays and indexes](#arrays-and-indexes)
- [Mixed Data Types](#mixed-data-types)
- [Multidimensional Arrays](#multidimensional-arrays)
- [ Classes and Objects](#classes-and-objects)
- [Objects](#objects)
- [Fields](#fields)
- [Methods](#methods)
- [Constructors](#constructors)
- [Class](#class)
- [ Math Class Operations](#math-class-operations)
- [Object](#object)
- [Getters and Setters](#getters-and-setters)
- [Inheritance](#inheritance)
- [Method](#method)
- [toString() Method](#tostring-method)
- [Method overloading](#method-overloading)
- [Wrapper Classes](#wrapper-classes)
- [Inheritance](#inheritance)
- [Polymorphism](#polymorphism)
- [Abstraction](#abstraction)
- [Encapsulation](#encapsulation)
- [Enums](#enums)
- [Loop through the enum values with the values() method](#loop-through-the-enum-values-with-the-values-method)
- [Get the Enum value](#get-the-enum-value)
- [Interfaces](#interfaces)
- [Exception](#exception)
- [Collections](#collections)
- [Generics](#generics)
- [Iterator](#iterator)
- [Enumeration](#enumeration)
- [Comparable](#comparable)
- [Comparator](#comparator)
- [Multithreading](#multithreading)
- [Thread class](#thread-class)
- [Runnable interface](#runnable-interface)
- [Thread states](#thread-states)
- [Serialization](#serialization)
- [ I/O](#io)
- [String Reader](#string-reader)
- [ String Writer](#string-writer)
- [ Pushback Reader](#pushback-reader)
- [Buffered Reader](#buffered-reader)
- [Buffered Writer](#buffered-writer)
- [Data Stream](#data-stream)
- [Error Handling](#error-handling)
- [Error Handling](#error-handling)
- [Exception](#exception)
- [Exception Handling](#exception-handling)
- [ Exception Propagation](#exception-propagation)
- [ Finally Block](#finally-block)
- [Throw](#throw)
- [Throws](#throws)
- [Try Catch](#try-catch)
- [Try Catch Finally](#try-catch-finally)
- [Try With Resources](#try-with-resources)
- [Unchecked Exceptions](#unchecked-exceptions)
- [User Defined Exceptions](#user-defined-exceptions)
- [Checked Exceptions](#checked-exceptions)
- [Calling external APIs](#calling-external-apis)
- [ Calling external APIs with parameters](#calling-external-apis-with-parameters)
- [Scanner Class in Java](#scanner-class-in-java)
- [ System Class in Java](#system-class-in-java)
- [Regex in Java](#regex-in-java)
- [Method reference](#method-reference)
- [Lambda expressions](#lambda-expressions)
- [Java 8 Stream API](#java-8-stream-api)
- [Java 8 Date Time API](#java-8-date-time-api)
- [Java 8 Optional Class](#java-8-optional-class)
- [Java 8 Default and Static Methods in Interfaces](#java-8-default-and-static-methods-in-interfaces)
- [Creating files in Java](#creating-files-in-java)
- [Reading files in Java](#reading-files-in-java)
- [Writing files in Java](#writing-files-in-java)
- [Java 8 Concurrency API](#java-8-concurrency-api)
- [Package](#package)
- [Exercise](#exercise)

---

#### What is Java? <a name="what-is-java"></a>

Java is a high-level, class-based, object-oriented programming language that is designed to have as few implementation dependencies as possible. It is a general-purpose programming language intended to let application developers write once, run anywhere (WORA), meaning that compiled Java code can run on all platforms that support Java without the need for recompilation. Java applications are typically compiled to bytecode that can run on any Java virtual machine (JVM) regardless of the underlying computer architecture. The syntax of Java is similar to C and C++, but it has fewer low-level facilities than either of them. As of 2019, Java was one of the most popular programming languages in use according to GitHub, particularly for client-server web applications, with a reported 9 million developers.

---

#### How to install Java <a name="how-to-install-java"></a>

    - Install Java on Windows
        - Download Java from Oracle website (https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
        - Install Java on Windows 10 using OpenJDK(https://adoptium.net/installation/)


![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/ka2c2pkgcld74rl74lkk.png) - Install Java on Linux - Install Java on Ubuntu - Install Java on CentOS - Install Java on Fedora - Install Java on Debian - Install Java on RHEL - Install Java on SUSE - Install Java on Mac (https://www3.ntu.edu.sg/home/ehchua/programming/howto/JDK_Howto.html)

---

#### To check if you have the java_home set <a name="to-check-if-you-have-the-java_home-set"></a>

> echo $JAVA_HOME


![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/24gv666dvq30z4ej53oz.png)

#### Check if Java is installed <a name="check-if-java-is-installed"></a>

    - Check Java version
        - Check Java version on Windows
            - java -version
        - Check Java version on Linux
            - java -version
    - Check Java path
        - echo %JAVA_HOME%

---

#### How to set Java path <a name="how-to-set-java-path"></a>

- Copy the bin folder and go to your path varibales and paste it there OR run the following commands 
- Set Java path on Windows 
- setx JAVA_HOME "C:\Program Files\Java\jdk1.8.0_131" 
- Set Java path on Linux - export JAVA_HOME=/usr/lib/jvm/java-8-oracle 
- Set Java path on Mac - export JAVA_HOME=/Library/Java/JavaVirtualMachines/jdk1.8.0_131.jdk/Contents/Home

---

#### Use jshell terminal i.e Java Shell <a name="use-jshell-terminal-ie-java-shell"></a>

Run the following command in your terminal:

```bash
jshell
```

System.out.println("hello world");

---

#### Write a Java program <a name="write-a-java-program"></a>

```java
    // Test.java
    public class Test {  // class name must be same as file name
        public static void main(String[] args) {
            System.out.println("Hello World");
        }
    }
```

---

#### How to compile Java program <a name="how-to-compile-java-program"></a>

Ensure that you are in the same directory as the Test.java file

        - javac Test.java

#### How to run Java program <a name="how-to-run-java-program"></a>

        - java Test

---

#### Variables <a name="variables"></a>

- Primitive data types (int, float, double, char, boolean, byte, short, long)

| Data type | Size    | Range                                                   |
| --------- | ------- | ------------------------------------------------------- |
| int       | 4 bytes | -2,147,483,648 to 2,147,483,647                         |
| float     | 4 bytes | 3.4e-038 to 3.4e+038                                    |
| double    | 8 bytes | 1.7e-308 to 1.7e+308                                    |
| char      | 2 bytes | 0 to 65,536                                             |
| boolean   | 1 bit   | true or false                                           |
| byte      | 1 byte  | -128 to 127                                             |
| short     | 2 bytes | -32,768 to 32,767                                       |
| long      | 8 bytes | -9,223,372,036,854,775,808 to 9,223,372,036,854,775,807 |

```java
  int a = 10; // 10 is an integer literal
  float b = 10.5f; // 10.5 is a floating point literal
  double c = 10.5; // 10.5 is a floating point literal
  char d = 'a'; // 'a' is a character literal
  boolean e = true; // true is a boolean literal
  byte f = 10;
  short g = 10;
  long h = 10;
```

##### Reference data types (String, Array, Class, Interface) <a name="reference-data-types"></a>

```java
    // examples of reference data types
    String a = "Hello World"; // "Hello World" is a string literal
    int[] b = {1, 2, 3, 4, 5};
    class Test {
        public static void main(String[] args) {
            System.out.println("Hello World");
        }
    }
    interface Test {
        public void test();
    }
```

---

##### Variable naming conventions <a name="variable-naming-conventions"></a>

- Variable names must start with a letter (A-Z or a-z), currency character (\$), or an underscore (\_).
- After the first character, variable names may contain any number of letters, digits, currency characters, or underscores.
- Variable names are case sensitive (y and Y are different variables).
- Variable names cannot be the same as Java keywords (like int or class).

Example of valid variable names:

```java
    int a;
    int a1;
    int _a;
    int $a;
    int a_b;
    int aB;
```

---

##### Reassigning variables <a name="reassigning-variables"></a>

```java
    // reassigning variables
    int a = 10;
    a = 20;
    System.out.println(a);
    // output: 20
```

---

##### Declare multiple variables <a name="declare-multiple-variables"></a>

```java
    // declare multiple variables
    int a, b, c;
    a = 10;
    b = 20;
    c = 30;
    System.out.println(a + b + c);
    // output: 60
```

---

##### Copying variables <a name="copying-variables"></a>

```java
    // copying variables
    int a = 10;
    int b = a;
    System.out.println(b);
    // output: 10
```

##### Type casting <a name="type-casting"></a>

```java
    // type casting
    int a = 10;
    float b = a;
    int c = (int) b;
    System.out.println(c);
    // output: 10
```

---

##### Type promotion <a name="type-promotion"></a>

```java
    // type promotion
    byte a = 10;
    int b = a;
    int c = 10;
    long d = c;
    float e = d;
    double f = e;
    System.out.println(f);
    // output: 10.0
```

---

##### Type conversion <a name="type-conversion"></a>

```java
    // type conversion
    int a = 10;
    String b = String.valueOf(a);
    int c = Integer.parseInt(b);
```

---

##### String concatenation <a name="string-concatenation"></a>

```java
    // string concatenation
    String a = "Hello";
    String b = "World";
    String c = a + b;
    System.out.println(c);
```

---

##### String comparison <a name="string-comparison"></a>

```java
    // string comparison
    String a = "Hello";
    String b = "World";
    boolean c = a.equals(b);
```

---

##### String formatting <a name="string-formatting"></a>

```java
    // string format
    String a = String.format("Hello %s", "World");
    System.out.println(a);
    // output: Hello World
```

---

##### NumberFormat <a name="numberformat"></a>

The NumberFormat class is used to format numbers in a locale-sensitive manner. It provides a number of methods for formatting numbers in different ways.

```java
    // number format
    NumberFormat currency = NumberFormat.getCurrencyInstance();
    String result = currency.format(1234567.891);
    System.out.println(result);
    // output: $1,234,567.89
```

```java
    // number format
    NumberFormat percent = NumberFormat.getPercentInstance();
    String result = percent.format(0.1);
    System.out.println(result);
    // output: 10%
```

```java
    // number format
    NumberFormat number = NumberFormat.getNumberInstance();
    String result = number.format(1234567.891);
    System.out.println(result);
    // output: 1,234,567.891
```

---

```java
public class Main {
    public static void main(String[] args) {
        String name = "Farhan";
        int age = 27;

        String formattedString = String.format("My name is %s and I'm %d years old.", name, age);

        System.out.println(formattedString);
        // output: My name is Farhan and I'm 27 years old.
    }

}

```

---

##### String methods <a name="string-methods"></a>

```java
    // string methods
    String a = "Hello World";
    int b = a.length(); // 11
    String c = a.toUpperCase(); // HELLO WORLD
    String d = a.toLowerCase(); // hello world
    String e = a.trim(); // Hello World
    String f = a.substring(0, 5); // Hello
    String g = a.replace("Hello", "Hi"); // Hi World
    String h = a.concat("!"); // Hello World!
    String i = a.charAt(0); // H
    String j = a.indexOf("World"); // 6
    String k = a.lastIndexOf("World");
    String l = a.startsWith("Hello"); // true
    String m = a.endsWith("World"); // true
    String n = a.contains("World"); // true
    String o = a.split(" "); // ["Hello", "World"]
    String p = a.split(" ")[0]; // Hello
    String q = a.split(" ")[1]; // World
    String z = a.indexOf("World") != -1; // true
```

##### String escape characters <a name="string-escape-characters"></a>

```java
    // string escape characters
    String a = "Hello\nWorld"; // Hello       - new line
                                // World
    String b = "Hello\tWorld"; // Hello   World - tab
    String c = "Hello\"World"; // Hello"World - double quote
    String d = "Hello\\World"; // Hello\World - backslash
```

---

##### Type of variables <a name="type-of-variables"></a>

```java
    // type of
    int a = 10;
    String b = "Hello";
    System.out.println(a instanceof Integer);
    System.out.println(b instanceof String);
    // output: true
```

```java
   Double result = Math.random() * 100;
        System.out.println(result.toString());
        // type of result
        System.out.println(result.getClass().getName());
        // type of result
        System.out.println(result instanceof Double);
```

---

##### Constants <a name="constants"></a>

This is a constant variable that cannot be changed. It is declared using the final keyword.

```java
    // constants
    final int a = 10;
    final String b = "Hello";
    final int[] c = {1, 2, 3, 4, 5};
    final int d;
    d = 10;

    // a = 20; // error
    // b = "World"; // error
    // c = {1, 2, 3, 4, 5, 6}; // error

```

---

#### Operators <a name="operators"></a>

##### Arithmetic operators ( +, -, \*, /, %, ++, -- )

```java
    int a = 10;
    int b = 20;
    int c = a + b; // 30
    int d = a - b; // -10
    int e = a * b; // 200
    int f = a / b; // 0 (integer division). To get the correct result, one of the operands must be a double.
    int g = a % b; // 10
    int h = a++;
    int i = a--;
    int j = ++a;
    int k = --a;
```

---

##### Order of operations

```java
    int a = 10 + 20 * 30; // This is the same as 10 + (20 * 30) = 610. i.e the multiplication is done first and then the addition.
    int b = (10 + 20) * 30; // This is the same as (10 + 20) = 30 * 30 = 900. i.e the addition is done first and then the multiplication.
    int c = 10 + 20 * 30 / 40; // This is the same as 10 + (20 * 30) / 40 = 610 / 40 = 15. i.e the multiplication is done first, then the division and then the addition.
    int d = (10 + 20) * 30 / 40; // This is the same as (10 + 20) = 30 * 30 / 40 = 900 / 40 = 22.5. i.e the addition is done first, then the multiplication and then the division.
```

---

##### Unary operators ( +, -, ++, --, !, ~ )

```java
 int a = 10;
 int b = -a; // -10
 int c = +a; // 10
 int d = a++; // 10
 int e = a--;
 boolean f = !a; // false
 int g = ~a;
```

---

##### Relational operators ( ==, !=, >, <, >=, <= )

```java
    int a = 10;
    int b = 20;
    boolean c = a == b; // false
    boolean d = a != b; // true
    boolean e = a > b; // false
    boolean f = a < b; // true
    boolean g = a >= b; // false
    boolean h = a <= b; // true
```

---

#### Logical operators ( &&, ||, ! )

```java
    int a = 10;
    int b = 20;
    boolean c = a > 5 && b > 5;
    boolean d = a > 5 || b > 5;
    boolean e = !(a > 5);
```

---

##### Bitwise operators ( &, |, ^, ~, <<, >>, >>> )

```java
    int a = 10;
    int b = 20;
    int c = a & b; // 0
    int d = a | b;
    int e = a ^ b;
    int f = ~a;
    int g = a << b;
    int h = a >> b;
    int i = a >>> b;
```

---

##### Assignment operators ( =, +=, -=, \*=, /=, %=, &=, |=, ^=, >>=, <<=, >>>= )

```java
    int a = 10;
    int b = 20;
    a += b;
    a -= b;
    a *= b;
    a /= b;
    a %= b;
    a &= b;
    a |= b;
    a ^= b;
    a >>= b;
    a <<= b;
    a >>>= b;
```

---

##### Ternary operators ( ?: )

```java
    int a = 10;
    int b = 20;
    int c = a > b ? a : b;
    System.out.println(c);
    // output: 20
```

---

##### Misc operators ( instanceof, -> )

```java
    int a = 10;
    boolean b = a instanceof Integer; // this is used to check the type of a variable
    System.out.println(b);
    // output: true
```

---

##### Data Types <a name="data-types"></a>

- Primitive data types (int, float, double, char, boolean, byte, short, long)

```java
        int a = 10;
        float b = 10.5f; // or 10.5F Here F is mandatory for float data type
        double c = 10.5;
        char d = 'a';
        boolean e = true;
        byte f = 10;
        short g = 10;
        long h = 10L; // or 10L Here L is mandatory for long data type
```

---

##### Reference data types (String, Array, Class, Interface)

```java
        // examples of reference data types
        LocalDate date = LocalDate.now();
        Date date = new Date();s
        String a = "Hello World";
        int[] b = {1, 2, 3, 4, 5};
        class Test {
            public static void main(String[] args) {
                System.out.println("Hello World");
            }
        }
        interface Test {
            public void test();
        }
```

---

##### Dates classes <a name="dates-classes"></a>

- LocalDate, LocalTime, LocalDateTime

```java
        LocalDate date = LocalDate.now();
        LocalTime time = LocalTime.now();
        LocalDateTime dateTime = LocalDateTime.now();
        DateTimeFormatter formatter = DateTimeFormatter.ofPattern("dd-MM-yyyy HH:mm:ss");
        String formattedDateTime = dateTime.format(formatter);
        System.out.println(formattedDateTime);

        Date date = new Date();
        SimpleDateFormat formatter = new SimpleDateFormat("dd-MM-yyyy HH:mm:ss");
        String formattedDateTime = formatter.format(date);
```

---

#### public vs private <a name="public-vs-private"></a>

- public
  - accessible from anywhere
- private
  - accessible only within the class

---

#### static vs non-static <a name="static-vs-non-static"></a>

- static
  - belongs to the class
  - can be accessed without creating an object
- non-static
  - belongs to the object
  - can be accessed only after creating an object

Example:

```java
class Test {
    public static void main(String[] args) {
        // static method
        Test.test();
        // non-static method
        Test t = new Test();
        t.test();
    }
    public static void test() {
        System.out.println("Hello World");
    }
    public void test() {
        System.out.println("Hello World");
    }
}
```

---

#### Public vs Static <a name="public-vs-static"></a>

- public
  - accessible from anywhere
- static
  - belongs to the class
  - can be accessed without creating an object

Example:

```java
class Test {
    public static void main(String[] args) {
        // static method
        Test.test();
        // non-static method
        Test t = new Test();
        t.test();
    }
    public static void test() {
        System.out.println("Hello World");
    }
    public void test() {
        System.out.println("Hello World");
    }
}
```

---

#### Java.lang package <a name="java-lang-package"></a>

Note: All the classes in java.lang package are imported by default. So, we don't need to import them explicitly.

```java
class Lang{
    public static void main(String[] args) {
        // Object class
        Object obj = new Object();
        // String class
        String str = new String("Hello World");
        // System class
        System.out.println("Hello World");
        // Math class
        int a = Math.abs(-10);
        // Integer class
        Integer i = new Integer(10);
        // Float class
        Float f = new Float(10.5f);
        // Double class
        Double d = new Double(10.5);
        // Character class
        Character c = new Character('a');
        // Boolean class
        Boolean b = new Boolean(true);
        // Byte class
        Byte by = new Byte((byte) 10);
        // Short class
        Short s = new Short((short) 10);
        // Long class
        Long l = new Long(10);
    }
}

```

---

##### Loops <a name="loops"></a>

- For loop, While loop, Do-While loop, Enhanced for loop (for-each loop)

```java
        // for loop
        for (int i = 0; i < 10; i++) {
            System.out.println(i);
        }
        // while loop
        int i = 0;
        while (i < 10) {
            System.out.println(i);
            i++;
        }
        // do-while loop
        int i = 0;
        do {
            System.out.println(i);
            i++;
        } while (i < 10);
        // enhanced for loop
        int[] a = {1, 2, 3, 4, 5};
        for (int i : a) {
            System.out.println(i);
        }
```

---

##### Break and Continue <a name="break-and-continue"></a>

- Break

```java
        for (int i = 0; i < 10; i++) {
            if (i == 5) {
                break;
            }
            System.out.println(i);
        }
```

- Continue

```java
        for (int i = 0; i < 10; i++) {
            if (i == 5) {
                continue;
            }
            System.out.println(i);
        }
```

---

##### Loops and Array <a name="loops-and-array"></a>

```java
        int[] a = {1, 2, 3, 4, 5};
        // for loop
        for (int i = 0; i < a.length; i++) {
            System.out.println(a[i]);
        }
        // while loop
        int i = 0;
        while (i < a.length) {
            System.out.println(a[i]);
            i++;
        }
        // do-while loop
        int i = 0;
        do {
            System.out.println(a[i]);
            i++;
        } while (i < a.length);
        // enhanced for loop
        for (int i : a) {
            System.out.println(i);
        }
```

##### Loops and String <a name="loops-and-string"></a>

```java
        String str = "Hello World";
        // for loop
        for (int i = 0; i < str.length(); i++) {
            System.out.println(str.charAt(i));
        }
        // while loop
        int i = 0;
        while (i < str.length()) {
            System.out.println(str.charAt(i));
            i++;
        }
        // do-while loop
        int i = 0;
        do {
            System.out.println(str.charAt(i));
            i++;
        } while (i < str.length());
        // enhanced for loop
        for (char c : str.toCharArray()) {
            System.out.println(c);
        }
```

##### Loops using Array streams <a name="loops-using-array-streams"></a>

```java
import java.util.Arrays;

public class Main {
   public static void main(String... args) {
    // Loops
      int [] numbers ={2,3,4,5,623,23};

      Arrays.stream(numbers).forEach(System.out::println);
   }

}
```

---

##### Decrements and Increments <a name="decrements-and-increments"></a>

- Pre-increment, Post-increment, Pre-decrement, Post-decrement

```java
        int a = 10;
        // pre-increment - the value of a is incremented before the assignment
        ++a;
        // post-increment - the value of a is incremented after the assignment
        a++;
        // pre-decrement - the value of a is decremented before the assignment
        --a;
        // post-decrement - the value of a is decremented after the assignment
        a--;
```

---

##### Conditional Statements <a name="conditional-statements"></a>

- If, If-else, If-else-if, Switch

```java
        // if
        if (a > 10) {
            System.out.println("a is greater than 10");
        }
        // if-else
        if (a > 10) {
            System.out.println("a is greater than 10");
        } else {
            System.out.println("a is less than 10");
        }
        // if-else-if
        if (a > 10) {
            System.out.println("a is greater than 10");
        } else if (a < 10) {
            System.out.println("a is less than 10");
        } else {
            System.out.println("a is equal to 10");
        }
        // switch
        switch (a) {
            case 1:
                System.out.println("a is equal to 1");
                break;
            case 2:
                System.out.println("a is equal to 2");
                break;
            case 3:
                System.out.println("a is equal to 3");
                break;
            default:
                System.out.println("a is not equal to 1, 2 or 3");
        }
```

---

##### Keywords <a name="keywords"></a>

- Access Modifiers (public, private, protected, default)
  > The reason for access modifiers is security. It helps us or users no to access variables that you are not suppose to access. For example, if you have a variable that is private, you can only access it within the class. If you have a variable that is public, you can access it anywhere in your program.

Types of access modifier (Privilege or permission level)

1. Public
2. Private
3. No modifier (default)
4. Protected

| Access modifier | Class | Package | Subclass | World |
| --------------- | ----- | ------- | -------- | ----- |
| public          | Y     | Y       | Y        | Y     |
| protected       | Y     | Y       | Y        | N     |
| no modifier     | Y     | Y       | N        | N     |
| private         | Y     | N       | N        | N     |

---

##### Arrays <a name="arrays"></a>

Arrays are used to store multiple values in a single variable, instead of declaring separate variables for each value.

```java
        // declaring an array
        int[] a = new int[5];
        // initializing an array
        int[] a = {1, 2, 3, 4, 5};
        // accessing an array
        System.out.println(a[0]);
        // changing an array
        a[0] = 10;
        // looping through an array
        for (int i = 0; i < a.length; i++) {
            System.out.println(a[i]);
        }
        // enhanced for loop
        for (int i : a) {
            System.out.println(i);
        }
```

---

##### Ways of creating an array <a name="ways-of-creating-an-array"></a>

1. Declaring an array

```java
        int[] a = new int[5];
```

2. Initializing an array

```java
        int[] a = {1, 2, 3, 4, 5};
```

3. Declaring and initializing an array

```java
        int[] a = new int[]{1, 2, 3, 4, 5};
```

---

#### Arrays.toString() <a name="arraystostring"></a>

This method is used to print the array in a readable format.

```java
import java.util.Arrays;
public class Simple {
    public static void main(String... args) {
        int[] a = {1, 2, 3, 4, 5};
        System.out.println(Arrays.toString(a));
    }
}

```

---

##### Array Methods <a name="array-methods"></a>

- length

```java
        int[] a = {1, 2, 3, 4, 5};
        System.out.println(a.length);
```

- clone

```java
        int[] a = {1, 2, 3, 4, 5};
        int[] b = a.clone();
```

- equals

```java
        int[] a = {1, 2, 3, 4, 5};
        int[] b = {1, 2, 3, 4, 5};
        System.out.println(a.equals(b));
```

- fill

```java
        int[] a = new int[5];
        Arrays.fill(a, 10);
```

- sort

```java
        int[] a = {5, 4, 3, 2, 1};
        Arrays.sort(a);
```

- toString

```java
        int[] a = {1, 2, 3, 4, 5};
        System.out.println(Arrays.toString(a));
```

- binarySearch

```java
        int[] a = {1, 2, 3, 4, 5};
        System.out.println(Arrays.binarySearch(a, 3));
```

- copyOf

```java
        int[] a = {1, 2, 3, 4, 5};
        int[] b = Arrays.copyOf(a, 3);
```

- copyOfRange

```java
        int[] a = {1, 2, 3, 4, 5};
        int[] b = Arrays.copyOfRange(a, 1, 3);
```

- deepEquals

```java
        int[][] a = {{1, 2}, {3, 4}};
        int[][] b = {{1, 2}, {3, 4}};
        System.out.println(Arrays.deepEquals(a, b));
```

- deepHashCode

```java
        int[][] a = {{1, 2}, {3, 4}};
        System.out.println(Arrays.deepHashCode(a));
```

- deepToString

```java
        int[][] a = {{1, 2}, {3, 4}};
        System.out.println(Arrays.deepToString(a));
```

- hashCode

```java
        int[] a = {1, 2, 3, 4, 5};
        System.out.println(Arrays.hashCode(a));
```

- parallelPrefix

```java
        int[] a = {1, 2, 3, 4, 5};
        Arrays.parallelPrefix(a, (x, y) -> x * y);
```

- parallelSetAll

```java
        int[] a = new int[5];
        Arrays.parallelSetAll(a, i -> i * 10);
```

- parallelSort

```java
        int[] a = {5, 4, 3, 2, 1};
        Arrays.parallelSort(a);
```

- setAll

```java
        int[] a = new int[5];
        Arrays.setAll(a, i -> i * 10);
```

- spliterator

```java
        int[] a = {1, 2, 3, 4, 5};
        Spliterator.OfInt s = Arrays.spliterator(a);
```

- stream

```java
        int[] a = {1, 2, 3, 4, 5};
        IntStream s = Arrays.stream(a);
```

- asList

```java
        int[] a = {1, 2, 3, 4, 5};
        List<Integer> l = Arrays.asList(a);
```

- deepHashCode

```java
        int[][] a = {{1, 2}, {3, 4}};
        System.out.println(Arrays.deepHashCode(a));
```

- deepToString

```java
        int[][] a = {{1, 2}, {3, 4}};
        System.out.println(Arrays.deepToString(a));
```

---

##### Arrays and indexes <a name="arrays-and-indexes"></a>

```java
        int[] a = {1, 2, 3, 4, 5};
        System.out.println(a[0]);
        System.out.println(a[1]);
        System.out.println(a[2]);
        System.out.println(a[3]);
        System.out.println(a[4]);
        // System.out.println(a[5]); // ArrayIndexOutOfBoundsException
        // output: 1 2 3 4 5
```

---

##### Mixed Data Types <a name="mixed-data-types"></a>

```java
        Object[] a = {1, "Hello", 2.5};
```

---

##### Multidimensional Arrays <a name="multidimensional-arrays"></a>


```java
        int[][] a = {{1, 2}, {3, 4}};
```

---

##### Jagged Arrays

```java
        int[][] a = {{1, 2}, {3, 4, 5}};
```

---

##### Classes and Objects <a name="classes-and-objects"></a>

Classes are the basics of object-oriented programming. A class is a user-defined blueprint or prototype from which objects are created. It represents the set of properties or methods that are common to all objects of one type.

```java
public class Student {
    int id;
    String name;
}
```

---

##### Objects <a name="objects"></a>

Objects are the instances of a class. An object contains an address and takes up some space in memory. It can be assigned to a variable.

```java
public class Student {
    int id;
    String name;
}
```

```java
public class Simple {
    public static void main(String... args) {
        Student s1 = new Student();
        s1.id = 1;
        s1.name = "John";
        System.out.println(s1.id + " " + s1.name);
    }
}
```

---

##### Fields <a name="fields"></a>

Fields are variables that belong to the class. Fields are also known as attributes or properties.

```java
public class Student { // this is a class
    int id; // this is a field
    String name;
}
```

```java
public class Simple {
    public static void main(String... args) {
        Student s1 = new Student();
        s1.id = 1;
        s1.name = "John";
        System.out.println(s1.id + " " + s1.name);
    }
}
```

---

##### Methods <a name="methods"></a>

Methods are a block of code that perform a specific task. Methods are used to perform certain actions, and they are also known as functions.

```java
public class Simple {
    public static void main(String... args) {
        // calling a method
        printSomething();
    }
    // defining a method
    public static void printSomething() {
        System.out.println("Hello World");
    }
}
```

---

##### Constructors <a name="constructors"></a>

Constructors are used to initialize the object. It is called when an object of a class is created. It can be used to set initial values for object attributes.

```java
public class Student {
    int id;
    String name;

    // creating a constructor - this creates a default constructor for the class
    public Student(int id, String name) {
        this.id = id;
        this.name = name;
    }


    public void display() {
        System.out.println(id + " " + name);
    }
    public static void main(String[] args) {
        Student s1 = new Student(111, "Karan");
        Student s2 = new Student(222, "Aryan");
        s1.display();
        s2.display();
    }
}
```

---

##### Class <a name="class"></a>

A class is a user-defined blueprint or prototype from which objects are created. It represents the set of properties or methods that are common to all objects of one type.

```java
public class Student { // class declaration
    int id; // instance variable
    String name; // instance variable
    public void display() { // method
        System.out.println(id + " " + name);
    }

    // main method
    public static void main(String[] args) {
        Student s1 = new Student(); // creating an object of Student
        Student s2 = new Student();
        s1.id = 111; // accessing member through reference variable
        s1.name = "Karan";
        s2.id = 222;
        s2.name = "Aryan";
        s1.display();
        s2.display();
    }
}
```

---

##### Math Class Operations <a name="math-class-operations"></a>

The java.lang.Math class is a part of the Java API. It provides us with a large number of methods that perform mathematical operations on primitive data types. The methods of the Math class are static, so we can call them without creating an object of the Math class.

```java
public class MathClass {
    public static void main(String[] args) {
        System.out.println(Math.abs(-26.7));
        System.out.println(Math.ceil(7.4));
        System.out.println(Math.floor(7.4));
        System.out.println(Math.max(8.6, 5.2));
        System.out.println(Math.min(8.6, 5.2));
        System.out.println(Math.pow(5, 3));
        System.out.println(Math.sqrt(64));
    }
}
```

---

##### Object <a name="object"></a>

An object is a basic unit of Object Oriented Programming and represents the real-life entities. A typical java program creates many objects, which as you know, interact by invoking methods.

```java
public class Student {
    int id;
    String name;
    public void display() {
        System.out.println(id + " " + name);
    }
    public static void main(String[] args) {
        Student s1 = new Student();
        Student s2 = new Student();
        s1.id = 111;
        s1.name = "Karan";
        s2.id = 222;
        s2.name = "Aryan";
        s1.display();
        s2.display();
    }
}
```

---

##### Getters and Setters <a name="getters-and-setters"></a>

Getters and setters are methods that provide access to the object’s properties. Getters return the value of the property, and setters set the value of the property.

```java
public class Student {
    private int id;
    private String name;

    public int getId() { // getter  for id - returns the value of id
        return id;
    }

    public void setId(int id) { // setter for id - sets the value of id
        this.id = id;
    }

    public String getName() { // getter for name - returns the value of name
        return name;
    }

    public void setName(String name) { // setter for name - sets the value of name
        this.name = name;
    }
}
```

---

##### toString() Method <a name="tostring-method"></a>

The toString() method returns the string representation of the object. If you print any object, java compiler internally invokes the toString() method on the object. So, overriding the toString() method, returns the desired output, it can be the state of an object etc. depending on your implementation.

```java
public class Student {
    int id;
    String name;
    public Student(int id, String name) {
        this.id = id;
        this.name = name;
    }
    public String toString() {
        return id + " " + name;
    }
    public static void main(String[] args) {
        Student s1 = new Student(111, "Karan");
        Student s2 = new Student(222, "Aryan");
        System.out.println(s1);
        System.out.println(s2);
    }
}
```

---

##### Inheritance <a name="inheritance"></a>

Inheritance is a mechanism in which one object acquires all the properties and behaviors of a parent object. It is an important part of OOPs (Object Oriented programming system). It is used to achieve runtime polymorphism.

```java
class Computer {
    public void computerMethod() {
        System.out.println("This is a computer");
    }
}

class Laptop extends Computer {
    public void laptopMethod() {
        System.out.println("This is a laptop");
    }
}

class Desktop extends Computer {
    public void desktopMethod() {
        System.out.println("This is a desktop");
    }
}

public class Main {
    public static void main(String[] args) {
        Laptop laptop = new Laptop();
        laptop.computerMethod();
        laptop.laptopMethod();
        Desktop desktop = new Desktop();
        desktop.computerMethod();
        desktop.desktopMethod();
    }
}
```

---

##### Method <a name="method"></a>

A method is a block of code which only runs when it is called. You can pass data, known as parameters, into a method. Methods are used to perform certain actions, and they are also known as functions. In this chapter, we will learn how to create methods with or without parameters, and how to call a method.

```java
public class Simple {
    public static void main(String... args) {
        printSomething();
    }
    public static void printSomething() {
        System.out.println("Hello World");
    }
}
```

---

#### Method overloading <a name="method-overloading"></a>

Method overloading is a feature that allows a class to have more than one method having the same name, if their argument lists are different. It is similar to constructor overloading in Java, that allows a class to have more than one constructor having different argument lists.

```java
public class MethodOverloading {
    public static void main(String[] args) {
        System.out.println(Add(11, 11));
        System.out.println(Add(11, 11, 11));
        System.out.println(Add(11.5, 11.5));
    }
    public static int Add(int a, int b) {
        return a + b;
    }
    public static int Add(int a, int b, int c) {
        return a + b + c;
    }
    public static double Add(double a, double b) {
        return a + b;
    }
}
```

---

##### Wrapper Class <a name="wrapper-class"></a>

Wrapper classes are used to convert primitive data types into objects. The primitive data types are boolean, char, byte, short, int, long, float, and double. All the wrapper classes are immutable (unchangeable).

```java
public class WrapperClass {
    public static void main(String[] args) {
        // Converting int into Integer
        int a = 20;
        Integer i = Integer.valueOf(a); // converting int into Integer
        Integer j = a; // autoboxing, now compiler will write Integer.valueOf(a) internally
        System.out.println(a + " " + i + " " + j);
        // Converting Integer to int
        Integer b = new Integer(3);
        int c = b.intValue(); // converting Integer to int
        int d = b; // unboxing, now compiler will write a.intValue() internally
        System.out.println(b + " " + c + " " + d);
    }
}
```

---

##### Inheritance <a name="inheritance"></a>

Inheritance is a mechanism in which one object acquires all the properties and behaviors of a parent object. It is an important part of OOPs (Object Oriented programming system). It is used to achieve runtime polymorphism.

```java
class Computer {
    public void computerMethod() {
        System.out.println("This is a computer");
    }
}

class Laptop extends Computer {
    public void laptopMethod() {
        System.out.println("This is a laptop");
    }
}

class Desktop extends Computer {
    public void desktopMethod() {
        System.out.println("This is a desktop");
    }
}

public class Main {
    public static void main(String[] args) {
        Laptop laptop = new Laptop();
        laptop.computerMethod();
        laptop.laptopMethod();
        Desktop desktop = new Desktop();
        desktop.computerMethod();
        desktop.desktopMethod();
    }
}
```

---

##### Polymorphism <a name="polymorphism"></a>

Polymorphism means "many forms", and it occurs when we have many classes that are related to each other by inheritance.

```java
class Animal {
    public void animalSound() {
        System.out.println("The animal makes a sound");
    }
}

class Pig extends
Animal {
    public void animalSound() {
        System.out.println("The pig says: wee wee");
    }
}

class Dog extends
Animal {
    public void animalSound() {
        System.out.println("The dog says: bow wow");
    }
}

public class Main {
    public static void main(String[] args) {
        Animal myAnimal = new Animal(); // Create a Animal object
        Animal myPig = new Pig(); // Create a Pig object
        Animal myDog = new Dog(); // Create a Dog object
        myAnimal.animalSound();
        myPig.animalSound();
        myDog.animalSound();
    }
}
```

---

##### Abstraction <a name="abstraction"></a>

Abstraction is a process of hiding the implementation details and showing only functionality to the user. There are two ways to achieve abstraction in java

- Abstract class (0 to 100%)
- Interface (100%)

```java
abstract class Shape {
    abstract void draw();
}

class Rectangle extends Shape {
    void draw() {
        System.out.println("drawing rectangle");
    }
}

class Circle1 extends Shape {
    void draw() {
        System.out.println("drawing circle");
    }
}

public class TestAbstraction1 {
    public static void main(String[] args) {
        Shape s = new Circle1();// In a real scenario, object is provided through method, e.g., getShape() method
        s.draw();
    }
}
```

---

##### Encapsulation <a name="encapsulation"></a>

Encapsulation is defined as the wrapping up of data under a single unit. It is the mechanism that binds together code and the data it manipulates.

```java
class Encapsulation {
    private String name;
    private int age;
    private int idNum;
    private String department;
    private String position;
    public int getIdNum() {
        return idNum;
    }
    public String getName() {
        return name;
    }
    public int getAge() {
        return age;
    }
    public String getDepartment() {
        return department;
    }
    public String getPosition() {
        return position;
    }
    public void setIdNum(int newId) {
        idNum = newId;
    }
    public void setName(String newName) {
        name = newName;
    }
    public void setAge(int newAge) {
        age = newAge;
    }
    public void setDepartment(String newDepartment) {
        department = newDepartment;
    }
    public void setPosition(String newPosition) {
        position = newPosition;
    }
}

public class TestEncapsulation {
    public static void main(String[] args) {
        Encapsulation obj = new Encapsulation();
        obj.setName("James");
        obj.setAge(20);
        obj.setIdNum("12343ms");
        obj.setDepartment("IT");
        obj.setPosition("Programmer");
        System.out.println("Name: " + obj.getName());
        System.out.println("Age: " + obj.getAge());
        System.out.println("ID: " + obj.getIdNum());
        System.out.println("Department: " + obj.getDepartment());
        System.out.println("Position: " + obj.getPosition());
    }
}
```

---

##### Enums <a name="enums"></a>

Enum is a special "class" that represents a group of constants (unchangeable variables, like final variables).

```java
enum Level {
    LOW,
    MEDIUM,
    HIGH
}

public class Main {
    public static void main(String[] args) {
        Level myVar = Level.MEDIUM;
        System.out.println(myVar);
    }
}
```

---

##### Loop through the enum values with the values() method <a name="loop-through-the-enum-values-with-the-values-method"></a>

```java

enum Level {
LOW,
MEDIUM,
HIGH
}

public class Main {
public static void main(String[] args) {
for (Level myVar : Level.values()) {
System.out.println(myVar);
}
}
}

```

---

##### Get the Enum value  <a name="get-the-enum-value"></a>


```java
enum Level {
    LOW,
    MEDIUM,
    HIGH
}

public class Main {
    public static void main(String[] args) {
        Level myVar = Level.valueOf("HIGH");
        System.out.println(myVar);
    }
}
```

##### Interfaces <a name="interfaces"></a>

An interface is a completely "abstract class" that is used to group related methods with empty bodies:

```java
interface Animal {
    public void animalSound(); // interface method (does not have a body)
    public void sleep(); // interface method (does not have a body)
}

class Pig implements Animal {
    public void animalSound() {
        // The body of animalSound() is provided here
        System.out.println("The pig says: wee wee");
    }
    public void sleep() {
        // The body of sleep() is provided here
        System.out.println("Zzz");
    }
}

class MyMainClass {
    public static void main(String[] args) {
        Pig myPig = new Pig(); // Create a Pig object
        myPig.animalSound();
        myPig.sleep();
    }
}
```

---

##### Exception <a name="exception"></a>

An exception is an event, which occurs during the execution of a program, that disrupts the normal flow of the program's instructions.

```java
public class TestException {
    public static void main(String args[]) {
        try {
            int a[] = new int[2];
            System.out.println("Access element three :" + a[3]);
        } catch (ArrayIndexOutOfBoundsException e) {
            System.out.println("Exception thrown  :" + e);
        }
        System.out.println("Out of the block");
    }
}
```

---

##### Collections <a name="collections"></a>

A collection is a group of individual objects represented as a single unit. Java provides a framework that enables us to manipulate a group of objects as a single unit.
Examples of Collection Framework are:ArrayList, List, Set, Queue, Deque, Map, LinkedList, HashSet, TreeSet, PriorityQueue, ArrayDeque, HashMap, TreeMap, LinkedHashMap, etc.

ArrayList is a collection class which implements List interface. It is used to create a dynamic array. It is like an array, but there is no size limit. We can add or remove elements anytime.

```java
import java.util.*;
public class TestCollection {
    public static void main(String args[]) {
        ArrayList<String> list = new ArrayList<String>(); //Creating arraylist
        list.add("Mango"); //Adding object in arraylist
        list.add("Apple");
        list.add("Banana");
        list.add("Grapes");
        //Traversing list through Iterator
        Iterator itr = list.iterator();
        while (itr.hasNext()) {
            System.out.println(itr.next());
        }
    }
}
```

List is an ordered collection (also known as a sequence). The user of this interface has precise control over where in the list each element is inserted. The user can access elements by their integer index (position in the list), and search for elements in the list.

```java
import java.util.*;
public class TestCollection2 {
    public static void main(String args[]) {
        List<String> list = new ArrayList<String>(); //Creating arraylist
        list.add("Mango"); //Adding object in arraylist
        list.add("Apple");
        list.add("Banana");
        list.add("Grapes");
        //Traversing list through Iterator
        Iterator itr = list.iterator();
        while (itr.hasNext()) {
            System.out.println(itr.next());
        }
    }
}
```

Set is a collection that cannot contain duplicate elements. Set interface models the mathematical set abstraction. The Set interface places additional stipulations, beyond those inherited from the Collection interface, on the contracts of all constructors and on the contracts of the add, equals and hashCode methods. Declarations for other inherited methods are also included here for convenience. (The specifications accompanying these declarations have been tailored to the Set interface, but they do not contain any additional stipulations.)

```java
import java.util.*;
public class TestCollection3 {
    public static void main(String args[]) {
        Set<String> set = new HashSet<String>(); //Creating HashSet and adding elements
        set.add("Ravi");
        set.add("Vijay");
        set.add("Ravi");
        set.add("Ajay");
        //Traversing elements
        Iterator<String> itr = set.iterator();
        while (itr.hasNext()) {
            System.out.println(itr.next());
        }
    }
}
```

Queue is an ordered collection (also known as a sequence). The user of this interface has precise control over where in the list each element is inserted. The user can access elements by their integer index (position in the list), and search for elements in the list.

```java
import java.util.*;
public class TestCollection4 {
    public static void main(String args[]) {
        Queue<String> queue = new PriorityQueue<String>(); //Creating queue and adding elements
        queue.add("Amit Sharma");
        queue.add("Vijay Raj");
        queue.add("JaiShankar");
        queue.add("Raj");
        System.out.println("head:" + queue.element());
        System.out.println("head:" + queue.peek());
        System.out.println("iterating the queue elements:");
        Iterator itr = queue.iterator();
        while (itr.hasNext()) {
            System.out.println(itr.next());
        }
        queue.remove();
        queue.poll();
        System.out.println("after removing two elements:");
        Iterator<String> itr2 = queue.iterator();
        while (itr2.hasNext()) {
            System.out.println(itr2.next());
        }
    }
}
```

Deque is a linear collection that supports element insertion and removal at both ends. The name deque is short for "double ended queue" and is usually pronounced "deck". Most Deque implementations place no fixed limits on the number of elements they may contain, but this interface supports capacity-restricted deques as well as those with no fixed size limit.

```java
import java.util.*;
public class TestCollection5 {
    public static void main(String args[]) {
        Deque<String> deque = new ArrayDeque<String>(); //Creating Deque and adding elements
        deque.add("Gautam");
        deque.add("Karan");
        deque.add("Ajay");
        //Traversing elements
        for (String str : deque) {
            System.out.println(str);
        }
    }
}
```

Map is an object that maps keys to values. A map cannot contain duplicate keys; each key can map to at most one value.

```java
import java.util.*;
public class TestCollection6 {
    public static void main(String args[]) {
        Map<Integer, String> map = new HashMap<Integer, String>(); //Creating HashMap
        map.put(100, "Amit");
        map.put(101, "Vijay");
        map.put(102, "Rahul");
        //Traversing Map
        for (Map.Entry m : map.entrySet()) {
            System.out.println(m.getKey() + " " + m.getValue());
        }
    }
}
```

LinkedList is a linear collection that supports element insertion and removal at both ends. The name deque is short for "double ended queue" and is usually pronounced "deck". Most Deque implementations place no fixed limits on the number of elements they may contain, but this interface supports capacity-restricted deques as well as those with no fixed size limit.

```java
import java.util.*;
public class TestCollection7 {
    public static void main(String args[]) {
        LinkedList<String> al = new LinkedList<String>(); //Creating object of LinkedList
        al.add("Ravi");
        al.add("Vijay");
        al.add("Ajay");
        Iterator<String> itr = al.iterator(); //Getting Iterator
        while (itr.hasNext()) {
            System.out.println(itr.next());
        }
    }
}
```

Vector is a legacy class that is similar to ArrayList. It is almost identical to ArrayList, except that it is synchronized. If a thread-safe implementation is not needed, it is recommended to use ArrayList in place of Vector.

```java
import java.util.*;
public class TestCollection8 {
    public static void main(String args[]) {
        Vector<String> v = new Vector<String>(); //Creating vector
        v.add("Ayush");
        v.add("Amit");
        v.add("Ashish");
        v.add("Garima");
        Iterator<String> itr = v.iterator(); //Traversing the vector element
        while (itr.hasNext()) {
            System.out.println(itr.next());
        }
    }
}
```

Stack is a legacy class that is similar to the Vector class. It implements a last-in-first-out (LIFO) stack of objects. It extends class Vector with five operations that allow a vector to be treated as a stack. The usual push and pop operations are provided, as well as a method to peek at the top item on the stack, a method to test for whether the stack is empty, and a method to search the stack for an item and discover how far it is from the top.

```java
import java.util.*;
public class TestCollection9 {
    public static void main(String args[]) {
        Stack<String> stack = new Stack<String>(); //Creating object of Stack
        stack.push("Ayush");
        stack.push("Garvit");
        stack.push("Amit");
        stack.push("Ashish");
        stack.push("Garima");
        stack.pop();
        Iterator<String> itr = stack.iterator(); //Traversing elements
        while (itr.hasNext()) {
            System.out.println(itr.next());
        }
    }
}
```

Hashtable is an implementation of a hash table, which maps keys to values. Any non-null object can be used as a key or as a value. To successfully store and retrieve objects from a hashtable, the objects used as keys must implement the hashCode method and the equals method.

```java
import java.util.*;
public class TestCollection10 {
    public static void main(String args[]) {
        Hashtable<Integer, String> hm = new Hashtable<Integer, String>(); //Creating Hashtable
        hm.put(100, "Amit");
        hm.put(102, "Ravi");
        hm.put(101, "Vijay");
        hm.put(103, "Rahul");
        for (Map.Entry m : hm.entrySet()) {
            System.out.println(m.getKey() + " " + m.getValue());
        }
    }
}
```

Properties is a Hashtable subclass representing a persistent set of properties. The Properties can be saved to a stream or loaded from a stream. Each key and its corresponding value in the property list is a string.

```java
import java.io.*;
import java.util.*;
public class TestCollection11 {
    public static void main(String args[]) throws Exception {
        Properties p = new Properties();
        FileInputStream fis = new FileInputStream("info.properties");
        p.load(fis);
        Enumeration e = p.propertyNames();
        while (e.hasMoreElements()) {
            String key = (String) e.nextElement();
            String value = p.getProperty(key);
            System.out.println(key + " = " + value);
        }
    }
}
```

HashMap is a part of Java Collections Framework. It is used to store items in key/value pairs. It is like an array, but you can access items using keys. It is denoted as HashMap<Key, Value>. The keys and values can be of any type.

```java
import java.util.*;
public class TestCollection12 {
    public static void main(String args[]) {
        HashMap<Integer, String> map = new HashMap<Integer, String>(); //Creating HashMap
        map.put(1, "Mango");
        map.put(2, "Apple");
        map.put(3, "Banana");
        map.put(4, "Grapes");
        for (Map.Entry m : map.entrySet()) {
            System.out.println(m.getKey() + " " + m.getValue());
        }
    }
}
```

TreeMap is a part of Java Collections Framework. It is used to store items in key/value pairs. It is like an array, but you can access items using keys. It is denoted as TreeMap<Key, Value>. The keys and values can be of any type.

```java
import java.util.*;
public class TestCollection13 {
    public static void main(String args[]) {
        TreeMap<Integer, String> map = new TreeMap<Integer, String>(); //Creating TreeMap
        map.put(100, "Amit");
        map.put(102, "Ravi");
        map.put(101, "Vijay");
        map.put(103, "Rahul");
        for (Map.Entry m : map.entrySet()) {
            System.out.println(m.getKey() + " " + m.getValue());
        }
    }
}
```

HashSet is a part of Java Collections Framework. It is used to store the elements by using a mechanism called hashing. HashSet contains unique elements only. It stores the elements by using a mechanism called hashing. HashSet contains unique elements only.

```java
import java.util.*;
public class TestCollection14 {
    public static void main(String args[]) {
        HashSet<String> set = new HashSet<String>(); //Creating HashSet and adding elements
        set.add("One");
        set.add("Two");
        set.add("Three");
        set.add("Four");
        set.add("Five");
        Iterator<String> i = set.iterator(); //Traversing elements
        while (i.hasNext()) {
            System.out.println(i.next());
        }
    }
}
```

LinkedHashSet is a part of Java Collections Framework. It is used to store the elements by using a mechanism called hashing. LinkedHashSet contains unique elements only. It extends the HashSet class and implements the Set interface. It inherits all methods from HashSet class and uses a doubly linked list to store the elements.

```java
import java.util.*;
public class TestCollection15 {
    public static void main(String args[]) {
        LinkedHashSet<String> set = new LinkedHashSet<String>(); //Creating LinkedHashSet and adding elements
        set.add("One");
        set.add("Two");
        set.add("Three");
        set.add("Four");
        set.add("Five");
        Iterator<String> i = set.iterator(); //Traversing elements
        while (i.hasNext()) {
            System.out.println(i.next());
        }
    }
}
```

TreeSet is a part of Java Collections Framework. It is used to store the elements by using a mechanism called hashing. TreeSet contains unique elements only. It implements the Set interface that uses a tree for storage. It inherits AbstractSet class and implements NavigableSet interface. The objects of TreeSet stored in ascending order.

```java
import java.util.*;
public class TestCollection16 {
    public static void main(String args[]) {
        TreeSet<String> set = new TreeSet<String>(); //Creating and adding elements
        set.add("Ravi");
        set.add("Vijay");
        set.add("Ravi");
        set.add("Ajay");
        Iterator<String> i = set.iterator(); //Traversing elements
        while (i.hasNext()) {
            System.out.println(i.next());
        }
    }
}
```

---

##### Generics <a id="generics"></a>

The Java Generics is a new feature that was added to the Java programming language in JDK 5. It is a way to achieve strong type checking at compile time. It allows us to parameterize types, the way classes parameterize their members. It is also known as parameterized types, and it provides compile-time type safety that allows programmers to catch invalid types at compile time.
Examples are: ArrayList, LinkedList, HashSet, TreeSet, HashMap, TreeMap, etc.

```java
import java.util.*;
public class TestCollection17 {
    public static void main(String args[]) {
        ArrayList<String> list = new ArrayList<String>(); //Creating arraylist
        list.add("Ravi");
        list.add("Vijay");
        list.add("Ravi");
        list.add("Ajay");
        //Traversing list through Iterator
        Iterator itr = list.iterator();
        while (itr.hasNext()) {
            System.out.println(itr.next());
        }
    }
}
```

##### Iterator <a id="iterator"></a>

Iterator is an interface which is used to traverse a collection object. It is present in the java.util package and is used to get the Iterator object. Iterator interface has 3 methods: hasNext(), next(), remove().

```java
import java.util.*;
public class TestCollection18 {
    public static void main(String args[]) {
        ArrayList<String> al = new ArrayList<String>(); //Creating arraylist
        al.add("Ravi");
        al.add("Vijay");
        al.add("Ravi");
        al.add("Ajay");
        Iterator<String> itr = al.iterator(); //Traversing elements using Iterator
        while (itr.hasNext()) {
            System.out.println(itr.next());
        }
    }
}
```

##### ListIterator

ListIterator is an interface which is used to traverse a collection object in both the directions. It is present in the java.util package and is used to get the ListIterator object. ListIterator interface has 5 methods: hasNext(), next(), hasPrevious(), previous(), remove().

```java
import java.util.*;
public class TestCollection19 {
    public static void main(String args[]) {
        ArrayList<String> al = new ArrayList<String>(); //Creating arraylist
        al.add("Ravi");
        al.add("Vijay");
        al.add("Ravi");
        al.add("Ajay");
        ListIterator<String> itr = al.listIterator(); //Traversing elements in forward direction
        while (itr.hasNext()) {
            System.out.println(itr.next());
        }
        System.out.println("Traversing elements in backward direction");
        while (itr.hasPrevious()) {
            System.out.println(itr.previous());
        }
    }
}
```

##### Enumeration <a id="enumeration"></a>

Enumeration is an interface which is used to traverse a collection object. It is present in the java.util package and is used to get the Enumeration object. Enumeration interface has 2 methods: hasMoreElements(), nextElement().

```java
import java.util.*;
public class TestCollection20 {
    public static void main(String args[]) {
        Vector<String> v = new Vector<String>(); //Creating vector
        v.add("Ayush");
        v.add("Amit");
        v.add("Ashish");
        v.add("Garima");
        Enumeration e = v.elements(); //Traversing elements using Enumeration
        while (e.hasMoreElements()) {
            System.out.println(e.nextElement());
        }
    }
}
```

##### Comparable <a id="comparable"></a>

Comparable is an interface which is used to order the objects of user-defined class. It is present in the java.lang package and contains only one method named compareTo(Object). It provides a single sorting sequence only, i.e., you can sort the elements on the basis of single data member only. It is found in java.lang package.

```java
import java.util.*;
public class TestCollection21 {
    public static void main(String args[]) {
        ArrayList<Student> al = new ArrayList<Student>(); //Creating user-defined class objects
        al.add(new Student(101, "Vijay", 23));
        al.add(new Student(106, "Ajay", 27));
        al.add(new Student(105, "Jai", 21));
        Collections.sort(al); //Sorting user-defined class objects
        for (Student st : al) {
            System.out.println(st.rollno + " " + st.name + " " + st.age);
        }
    }
}

class Student implements Comparable<Student> {
    int rollno;
    String name;
    int age;
    Student(int rollno, String name, int age) {
        this.rollno = rollno;
        this.name = name;
        this.age = age;
    }
    public int compareTo(Student st) {
        if (age == st.age)
            return 0;
        else if (age > st.age)
            return 1;
        else
            return -1;
    }
}
```

##### Comparator <a id="comparator"></a>

Comparator is an interface which is used to order the objects of user-defined class. It is present in the java.util package and contains only one method named compare(Object, Object). It provides multiple sorting sequences, i.e., you can sort the elements on the basis of multiple data members like name, age, rollno, etc. It is found in java.util package.

```java
import java.util.*;
public class TestCollection22 {
    public static void main(String args[]) {
        ArrayList<Student> al = new ArrayList<Student>(); //Creating user-defined class objects
        al.add(new Student(101, "Vijay", 23));
        al.add(new Student(106, "Ajay", 27));
        al.add(new Student(105, "Jai", 21));
        Collections.sort(al, new AgeComparator()); //Sorting elements on the basis of age
        for (Student st : al) {
            System.out.println(st.rollno + " " + st.name + " " + st.age);
        }
    }
}

class Student {
    int rollno;
    String name;
    int age;
    Student(int rollno, String name, int age) {
        this.rollno = rollno;
        this.name = name;
        this.age = age;
    }
}

class AgeComparator implements Comparator<Student> {
    public int compare(Student s1, Student s2) {
        if (s1.age == s2.age)
            return 0;
        else if (s1.age > s2.age)
            return 1;
        else
            return -1;
    }
}
```

##### Multithreading <a id="multithreading"></a>

Multithreading is a Java feature that allows concurrent execution of two or more parts of a program for maximum utilization of CPU. Each part of such program is called a thread. Thus, threads are light-weight processes within a process.

How to create a thread in Java:

```java
class TestMultitasking1 extends Thread {
    public void run() {
        System.out.println("task one");
    }
    public static void main(String args[]) {
        TestMultitasking1 t1 = new TestMultitasking1();
        TestMultitasking1 t2 = new TestMultitasking1();
        t1.start();
        t2.start();
    }
}
```

##### Thread class <a id="thread-class"></a>

Thread class is present in java.lang package. It provides constructors and methods to create and perform operations on a thread. It is the direct child of Object class.

```java

class TestMultitasking2 extends Thread {
    public void run() {
        System.out.println("task one");
    }
    public static void main(String args[]) {
        TestMultitasking2 t1 = new TestMultitasking2();
        TestMultitasking2 t2 = new TestMultitasking2();
        t1.start();
        t2.start();
    }
}
```

##### Runnable interface <a id="runnable-interface"></a>

Runnable interface is present in java.lang package. It provides run() method to perform action for a thread. It is the direct child of Object class.

```java
class TestMultitasking3 implements Runnable {
    public void run() {
        System.out.println("task one");
    }
    public static void main(String args[]) {
        TestMultitasking3 m1 = new TestMultitasking3();
        Thread t1 = new Thread(m1);
        t1.start();
    }
}
```

##### Thread states <a id="thread-states"></a>

A thread can be in one of the following states:

1. New
2. Runnable
3. Running
4. Waiting
5. Time Waiting
6. Terminated

e.g 1: New state

```java
class TestMultitasking4 extends Thread {
    public void run() {
        System.out.println("task one");
    }
    public static void main(String args[]) {
        TestMultitasking4 t1 = new TestMultitasking4();
        System.out.println("Name of t1:" + t1.getName());
        System.out.println("id of t1:" + t1.getId());
        t1.start();
        t1.setName("Sonoo Jaiswal");
        System.out.println("After changing name of t1:" + t1.getName());
    }
}
```

e.g 2: Runnable state

```java
class TestMultitasking5 extends Thread {
    public void run() {
        System.out.println("task one");
    }
    public static void main(String args[]) {
        TestMultitasking5 t1 = new TestMultitasking5();
        TestMultitasking5 t2 = new TestMultitasking5();
        System.out.println("Name of t1:" + t1.getName());
        System.out.println("Name of t2:" + t2.getName());
        System.out.println("id of t1:" + t1.getId());
        t1.start();
        t2.start();
        t1.setName("Sonoo Jaiswal");
        System.out.println("After changing name of t1:" + t1.getName());
    }
}
```

e.g 3: Running state

```java
class TestMultitasking6 extends Thread {
    public void run() {
        System.out.println("task one");
    }
    public static void main(String args[]) {
        TestMultitasking6 t1 = new TestMultitasking6();
        TestMultitasking6 t2 = new TestMultitasking6();
        System.out.println("Name of t1:" + t1.getName());
        System.out.println("Name of t2:" + t2.getName());
        System.out.println("id of t1:" + t1.getId());
        t1.start();
        t2.start();
        t1.setName("Sonoo Jaiswal");
        System.out.println("After changing name of t1:" + t1.getName());
    }
}
```

e.g 4: Waiting state

```java
class TestMultitasking7 extends Thread {
    public void run() {
        for (int i = 1; i < 5; i++) {
            try {
                Thread.sleep(500);
            } catch (InterruptedException e) {
                System.out.println(e);
            }
            System.out.println(i);
        }
    }
    public static void main(String args[]) {
        TestMultitasking7 t1 = new TestMultitasking7();
        TestMultitasking7 t2 = new TestMultitasking7();
        t1.start();
        try {
            t1.join();
        } catch (Exception e) {
            System.out.println(e);
        }
        t2.start();
    }
}
```

e.g 5: Time Waiting state

```java
class TestMultitasking8 extends Thread {
    public void run() {
        for (int i = 1; i < 5; i++) {
            try {
                Thread.sleep(500);
            } catch (InterruptedException e) {
                System.out.println(e);
            }
            System.out.println(i);
        }
    }
    public static void main(String args[]) {
        TestMultitasking8 t1 = new TestMultitasking8();
        TestMultitasking8 t2 = new TestMultitasking8();
        t1.start();
        try {
            t1.join(1500);
        } catch (Exception e) {
            System.out.println(e);
        }
        t2.start();
    }
}
```

e.g 6: Terminated state

```java
class TestMultitasking9 extends Thread {
    public void run() {
        System.out.println("task one");
    }
    public static void main(String args[]) {
        TestMultitasking9 t1 = new TestMultitasking9();
        TestMultitasking9 t2 = new TestMultitasking9();
        System.out.println("Name of t1:" + t1.getName());
        System.out.println("Name of t2:" + t2.getName());
        System.out.println("id of t1:" + t1.getId());
        t1.start();
        t2.start();
        t1.setName("Sonoo Jaiswal");
        System.out.println("After changing name of t1:" + t1.getName());
    }
}
```



---

##### Serialization <a id="serialization"></a>

Serialization is a mechanism of writing the state of an object into a byte stream. Deserialization is the reverse process where the byte stream is used to recreate the actual Java object in memory. This mechanism is used to persist the object.

##### Serialization in Java

```java
import java.io.*;
class Student implements Serializable {
    int id;
    String name;
    public Student(int id, String name) {
        this.id = id;
        this.name = name;
    }
}
public class TestSerialization1 {
    public static void main(String args[]) throws Exception {
        Student s1 = new Student(211, "ravi");
        FileOutputStream fout = new FileOutputStream("f.txt");
        ObjectOutputStream out = new ObjectOutputStream(fout);
        out.writeObject(s1);
        out.flush();
        System.out.println("success");
    }
}
```

##### Deserialization in Java

```java
import java.io.*;
class Student implements Serializable {
    int id;
    String name;
    public Student(int id, String name) {
        this.id = id;
        this.name = name;
    }
}
public class TestDeserialization1 {
    public static void main(String args[]) throws Exception {
        Student s1;
        FileInputStream fin = new FileInputStream("f.txt");
        ObjectInputStream in = new ObjectInputStream(fin);
        s1 = (Student) in.readObject();
        System.out.println(s1.id + " " + s1.name);
    }
}
```

---

##### I/O <a id="io"></a>

I/O stands for Input/Output. It is a mechanism to communicate between two entities. In Java, I/O is divided into two categories:

1. Byte Stream
2. Character Stream

##### Byte Stream

Byte stream is used to perform input and output of 8-bit bytes. If you are dealing with image or video, you should go for byte stream. It is used to perform input and output of 8-bit bytes. If you are dealing with image or video, you should go for byte stream. It is found in java.io package.

```java
import java.io.*;
public class TestIO1 {
    public static void main(String args[]) throws Exception {
        FileOutputStream fout = new FileOutputStream("testout.txt");
        fout.write(65);
        fout.close();
        System.out.println("success...");
    }
}
```

##### Character Stream

Character stream is used to perform input and output for 16-bit unicode. If you are dealing with text data, you should go for character stream. It is found in java.io package.

```java
import java.io.*;
public class TestIO2 {
    public static void main(String args[]) throws Exception {
        FileWriter fout = new FileWriter("testout.txt");
        fout.write("Welcome to javaTpoint.");
        fout.close();
        System.out.println("success...");
    }
}
```

##### Buffered Stream

Buffered stream adds additional functionality to the input and output stream. Buffered stream keeps the data in buffer. It reduces the number of I/O operations. It is found in java.io package.

```java
import java.io.*;

public class TestIO3 {
    public static void main(String args[]) throws Exception {
        FileOutputStream fout = new FileOutputStream("testout.txt");
        BufferedOutputStream bout = new BufferedOutputStream(fout);
        String s = "Welcome to javaTpoint.";
        byte b[] = s.getBytes();
        bout.write(b);
        bout.flush();
        bout.close();
        fout.close();
        System.out.println("success...");
    }
}
```

##### Data Stream

Data stream is used for java primitive data types. It is found in java.io package.

```java
import java.io.*;

public class TestIO4 {
    public static void main(String args[]) throws Exception {
        FileOutputStream fout = new FileOutputStream("testout.txt");
        DataOutputStream dout = new DataOutputStream(fout);
        dout.writeInt(65);
        dout.flush();
        dout.close();
        fout.close();
        System.out.println("success...");
    }
}
```

##### Sequence Stream

Sequence stream is used to read data from multiple streams. It is found in java.io package.

```java
import java.io.*;

public class TestIO5 {
    public static void main(String args[]) throws Exception {
        FileInputStream fin1 = new FileInputStream("f1.txt");
        FileInputStream fin2 = new FileInputStream("f2.txt");
        SequenceInputStream sis = new SequenceInputStream(fin1, fin2);
        int j;
        while ((j = sis.read()) != -1) {
            System.out.print((char) j);
        }
        sis.close();
        fin1.close();
        fin2.close();
    }
}
```

##### Object Stream

Object stream is used to perform serialization and deserialization of an object. It is found in java.io package.

```java
import java.io.*;

class Student implements Serializable {
    int id;
    String name;

    public Student(int id, String name) {
        this.id = id;
        this.name = name;
    }
}

public class TestIO6 {
    public static void main(String args[]) throws Exception {
        FileOutputStream fout = new FileOutputStream("f.txt");
        ObjectOutputStream out = new ObjectOutputStream(fout);
        Student s1 = new Student(211, "ravi");
        out.writeObject(s1);
        out.flush();
        System.out.println("success");
    }
}
```

##### Piped Stream

Piped stream is used to communicate between two threads. It is found in java.io package.

```java
import java.io.*;

class Sender extends Thread {
    PipedOutputStream out = new PipedOutputStream();

    public PipedOutputStream getOutputStream() {
        return out;
    }

    public void run() {
        try {
            out.write("Welcome to javaTpoint.".getBytes());
        } catch (Exception e) {
        }
    }
}

class Receiver extends Thread {
    PipedInputStream in;

    public Receiver(Sender sender) throws Exception {
        in = new PipedInputStream(sender.getOutputStream());
    }

    public void run() {
        try {
            int i;
            while ((i = in.read()) != -1) {
                System.out.print((char) i);
            }
        } catch (Exception e) {
        }
    }
}

public class TestIO7 {
    public static void main(String args[]) throws Exception {
        Sender sender = new Sender();
        Receiver receiver = new Receiver(sender);
        sender.start();
        receiver.start();
    }
}
```

##### File Stream

File stream is used to perform input and output operation for files. It is found in java.io package.

```java
import java.io.*;

public class TestIO8 {
    public static void main(String args[]) throws Exception {
        FileInputStream fin = new FileInputStream("f.txt");
        int i = 0;
        while ((i = fin.read()) != -1) {
            System.out.print((char) i);
        }
        fin.close();
    }
}
```

##### String Reader <a name="string-reader"></a>

String reader is used to read data from string. It is found in java.io package.

```java
import java.io.*;

public class TestIO9 {
    public static void main(String args[]) throws Exception {
        String srg = "Welcome to javaTpoint.";
        char[] ch = new char[srg.length()];
        StringReader reader = new StringReader(srg);
        reader.read(ch);
        for (char c : ch) {
            System.out.print(c);
        }
        reader.close();
    }
}
```

##### String Writer <a name="string-writer"></a>

String writer is used to write data into string. It is found in java.io package.

```java
import java.io.*;

public class TestIO10 {
    public static void main(String args[]) throws Exception {
        StringWriter writer = new StringWriter();
        writer.write("Welcome to javaTpoint.");
        writer.flush();
        System.out.println(writer.toString());
        writer.close();
    }
}
```

##### Pushback Reader <a name="pushback-reader"></a>

Pushback reader is used to push back the data into stream. It is found in java.io package.

```java
import java.io.*;

public class TestIO11 {
    public static void main(String args[]) throws Exception {
        String srg = "Welcome to javaTpoint.";
        char[] ch = new char[srg.length()];
        StringReader reader = new StringReader(srg);
        PushbackReader push = new PushbackReader(reader);
        int i;
        while ((i = push.read()) != -1) {
            if (i == 'o') {
                push.unread(i);
                i = push.read();
                System.out.print((char) i);
            } else {
                System.out.print((char) i);
            }
        }
    }
}
```

##### Buffered Reader <a name="buffered-reader"></a>

Buffered reader is used to read data line by line. It is found in java.io package.

```java
import java.io.*;

public class TestIO12 {
    public static void main(String args[]) throws Exception {
        FileReader fr = new FileReader("f.txt");
        BufferedReader br = new BufferedReader(fr);
        int i;
        while ((i = br.read()) != -1) {
            System.out.print((char) i);
        }
        br.close();
        fr.close();
    }
}
```

##### Buffered Writer <a name="buffered-writer"></a>

Buffered writer is used to write data line by line. It is found in java.io package.

```java
import java.io.*;

public class TestIO13 {
    public static void main(String args[]) throws Exception {
        FileWriter fw = new FileWriter("f.txt");
        BufferedWriter bw = new BufferedWriter(fw);
        bw.write("Welcome to javaTpoint.");
        bw.flush();
        bw.close();
        fw.close();
    }
}
```

##### Data Stream <a name="data-stream"></a>

Data stream is used to read and write primitive data types. It is found in java.io package.

```java
import java.io.*;

public class TestIO14 {
    public static void main(String args[]) throws Exception {
        FileOutputStream fout = new FileOutputStream("f.txt");
        DataOutputStream dout = new DataOutputStream(fout);
        dout.writeInt(65);
        dout.flush();
        dout.close();
        fout.close();
        System.out.println("success");
    }
}
```

---

##### Error Handling <a name="error-handling"></a>

Error handling is a mechanism to handle the run time errors so that normal flow of the application can be maintained. It is found in java.lang package.

```java
import java.lang.*;

public class TestError {
    public static void main(String args[]) {
        try {
            int data = 50 / 0;
        } catch (ArithmeticException e) {
            System.out.println(e);
        }
        System.out.println("rest of the code");
    }
}
```

##### Error Handling <a name="error-handling"></a>

Error is a subclass of Throwable class. It is found in java.lang package.

```java
import java.lang.*;

public class TestError1 {
    public static void main(String args[]) {
        try {
            int data = 50 / 0;
        } catch (Error e) {
            System.out.println(e);
        }
        System.out.println("rest of the code");
    }
}
```

##### Exception <a name="exception"></a>

Exception is a subclass of Throwable class. It is found in java.lang package.

```java
import java.lang.*;

public class TestError2 {
    public static void main(String args[]) {
        try {
            int data = 50 / 0;
        } catch (Exception e) {
            System.out.println(e);
        }
        System.out.println("rest of the code");
    }
}
```

##### Exception Handling <a name="exception-handling"></a>

Exception handling is a mechanism to handle the run time errors so that normal flow of the application can be maintained. It is found in java.lang package.

```java
import java.lang.*;

public class TestError3 {
    public static void main(String args[]) {
        try {
            int data = 50 / 0;
        } catch (Exception e) {
            System.out.println(e);
        }
        System.out.println("rest of the code");
    }
}
```

##### Exception Propagation <a name="exception-propagation"></a>

Exception propagation is a mechanism to propagate the exception to caller method. It is found in java.lang package.

```java
import java.lang.*;

public class TestError4 {
    public static void main(String args[]) {
        try {
            int data = 50 / 0;
        } catch (Exception e) {
            System.out.println(e);
        }
        System.out.println("rest of the code");
    }
}
```

##### Finally Block <a name="finally-block"></a>

Finally block is used to execute important code such as closing connection, stream etc. It is found in java.lang package.

```java
import java.lang.*;

public class TestError5 {
    public static void main(String args[]) {
        try {
            int data = 50 / 0;
        } catch (Exception e) {
            System.out.println(e);
        } finally {
            System.out.println("finally block is always executed");
        }
        System.out.println("rest of the code");
    }
}
```

##### Throw <a name="throw"></a>

Throw is used to explicitly throw an exception. It is found in java.lang package.

```java
import java.lang.*;

public class TestError6 {
    static void validate(int age) {
        if (age < 18)
            throw new ArithmeticException("not valid");
        else
            System.out.println("welcome to vote");
    }

    public static void main(String args[]) {
        validate(13);
        System.out.println("rest of the code...");
    }
}
```

##### Throws <a name="throws"></a>

Throws is used to declare an exception. It is found in java.lang package.

```java

import java.lang.*;

public class TestError7 {
    static void validate(int age) throws ArithmeticException {
        if (age < 18)
            throw new ArithmeticException("not valid");
        else
            System.out.println("welcome to vote");
    }

    public static void main(String args[]) {
        try {
            validate(13);
        } catch (Exception e) {
            System.out.println(e);
        }
        System.out.println("rest of the code...");
    }
}
```

##### Try Catch <a name="try-catch"></a>

Try catch is used to handle the checked exceptions. It is found in java.lang package.

```java
import java.lang.*;

public class TestError8 {
    public static void main(String args[]) {
        try {
            int data = 50 / 0;
        } catch (Exception e) {
            System.out.println(e);
        }
        System.out.println("rest of the code");
    }
}
```

##### Try Catch Finally <a name="try-catch-finally"></a>

Try catch finally is used to handle the checked exceptions. It is found in java.lang package.

```java

import java.lang.*;

public class TestError9 {
    public static void main(String args[]) {
        try {
            int data = 50 / 0;
        } catch (Exception e) {
            System.out.println(e);
        } finally {
            System.out.println("finally block is always executed");
        }
        System.out.println("rest of the code");
    }
}
```

##### Try With Resources <a name="try-with-resources"></a>

Try with resources is used to handle the checked exceptions. It is found in java.lang package.

```java
import java.lang.*;

public class TestError10 {
    public static void main(String args[]) {
        try {
            int data = 50 / 0;
        } catch (Exception e) {
            System.out.println(e);
        } finally {
            System.out.println("finally block is always executed");
        }
        System.out.println("rest of the code");
    }
}
```

##### Unchecked Exception

Unchecked exception is a subclass of RuntimeException class. It is found in java.lang package.

```java

import java.lang.*;

public class TestError11 {
    public static void main(String args[]) {
        try {
            int data = 50 / 0;
        } catch (Exception e) {
            System.out.println(e);
        }
        System.out.println("rest of the code");
    }
}
```

##### User Defined Exception <a name="user-defined-exception"></a>

User defined exception is a subclass of Exception class. It is found in java.lang package.

```java
import java.lang.*;

public class TestError12 {
    public static void main(String args[]) {
        try {
            int data = 50 / 0;
        } catch (Exception e) {
            System.out.println(e);
        }
        System.out.println("rest of the code");
    }
}
```

##### Checked Exception <a name="checked-exception"></a>

Checked exception is a subclass of Exception class. It is found in java.lang package.

```java

import java.lang.*;

public class TestError13 {
    public static void main(String args[]) {
        try {
            int data = 50 / 0;
        } catch (Exception e) {
            System.out.println(e);
        }
        System.out.println("rest of the code");
    }
}
```

---

#### Calling external APIs <a name="calling-external-apis"></a>

To call external APIS like https://jsonplaceholder.typicode.com/posts, we need to use the following code:

```java
import java.io.BufferedReader;
import java.io.InputStreamReader;
import java.net.HttpURLConnection;

import java.net.URL;

public class TestAPI {
    public static void main(String[] args) {
        try {
            URL url = new URL("https://jsonplaceholder.typicode.com/posts");
            HttpURLConnection con = (HttpURLConnection) url.openConnection();
            con.setRequestMethod("GET");
            BufferedReader in = new BufferedReader(new InputStreamReader(con.getInputStream()));
            String inputLine;
            StringBuffer content = new StringBuffer();
            while ((inputLine = in.readLine()) != null) {
                content.append(inputLine);
            }
            in.close();
            con.disconnect();
            System.out.println(content.toString());
        } catch (Exception e) {
            e.printStackTrace();
        }
    }
}
```

---

#### Calling external APIs with parameters <a name="calling-external-apis-with-parameters"></a>

To call external APIS like https://jsonplaceholder.typicode.com/posts, we need to use the following code:

```java
import java.io.BufferedReader;
import java.io.InputStreamReader;
import java.net.HttpURLConnection;

import java.net.URL;

public class TestAPI {
    public static void main(String[] args) {
        try {
            URL url = new URL("https://jsonplaceholder.typicode.com/posts");
            HttpURLConnection con = (HttpURLConnection) url.openConnection();
            con.setRequestMethod("GET");
            BufferedReader in = new BufferedReader(new InputStreamReader(con.getInputStream()));
            String inputLine;
            StringBuffer content = new StringBuffer();
            while ((inputLine = in.readLine()) != null) {
                content.append(inputLine);
            }
            in.close();
            con.disconnect();
            System.out.println(content.toString());
        } catch (Exception e) {
            e.printStackTrace();
        }
    }
}
```

---

##### Scanner Class in Java <a name="scanner-class-in-java"></a>

Scanner class is used to get the input of the primitive types like int, double, etc. and strings. It is found in java.util package.

```java
import java.util.Scanner;

public class TestScanner {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter your rollno");
        int rollno = sc.nextInt();
        System.out.println("Enter your name");
        String name = sc.next();
        System.out.println("Enter your fee");
        double fee = sc.nextDouble();
        System.out.println("Rollno:" + rollno + " name:" + name + " fee:" + fee);
        sc.close();
    }
}
```

##### System Class in Java <a name="system-class-in-java"></a>

System class is used to get the input of the primitive types like int, double, etc. and strings. It is found in java.lang package.

```java
import java.util.Scanner;

public class TestSystem {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter your rollno");
        int rollno = sc.nextInt();
        System.out.println("Enter your name");
        String name = sc.next();
        System.out.println("Enter your fee");
        double fee = sc.nextDouble();
        System.out.println("Rollno:" + rollno + " name:" + name + " fee:" + fee);
        sc.close();
    }
}
```

---

#### Regex in Java

Regex is used to match the pattern of the string. It is found in java.util.regex package.

```java
import java.util.regex.Matcher;
import java.util.regex.Pattern;

public class TestRegex {
    public static void main(String[] args) {
        Pattern p = Pattern.compile(".s");
        Matcher m = p.matcher("as");
        boolean b = m.matches();
        System.out.println(b);
        boolean b2 = Pattern.compile(".s").matcher("as").matches();
        System.out.println(b2);
        boolean b3 = Pattern.matches(".s", "as");
        System.out.println(b3);
    }
}
```

Example 2:

```java
public class Main {

        public static void main(String... args) {
        // regex to match a valid email address
        String regex = "^[a-zA-Z0-9_+&*-]+(?:\\."+
                       "[a-zA-Z0-9_+&*-]+)*@" +
                       "(?:[a-zA-Z0-9-]+\\.)+[a-z" +
                       "A-Z]{2,7}$";

        // input email address
        String email = "ab@gmail.cm";

        // check if email address is valid
        boolean result = email.matches(regex);

        if(result)
            System.out.println(email + " is a valid email address");
        else
            System.out.println(email + " is not a valid email address");
        }
}
```

---

##### Method reference <a name="method-reference"></a>

Method reference is used to refer method of functional interface. It is compact and easy form of lambda expression. Each time when you are using lambda expression to just referring a method, you can replace your lambda expression with method reference.

```java

import java.util.*;

public class TestMethodReference {
    public static void main(String[] args) {
        List<String> list = new ArrayList<String>();
        list.add("ankit");
        list.add("mayank");
        list.add("irfan");
        list.add("jai");
        list.forEach(System.out::println);
    }
}
```

---

##### Lambda expression

Lambda expression provides implementation of functional interface. It saves a lot of code. In case of lambda expression, we don't need to define the method again for providing the implementation. Here, we just write the implementation code.

```java
import java.util.*;

public class TestLambdaExpression {
    public static void main(String[] args) {
        List<String> list = new ArrayList<String>();
        list.add("ankit");
        list.add("mayank");
        list.add("irfan");
        list.add("jai");
        list.forEach(
                (n) -> System.out.println(n)
        );
    }
}
```

---

##### Java 8 Stream API <a name="java-8-stream-api"></a>

Stream API is used to process collections of objects. It provides a clear and concise way to implement lambda expressions to iterate, filter and extract data from a collection.

```java
import java.util.*;
import java.util.stream.Collectors;

public class TestStreamAPI {
    public static void main(String[] args) {
        List<String> list = new ArrayList<String>();
        list.add("ankit");
        list.add("mayank");
        list.add("irfan");
        list.add("jai");
        List<String> result = list.stream().filter(s -> s.startsWith("a")).collect(Collectors.toList());
        System.out.println(result);
    }
}
```

---

##### Java 8 Date Time API <a name="java-8-date-time-api"></a>

Java 8 Date Time API is introduced to deal with date and time. It is found in java.time package.

```java
import java.time.LocalDate;
import java.time.LocalTime;
import java.time.LocalDateTime;
import java.time.Month;

public class TestDateTimeAPI {
    public static void main(String[] args) {
        LocalDate date = LocalDate.now();
        System.out.println(date);
        LocalDate date1 = LocalDate.of(2017, Month.JANUARY, 1);
        System.out.println(date1);
        LocalTime time = LocalTime.now();
        System.out.println(time);
        LocalTime time1 = LocalTime.of(12, 20, 25, 40);
        System.out.println(time1);
        LocalDateTime dt = LocalDateTime.now();
        System.out.println(dt);
        LocalDateTime dt1 = LocalDateTime.of(2017, Month.JANUARY, 1, 10, 10, 30);
        System.out.println(dt1);
    }
}
```

---

##### Java 8 Optional Class <a name="java-8-optional-class"></a>

Optional class is a public final class and used to deal with NullPointerException in Java application. It is a container object which may or may not contain a non-null value. If a value is present, isPresent() will return true and get() will return the value.

```java
import java.util.Optional;

public class TestOptionalClass {
    public static void main(String[] args) {
        String[] str = new String[10];
        Optional<String> checkNull = Optional.ofNullable(str[5]);
        if (checkNull.isPresent()) {
            String lowercaseString = str[5].toLowerCase();
            System.out.print(lowercaseString);
        } else
            System.out.println("string value is not present");
    }
}
```

---

##### Java 8 Default and Static Methods in Interfaces <a name="java-8-default-and-static-methods-in-interfaces"></a>

Java 8 allows us to add non-abstract methods with implementation in interfaces. These methods are known as default methods. We can also declare and define static methods in interfaces.

```java

interface Vehicle {
    default void print() {
        System.out.println("I am a vehicle!");
    }

    static void blowHorn() {
        System.out.println("Blowing horn!!!");
    }
}

interface FourWheeler {
    default void print() {
        System.out.println("I am a four wheeler!");
    }
}

public class TestInterface1 implements Vehicle, FourWheeler {
    public void print() {
        Vehicle.super.print();
        FourWheeler.super.print();
        Vehicle.blowHorn();
        System.out.println("I am a car!");
    }

    public static void main(String args[]) {
        TestInterface1 obj = new TestInterface1();
        obj.print();
    }
}
```

---

##### Creating files in Java <a name="creating-files-in-java"></a>

Java provides a File class to create, delete, rename and write to files. We can also get the properties of a file using this class.

```java
import java.io.File;
import java.io.IOException;

public class TestFile {
    public static void main(String[] args) {
        try {
            File file = new File("test.txt");
            if (file.createNewFile()) {
                System.out.println("New File is created!");
            } else {
                System.out.println("File already exists.");
            }
        } catch (IOException e) {
            e.printStackTrace();
        }
    }
}
```

---

##### Reading files in Java <a name="reading-files-in-java"></a>

Java provides a File class to create, delete, rename and write to files. We can also get the properties of a file using this class.

```java
import java.io.File;
import java.io.IOException;
import java.util.Scanner;

public class TestFile {
    public static void main(String[] args) {
        try {
            File file = new File("test.txt");
            Scanner sc = new Scanner(file);
            while (sc.hasNextLine())
                System.out.println(sc.nextLine());
            sc.close();
        } catch (IOException e) {
            e.printStackTrace();
        }
    }
}
```

---

##### Writing files in Java <a name="writing-files-in-java"></a>

Java provides a File class to create, delete, rename and write to files. We can also get the properties of a file using this class.

```java
import java.io.File;
import java.io.FileWriter;
import java.io.IOException;

public class TestFile {
    public static void main(String[] args) {
        try {
            File file = new File("test.txt");
            FileWriter writer = new FileWriter(file);
            writer.write("Hello World");
            writer.close();
        } catch (IOException e) {
            e.printStackTrace();
        }
    }
}
```

---

##### Java 8 Concurrency API <a name="java-8-concurrency-api"></a>

Java 8 Concurrency API is introduced to deal with concurrency in Java. It provides a simpler and easier way to deal with concurrency. It provides the following features:

- Improved performance
- Better scalability
- Better maintainability
- Better testability
- Better readability
- Better support for functional programming
- Better support for parallelism
- Better support for reactive programming
- Better support for asynchronous programming
- Better support for non-blocking programming

```java
import java.util.concurrent.ExecutorService;
import java.util.concurrent.Executors;

public class TestConcurrencyAPI {
    public static void main(String[] args) {
        ExecutorService executor = Executors.newSingleThreadExecutor();
        executor.submit(() -> {
            String threadName = Thread.currentThread().getName();
            System.out.println("Hello " + threadName);
        });
    }
}
```

---

---

##### Package <a name="package"></a>

A package in Java is used to group related classes. Think of it as a folder in a file directory. We use packages to avoid name conflicts, and to write a better maintainable code. In order to define a package, we use the package keyword at the top of the source file. Package name should be written in all lowercase letters. If we do not specify any package, the classes are placed in the default package. The package statement must be the first statement in the source file. There can be only one package statement in a file, and package declaration should be present in all the source files of the package.

```java

package com.javatpoint;

public class TestPackage {
    public static void main(String[] args) {
        System.out.println("Hello Package");
    }
}
```

---

##### Exercise

Odd even exercise

```java
import java.util.Scanner;

public class OddEven {
   public static void main(String[] args) {
       Scanner sc = new Scanner(System.in);
       System.out.println("Enter a number: ");
       int num = sc.nextInt();
       if (num % 2 == 0)
           System.out.println("Even");
       else
           System.out.println("Odd");
   }
}
```

Example 2: Odd even exercise

```java
public class Main {

    public static void main(String[] args) {
        int n = 10;

        // get old number{
        if (n % 2 == 0)
            System.out.println("Even number");
         else
            System.out.println("odd number");
    }
}

```

---

##### Exercise

Leap year exercise

```java
import java.util.Scanner;

public class LeapYear {
   public static void main(String[] args) {
       Scanner sc = new Scanner(System.in);
       System.out.println("Enter a year: ");
       int year = sc.nextInt();
       if (year % 4 == 0)
           System.out.println("Leap year");
       else
           System.out.println("Not a leap year");
   }
}
```

---

##### Exercise

Factorial exercise

```java
import java.util.Scanner;

public class Factorial {
   public static void main(String[] args) {
       Scanner sc = new Scanner(System.in);
       System.out.println("Enter a number: ");
       int num = sc.nextInt();
       int fact = 1;
       for (int i = 1; i <= num; i++) {
           fact = fact * i;
       }
       System.out.println("Factorial of " + num + " is: " + fact);
   }
}
```

---

##### Exercise

Fibonacci series exercise

```java
import java.util.Scanner;

public class Fibonacci {
   public static void main(String[] args) {
       Scanner sc = new Scanner(System.in);
       System.out.println("Enter a number: ");
       int num = sc.nextInt();
       int t1 = 0, t2 = 1;
       System.out.print("First " + num + " terms: ");

       for (int i = 1; i <= num; ++i) {
           System.out.print(t1 + " + ");

           int sum = t1 + t2;
           t1 = t2;
           t2 = sum;
       }
   }
}
```

---

##### Exercise

Prime number exercise

```java
import java.util.Scanner;

public class PrimeNumber {
   public static void main(String[] args) {
       Scanner sc = new Scanner(System.in);
       System.out.println("Enter a number: ");
       int num = sc.nextInt();
       int i, m = 0, flag = 0;
       m = num / 2;
       if (num == 0 || num == 1) {
           System.out.println(num + " is not prime number");
       } else {
           for (i = 2; i <= m; i++) {
               if (num % i == 0) {
                   System.out.println(num + " is not prime number");
                   flag = 1;
                   break;
               }
           }
           if (flag == 0) {
               System.out.println(num + " is prime number");
           }
       }
   }
}
```

---

##### Exercise

Palindrome number exercise

```java
import java.util.Scanner;

public class PalindromeNumber {
   public static void main(String[] args) {
       Scanner sc = new Scanner(System.in);
       System.out.println("Enter a number: ");
       int num = sc.nextInt();
       int r, sum = 0, temp;
       temp = num;
       while (num > 0) {
           r = num % 10;
           sum = (sum * 10) + r;
           num = num / 10;
       }
       if (temp == sum)
           System.out.println(temp + " is a palindrome number");
       else
           System.out.println(temp + " is not a palindrome number");
   }
}
```

---

##### Exercise

Armstrong number exercise

```java
import java.util.Scanner;

public class ArmstrongNumber {
   public static void main(String[] args) {
       Scanner sc = new Scanner(System.in);
       System.out.println("Enter a number: ");
       int num = sc.nextInt();
       int c = 0, a, temp;
       temp = num;
       while (num > 0) {
           a = num % 10;
           num = num / 10;
           c = c + (a * a * a);
       }
       if (temp == c)
           System.out.println("armstrong number");
       else
           System.out.println("Not armstrong number");
   }
}
```

---

##### Exercise

Reverse number exercise

```java
import java.util.Scanner;

public class ReverseNumber {
   public static void main(String[] args) {
       Scanner sc = new Scanner(System.in);
       System.out.println("Enter a number: ");
       int num = sc.nextInt();
       int r, sum = 0;
       while (num > 0) {
           r = num % 10;
           sum = (sum * 10) + r;
           num = num / 10;
       }
       System.out.println("Reverse of the number: " + sum);
   }
}
```

---

##### Exercise

Sum of digits exercise

```java
import java.util.Scanner;

public class SumOfDigits {
   public static void main(String[] args) {
       Scanner sc = new Scanner(System.in);
       System.out.println("Enter a number: ");
       int num = sc.nextInt();
       int r, sum = 0;
       while (num > 0) {
           r = num % 10;
           sum = sum + r;
           num = num / 10;
       }
       System.out.println("Sum of digits: " + sum);
   }
}
```

---

##### Exercise

Swap two numbers exercise

```java
import java.util.Scanner;

public class SwapTwoNumbers {
   public static void main(String[] args) {
       Scanner sc = new Scanner(System.in);
       System.out.println("Enter first number: ");
       int num1 = sc.nextInt();
       System.out.println("Enter second number: ");
       int num2 = sc.nextInt();
       int temp;
       temp = num1;
       num1 = num2;
       num2 = temp;
       System.out.println("After swapping");
       System.out.println("First number = " + num1);
       System.out.println("Second number = " + num2);
   }
}
```

---

##### Exercise

Decimal to binary exercise

```java
import java.util.Scanner;

public class DecimalToBinary {
   public static void main(String[] args) {
       Scanner sc = new Scanner(System.in);
       System.out.println("Enter a decimal number: ");
       int num = sc.nextInt();
       int binary[] = new int[40];
       int index = 0;
       while (num > 0) {
           binary[index++] = num % 2;
           num = num / 2;
       }
       for (int i = index - 1; i >= 0; i--) {
           System.out.print(binary[i]);
       }
   }
}
```

---

##### Exercise

Binary to decimal exercise

```java
import java.util.Scanner;

public class BinaryToDecimal {
   public static void main(String[] args) {
       Scanner sc = new Scanner(System.in);
       System.out.println("Enter a binary number: ");
       int num = sc.nextInt();
       int decimal = 0, p = 0;
       while (true) {
           if (num == 0) {
               break;
           } else {
               int temp = num % 10;
               decimal += temp * Math.pow(2, p);
               num = num / 10;
               p++;
           }
       }
       System.out.println("Decimal number is: " + decimal);
   }
}
```

---

##### Exercise

Decimal to octal exercise

```java
import java.util.Scanner;

public class DecimalToOctal {
   public static void main(String[] args) {
       Scanner sc = new Scanner(System.in);
       System.out.println("Enter a decimal number: ");
       int num = sc.nextInt();
       int octal[] = new int[100];
       int index = 0;
       while (num > 0) {
           octal[index++] = num % 8;
           num = num / 8;
       }
       for (int i = index - 1; i >= 0; i--) {
           System.out.print(octal[i]);
       }
   }
}
```

---

##### Exercise

Octal to decimal exercise

```java
import java.util.Scanner;

public class OctalToDecimal {
   public static void main(String[] args) {
       Scanner sc = new Scanner(System.in);
       System.out.println("Enter a octal number: ");
       int num = sc.nextInt();
       int decimal = 0, p = 0;
       while (true) {
           if (num == 0) {
               break;
           } else {
               int temp = num % 10;
               decimal += temp * Math.pow(8, p);
               num = num / 10;
               p++;
           }
       }
       System.out.println("Decimal number is: " + decimal);
   }
}
```

---

##### Exercise

Decimal to hexadecimal exercise

```java
import java.util.Scanner;

public class DecimalToHexadecimal {
   public static void main(String[] args) {
       Scanner sc = new Scanner(System.in);
       System.out.println("Enter a decimal number: ");
       int num = sc.nextInt();
       String hex = "";
       while (num > 0) {
           int temp = 0;
           temp = num % 16;
           if (temp < 10) {
               hex = temp + hex;
           } else {
               hex = (char) (temp + 55) + hex;
           }
           num = num / 16;
       }
       System.out.println("Hexadecimal number is: " + hex);
   }
}
```

---
