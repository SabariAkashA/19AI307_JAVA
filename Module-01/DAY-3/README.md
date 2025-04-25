# Ex.No:1(C) CONTROL STATEMENTS

## AIM:
To develop a java program to read the value of an integer m and display the value of n is 1 when m is larger than 0, 0 when m is 0 and -1 when m is less than 0..

## ALGORITHM :
1. Start the program and declare variables m and n.

2. Read an integer m from the user using a Scanner.

3. Check the value of m:

   If m > 0, assign n = 1.

   If m == 0, assign n = 0.

   If m < 0, assign n = -1.

4. Display the values of m and n.

5. End the program.

## PROGRAM:
 ```
/*
Program to implement a class & objects using Java
Developed by: SABARI AKASH A
RegisterNumber: 212222230124
*/
```

## Sourcecode.java:
```java
import java.util.Scanner;
public class Main
{
    public static void main(String[] args)
    {
        Scanner scan=new Scanner(System.in);
        int m=scan.nextInt();
        int n=0;
        if(m>0)
        {
            n=1;
        }
        else if(m==0)
        {
            n=0;
        }
        else
        {
            n=-1;
            
        }
        System.out.println("The value of m = "+m);
        System.out.println("The value of n = "+n);
    }
}
```
## OUTPUT:
<img src = https://github.com/user-attachments/assets/d7dcb651-cad2-4de4-a1d1-99c7744bb402 width = 300 height = 200>

## RESULT:
Thus, the Java program to check given number is zero or not was created successfully.

