# Program-2-a
## C-Module 2
## EX_NO-02)a)-Loop
### Date: 10-09-2025
### Name: Sujhan Prasanth S B 
### Register Number:25018059
## AIM:
Write a C Program to print the string "LINUX" n number of times.
## ALGORITHM:
1. Start the program.
2. Declare an integer variable to store the input value.
3. Read the integer value from the user using the scanf function.
4. Use a for loop starting from 1 to the input value:

   a. In each iteration, print "LINUX".

6. End the program.
## PROGRAM:
```
#include <stdio.h>
int main()
{
    int num;
    scanf("%d",&num);
    for(int i=1;i<=num;i++)
    {
        printf("LINUX\n");
    }
return 0;
}
```
## OUTPUT:
<img width="835" height="267" alt="Screenshot 2025-10-19 214719" src="https://github.com/user-attachments/assets/772b86ac-6423-40d0-8886-79dc6eb5ae9d" />


## RESULT:
Thus the program to print the string "LINUX" n number of times has been executed successfully
# Program-2-b
## C-Module 2
## EX_NO-02)b)-Nested Loops
### Date: 10-09-2025
### Name: Sujhan Prasanth S B 
### Register Number:25018059
## AIM:
write a c program to print hollow rectangular pattern
## ALGORITHM:
1. Start the program.
2. Declare two integer variables to store the number of rows and columns.
3. Read the values of rows and columns from the user using the scanf function.
4. Use a for loop from 1 to the number of rows:

     a. Inside this loop, use another for loop from 1 to the number of columns:

        i. If the current row or column is the first or last, print "*".

        ii. Otherwise, print a space " ".

    b. After the inner loop, move to the next line using printf("\n").

6. End the program.

## PROGRAM:
```
#include<stdio.h>
int main()
{
    int row,col;
    scanf("%d\n%d",&row,&col);
    for(int i=1;i<=row;i++){
        for(int j=1;j<=col;j++){
            if(i==1||j==1||i==row||j==col)printf("*");
            else printf(" ");
        }printf("\n");
    }
return 0;
}
```
## OUTPUT:
<img width="842" height="357" alt="Screenshot 2025-10-19 215213" src="https://github.com/user-attachments/assets/55ed2f2b-bb10-4f83-baf8-7441dfab8ac2" />

## RESULT:
Thus the program to print hollow rectangular pattern has been executed successfully
# Program-2-c
## C-Module 2
## EX_NO-02)c)-FUNCTIONS
### Date: 10-09-2025
### Name: Sujhan Prasanth S B 
### Register Number:25018059
## AIM:
Write a C program to perform multiplication and division of two numbers using functions (With argument and without return type).
## ALGORITHM:
1. Start the program.
2. Declare two float variables to store the input numbers.
3. Read the two float numbers from the user using the scanf function.
4. Define a function to perform multiplication:

     a. Take two float arguments.

    b. Multiply the two numbers and store the result.

    c. Print the multiplication result.

6. Define a function to perform division:

    a. Take two float arguments.

    b. Divide the first number by the second and store the result.

    c. Print the division result with six decimal places.

8. In the main function, call the multiplication function with the input numbers.
9. Call the division function with the input numbers.
10. End the program.

## PROGRAM:
```
#include<stdio.h>
void mul(float a,float b){
    float c=a*b;
    printf("Multiplication: %.f",c);
}
void div(float a,float b)
{
    float c=a/b;
    printf("\nDivision: %.6f",c);
}
int main()
{
    float a,b;
    scanf("%f\n%f",&a,&b);
    mul(a,b);
    div(a,b);
}
```
## OUTPUT:
<img width="840" height="287" alt="Screenshot 2025-10-19 215710" src="https://github.com/user-attachments/assets/5da6f4f2-6fbb-4892-88e0-c59ba5f0b261" />

## RESULT:
Thus the program to perform multiplication and division of two numbers using functions (With argument and without return type) has been executed successfully
# Program-2-d
## C-Module 2
## EX_NO-02)d)-LOOPS
### Date: 10-09-2025
### Name: Sujhan Prasanth S B 
### Register Number:25018059
## AIM:
Write a c program to find the sum of Odd digits using while loop in a Given range
## ALGORITHM:
1. Start the program.
2. Declare three integer variables: num1, num2, and sum. Initialize sum to 0.
3. Read two integer values (num1 and num2) from the user using scanf.
4. Assign the value of num1 to a variable n.
5. Use a while loop that runs as long as n is less than or equal to num2:

   a. Check if n is an odd number (n % 2 != 0).
        i. If true, add n to sum.

    b. Increment n by 1.

7. After the loop ends, print the value of sum.
8. End the program.

## PROGRAM:
```
#include<stdio.h>
int main()
{
    int num1,num2,n,sum=0;
    scanf("%d\n%d",&num1,&num2);
    n=num1;
    while(n<=num2){
        if(n%2!=0)
        {
            sum+=n;
        }
        n++;
    }
    printf("%d",sum);
}
```
## OUTPUT:
<img width="840" height="340" alt="Screenshot 2025-10-19 220159" src="https://github.com/user-attachments/assets/b7b33626-30ae-461e-958c-6594b926b0b0" />

## RESULT:
Thus the program to find the sum of Odd digits using while loop in a Given range has been executed successfully
# Program-2-e
## C-Module 2
## EX_NO-02)e)-LOOPS
### Date: 10-09-2025
### Name: Sujhan Prasanth S B 
### Register Number:25018059
## AIM:
Write a C program to print the multiplication table of  a given number using do while loop within the certain limit or range
## ALGORITHM:
1. Start the program.
2. Declare three integer variables: num1, num2, and i. Initialize i to 1.
3. Read two integer values (num1 and num2) from the user using scanf.
4. Use a do-while loop that runs as long as i is less than or equal to num2:

    a. Multiply num1 by i and store the result in a variable mul.

    b. Print the value of mul followed by a space.

    c. Increment i by 1.

6. End the program.

## PROGRAM:
```
#include<stdio.h>
int main()
{
    int num1,num2,i=1;
    scanf("%d\n%d",&num1,&num2);
    do{
        int mul=num1*i;
        printf("%d ",mul);
        i++;
    }while(i<=num2);
}

```
## OUTPUT:
<img width="844" height="338" alt="Screenshot 2025-10-19 220637" src="https://github.com/user-attachments/assets/2268e54a-1cce-4637-b323-20f52bb7961a" />

## RESULT:
Thus the program to print the multiplication table of  a given number using do while loop within the certain limit or range has been executed successfully
