# Ex.No:1(B) CONDITIONAL STATEMENT

## QUESTION:
```
Given a month number (1 to 12), print which quarter of the year it belongs to:
Months 1,2,3 → "First Quarter"
Months 4,5,6 → "Second Quarter"
Months 7,8,9 → "Third Quarter"
Months 10,11,12 → "Fourth Quarter"
If the number is not in 1-12, print "Invalid Month".
Write a java program to get the month from user and and display appropriate output for the given input.
```

## AIM:
To determine and display the quarter of the year based on the month number entered by the user.

## ALGORITHM :
1.	Start the program and read the month number from the user.
2. Check if the month is in the range 1 to 3 and print “First Quarter”.
3. Check if the month is in the range 4 to 6 and print “Second Quarter”.
4. Check if the month is in the range 7 to 9 and print “Third Quarter”.
5. Check if the month is in the range 10 to 12 and print “Fourth Quarter”, otherwise print “Invalid Month”.


## PROGRAM:
 ```
/*
Program to implement a conditional statement using Java
Developed by: Sanjeev Raj T
RegisterNumber:  212222040148
*/
```

## SOURCE CODE:
```
import java.util.*;
class prog{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        int a=sc.nextInt();
        if(a==1|| a==2||a==3) System.out.println("First Quarter");
        else if(a==4 || a==5 ||a==6) System.out.println("Second Quarter");
        else if(a==7||a==8||a==9) System.out.println("Third Quarter");
        else if(a==10||a==11||a==12) System.out.println("Fourth Quarter");
        else System.out.println("Invalid Month");
    }
}
```





## OUTPUT:

<img width="1219" height="265" alt="image" src="https://github.com/user-attachments/assets/bca7d84a-f3be-4a80-bae1-1a7ee2440875" />


## RESULT:
Thus, the program executed successfully and displayed the correct output based on the given input and conditions.


