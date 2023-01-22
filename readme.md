#### Java
#### How to install Java
    - Install Java on Windows
        - Download Java from Oracle website (https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
        - Install Java on Windows 10 (https://www3.ntu.edu.sg/home/ehchua/programming/howto/JDK_Howto.html)
    - Install Java on Linux
        - Install Java on Ubuntu
        - Install Java on CentOS
        - Install Java on Fedora
        - Install Java on Debian
        - Install Java on RHEL
        - Install Java on SUSE
    - Install Java on Mac (https://www3.ntu.edu.sg/home/ehchua/programming/howto/JDK_Howto.html)
        - Install Java on Mac OS X 10.9 (Mavericks)

---

#### Check if Java is installed
    - Check Java version
        - Check Java version on Windows
            - java -version
        - Check Java version on Linux
            - java -version
    - Check Java path
        - echo %JAVA_HOME%

---

#### How to set Java path
    - Set Java path on Windows
        - setx JAVA_HOME "C:\Program Files\Java\jdk1.8.0_131"
    - Set Java path on Linux
        - export JAVA_HOME=/usr/lib/jvm/java-8-oracle
    - Set Java path on Mac
        - export JAVA_HOME=/Library/Java/JavaVirtualMachines/jdk1.8.0_131.jdk/Contents/Home

---

#### Write a Java program
```java
    // Test.java
    public class Test {  // class name must be same as file name
        public static void main(String[] args) {
            System.out.println("Hello World");
        }
    }
```

---

#### How to compile Java program
        - javac Test.java
#### How to run Java program
        - java Test

---



#### Variables
  - Primitive data types (int, float, double, char, boolean, byte, short, long)
    > int a = 10;
    > float b = 10.5f;
    > double c = 10.5;
    > char d = 'a';
    > boolean e = true;
    > byte f = 10;
    > short g = 10;
    > long h = 10;
    
- Reference data types (String, Array, Class, Interface)
```java
    // examples of reference data types
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

#### Operators
##### Arithmetic operators ( +, -, *, /, %, ++, -- )
```java
    int a = 10;
    int b = 20;
    int c = a + b;
    int d = a - b;
    int e = a * b;
    int f = a / b;
    int g = a % b;
    int h = a++;
    int i = a--;
    int j = ++a;
    int k = --a;
```

---

##### Unary operators ( +, -, ++, --, !, ~ )
```java
 int a = 10;
 int b = -a;
 int c = +a;
 int d = a++;
 int e = a--;
 boolean f = !a;
 int g = ~a;
```

---

##### Relational operators ( ==, !=, >, <, >=, <= )
```java
    int a = 10;
    int b = 20;
    boolean c = a == b;
    boolean d = a != b;
    boolean e = a > b;
    boolean f = a < b;
    boolean g = a >= b;
    boolean h = a <= b;
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
    int c = a & b;
    int d = a | b;
    int e = a ^ b;
    int f = ~a;
    int g = a << b;
    int h = a >> b;
    int i = a >>> b;
```

---

##### Assignment operators ( =, +=, -=, *=, /=, %=, &=, |=, ^=, >>=, <<=, >>>= )
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
```

---

#####s Misc operators ( instanceof, -> )
```java
    int a = 10;
    boolean b = a instanceof Integer;
```

---


##### Data Types
- Primitive data types (int, float, double, char, boolean, byte, short, long)
```java
        int a = 10;
        float b = 10.5f;
        double c = 10.5;
        char d = 'a';
        boolean e = true;
        byte f = 10;
        short g = 10;
        long h = 10;
```

- Reference data types (String, Array, Class, Interface)
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

##### Loops
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

##### Conditional Statements
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

##### Keywords

- Access Modifiers (public, private, protected, default)
> The reason for access modifiers is security. It helps us or users no to access variables that you are not suppose to access. For example, if you have a variable that is private, you can only access it within the class. If you have a variable that is public, you can access it anywhere in your program.

Types of access modifier (Privilege or permission level)
1) Public
2) Private
3) No modifier (default)
4) Protected

Access modifier | Class | Package | Subclass | World
--- | --- | --- | --- | ---
public | Y | Y | Y | Y
protected | Y | Y | Y | N
no modifier | Y | Y | N | N
private | Y | N | N | N

---

- Arrays
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

##### Ways of creating an array
1) Declaring an array
```java
        int[] a = new int[5];
```
2) Initializing an array
```java
        int[] a = {1, 2, 3, 4, 5};
```
3) Declaring and initializing an array
```java
        int[] a = new int[]{1, 2, 3, 4, 5};
```

---

#### Arrays.toString() 
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

##### Array Methods
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

##### Methods
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

##### Constructors
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


##### Class
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

##### Object
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

##### Inheritance
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

##### Method
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


##### Wrapper Class
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


##### Inheritance
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


##### Polymorphism
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

##### Abstraction
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


##### Encapsulation
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

##### Interface
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


##### Exception
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


##### Collection
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



##### Generics
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

##### Iterator
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

##### Enumeration
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

##### Comparable
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

##### Comparator
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



##### Multithreading
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

##### Thread class
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

##### Runnable interface
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

##### Thread states
A thread can be in one of the following states:
1. New
2. Runnable
3. Running
4. Waiting
5. Time Waiting
6. Terminated


---

##### Serialization
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

##### I/O
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

##### String Reader
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

##### String Writer
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

##### Pushback Reader
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

##### Buffered Reader
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

##### Buffered Writer
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

##### Data Stream
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
