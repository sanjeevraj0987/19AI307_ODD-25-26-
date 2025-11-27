# Ex.No:3(b) POLYMORPHISM

## QUESTION:
Write a Java program that calculates the area of different shapes using method overloading. Create a class AreaCalculator with:
- area(int side) for square
- area(int length, int breadth) for rectangle
- area(double radius) for circle
- For example:
 <img width="406" height="151" alt="image" src="https://github.com/user-attachments/assets/18ee3fbc-c7c8-4e56-a825-ea0a96792a95" />


## AIM:
To write a Java program that demonstrates method overloading by calculating the area of a square, rectangle, and circle using overloaded area() methods.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Read the side of a square, length, breadth, and radius from the user.
4. Create an object of the areacalc class.
5. Call the overloaded area(int) method to compute the area of a square.
6. Call the overloaded area(int,int) method to compute the area of a rectangle.
7. Call the overloaded area(double) method to compute the area of a circle and display all results.

## PROGRAM:
 ```
Program to implement a Polymorphism using Java
Developed by: SANJEEV RAJ T
RegisterNumber:212222040148
```

## SOURCE CODE:
```
import java.util.*;
class areacalc
{
    int area(int side)
    {    
    return side*side;
    }
    int area(int len,int breath)
    {
        return len*breath;
    }
    double area(double radius)
    {
        return Math.PI*radius*radius;
    }
}
public class Main
{
    public static void main(String[] args)
    {
        Scanner input=new Scanner(System.in);
        int side=input.nextInt();
        int len=input.nextInt();
        int breath=input.nextInt();
        double radius=input.nextDouble();
        
        areacalc calc=new areacalc();
        
        System.out.println("Area of square: "+calc.area(side));
        System.out.println("Area of rectangle: "+calc.area(len,breath));
        System.out.println("Area of circle: "+calc.area(radius));
    }
}
```

## OUTPUT:
<img width="909" height="400" alt="image" src="https://github.com/user-attachments/assets/32844eed-6c64-4441-9216-0b1f496137b7" />

## RESULT:
The program successfully demonstrates method overloading by calculating and displaying the areas of a square, rectangle, and circle using three versions of the area() method.


