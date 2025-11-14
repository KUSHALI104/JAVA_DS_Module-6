# Ex4 You are given a Java program that performs matrix addition. If Matrix A has all odd numbers and Matrix B has all even numbers of the same dimension, what will be the nature (even/odd/mixed) of the resulting matrix?
## DATE:14-11-2025
## AIM:
To write a java function to evaluate weather the given Matrix A has all odd numbers and Matrix B has all even numbers of the same dimension and find the nature of resultant matrrix.

## Algorithm
1. Read matrix size
Input the number of rows r and columns c.
2. Input matrix A
Read all r × c elements and store them in matrix A.
3. Input matrix B
Read all r × c elements and store them in matrix B.
4. Add corresponding elements
For each position (i, j), compute A[i][j] + B[i][j].
5. Display the result matrix
Print the sum matrix row by row.

## Program:
```
/*
Program to ind the nature of resultant matrrix.
Developed by: KUSHALI P G
RegisterNumber: 212223230110
import java.util.*;

public class MatrixAddShort {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int r = sc.nextInt(), c = sc.nextInt();
        int[][] A = new int[r][c], B = new int[r][c];

        for (int i = 0; i < r; i++)  
            for (int j = 0; j < c; j++)
                A[i][j] = sc.nextInt();

        for (int i = 0; i < r; i++)  
            for (int j = 0; j < c; j++)
                B[i][j] = sc.nextInt();

       
        for (int i = 0; i < r; i++) {
            for (int j = 0; j < c; j++)
                System.out.print((A[i][j] + B[i][j]) + " ");
            System.out.println();
        }
    }
}
 
*/
```

## Output:


<img width="506" height="697" alt="image" src="https://github.com/user-attachments/assets/8eaf114a-2f05-4f91-8f42-2a5ebe56386b" />



## Result:
Thus, the java program to evaluate weather the given Matrix A has all odd numbers and Matrix B has all even numbers of the same dimension and find the nature of resultant matrrix is implemented successfully.
