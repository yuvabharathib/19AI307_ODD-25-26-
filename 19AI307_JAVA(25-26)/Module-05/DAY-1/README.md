# Ex.No:5(A) INPUTSTREAMREADER 

## QUESTION:
Write a program to read user input from the keyboard using InputStreamReader 

## AIM:
To write a Java program that reads input from the keyboard using InputStreamReader and displays the output.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Create an InputStreamReader object with System.in as input.
4.	Wrap it inside a BufferedReader to read text efficiently.
5.	Read a string entered by the user.
6.	Display the output using System.out.println().
7.	End the program.





## PROGRAM:
 ```
/*
Program to implement a InputStreamReader using Java
Developed by: SRINIDHI SENTHIL
RegisterNumber: 212222230148 
*/
```

## SOURCE CODE:
```

import java.io.*;

public class Q2_InputStreamReader {
    public static void main(String[] args) throws IOException {
        InputStreamReader reader = new InputStreamReader(System.in);
        BufferedReader br = new BufferedReader(reader);
        
        System.out.print("Enter your name: ");
        String name = br.readLine();
        
        System.out.println("Hello, " + name + "!");
    }
}
```




## OUTPUT:

<img width="487" height="280" alt="image" src="https://github.com/user-attachments/assets/5a0bece5-cbe0-46f0-9ce5-2918ebdd8b82" />


## RESULT:
The program has been executed successfully and the desired output has been obtained.


