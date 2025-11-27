# Ex.No:1(C) LOOPING STATEMENT

## QUESTION:
Display Factors of a Number

## AIM:
To read a number from the user and display all of its factors.

## ALGORITHM :
1.	Start the program and accept an integer input from the user.
2. Initialize a loop from 1 to the given number.
3. Check each number if it divides the given number exactly.
4. If divisible, print that number as a factor.
5. Continue the process until all factors are displayed.





## PROGRAM:
 ```
/*
Program to implement a Looping Statement using Java
Developed by: Akshaya Lakshmi V S
RegisterNumber:  212222040005
*/
```

## SOURCE CODE:

```
import java.util.*;
class prog{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();
        System.out.print("Factors: ");
        for(int i=1;i<=n;i++){
            
            if(n%i==0){
                System.out.print(i+" ");
            }
        }
    }
}
```





## OUTPUT:

<img width="1280" height="349" alt="image" src="https://github.com/user-attachments/assets/80c86531-18df-4c36-a662-2cb014bfd3af" />


## RESULT:

Thus, the program executed successfully and displayed the correct output based on the given input and conditions.

