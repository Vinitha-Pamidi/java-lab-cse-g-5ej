# EXPERIMRNT-2
## 2a) Title: Implement class mechanism in java. create a class ,methods and invoke them inside the method.
## source code;
```java
 class Rectangle {
      double length;
      double breadth;
      double area() {
          return length * breadth;
      }

      double perimeter() {
      return 2*(length +breadth);
}
}
class Main {
  public static void main(String args[]) {
    Rectangle rect = new Rectangle();
         rect.length = 10;
         rect.breadth = 5;
    double area = rect.area();
    double perimeter = rect.perimeter();
    System.out.println("Area of the given rectangle =" + area);
    System.out.println("perimeter of the given rectangle =" + perimeter);
 }
}
```
## output:
![output](r1.png)



