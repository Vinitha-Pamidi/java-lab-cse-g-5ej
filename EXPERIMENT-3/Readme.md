# EXPERIMENT-3:
## 3a) Title:Implement Constructor overloading in java.
## source code:
```java
class Student {
    String name;
    int age;
    double marks;

    Student() {
    }

    Student(String name, int age, double marks) {
        this.name = name;
        this.age = age;
        this.marks = marks;
    }

    void display() {
        System.out.println("Name: " + name);
        System.out.println("Age: " + age);
        System.out.println("Marks: " + marks);
    }
}

class Main {
    public static void main(String[] args) {
        Student std = new Student();
        std.display();
        Student std1 = new Student("Vinitha", 18, 96.8);
        std1.display();
    }
}
```
# output:
![output](3a.png)

