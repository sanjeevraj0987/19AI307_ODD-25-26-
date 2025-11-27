# Ex.No:1(A) INTRODUCTION TO JAVA PROGRAMMING, DATA TYPES, VARIABLES AND OPERATORS

## QUESTION:
```
Lovely reaches the Gate of Reason in an ancient temple. A mystical voice says:
"Only those who solve the number puzzle and meet all logical conditions may pass."
To open the gate, Lovely must enter two numbers, and then the system checks:
Conditions to pass the gate:
The sum of the numbers must be greater than 50
(a + b > 50)
The difference between the numbers must be less than 30
(Math.abs(a - b) < 30)
The product must be even
((a * b) % 2 == 0)
She must not enter the same number twice
(a != b)
Only if all 4 conditions are satisfied, the gate opens.
Input Format:
Two integers:
<int a>
<int b>
Output Format:
Gate Opens: true/false
```
## AIM:
To check whether all logical conditions based on two numbers are satisfied and determine if the gate opens.

## ALGORITHM :
1. Start the program and input two integers from the user.
2. Check if the sum of the numbers is greater than 50.
3. Check if the absolute difference is less than 30.
4. Check if the product of the numbers is even.
5. Check if both numbers are not the same and print whether the gate opens.



## PROGRAM:
 ```
/*
Program to implement variables and Operators using Java
Developed by: Akshaya lakshmi V S
RegisterNumber:  212222040005
*/
```

## Sourcecode.java:
```
import java.util.*;
class prog{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        int a=sc.nextInt();
        int b=sc.nextInt();
        boolean cond1=(a+b>50);
        boolean cond2=(Math.abs(a-b)<30);
        boolean cond3=((a*b)%2==0);
        boolean cond4=(a!=b);
        boolean gate=cond1&&cond2&&cond3&&cond4;
        System.out.println("Gate Opens: "+gate);
    }
}
```






## OUTPUT:

<img width="1229" height="270" alt="image" src="https://github.com/user-attachments/assets/2a4feaaf-0cab-438a-879f-2ac6a43f385f" />


## RESULT:
Thus, the program executed successfully and displayed the correct output based on the given input and conditions.

