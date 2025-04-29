
# EX-01-Datatypes-Operators
## AIM:
Write a C program to initialize the value as 5.800000 & display the same value as 5.800.
## ALGORITHM:
1. Start

2. Declare a float variable.

3. Initialize the variable with 5.800000.

4. Use printf with a format specifier %.3f to display the value with 3 decimal places.

5. End


## PROGRAM:
#include <stdio.h>
int main()
{
    float x=5.800;
    printf("%.3f",x);
    return 0;
}

## OUTPUT:

![image](https://github.com/user-attachments/assets/e0ce47a1-888f-4cb1-b216-70c5179628f4)

## RESULT:
Thus the program to read 3 characters one by one and print the characters in a reverse order has been executed successfully.


# EX-02- Conditional-Statements
## AIM:
Write a C program to read A values and check whether the value is greater than and equal to 50. 


# ALGORITHM:
### ✅ **Simple Algorithm to Compare `x` and `y` Using `if-else`**

1. **Start**  
2. **Declare** two variables: `x` and `y`  
3. **Read** values of `x` and `y` from the user  
4. **Use an if-else statement** to compare:
   - If `x == y`, print `"x == y"`
   - Else, print `"x != y"`  
5. **End**

# PROGRAM:
#include <stdio.h>
int main()
{
    int x,y;
    scanf("%d%d",&x,&y);
    if(x==y){
        printf("X is equal to Y");
    }
    else{
        printf("X is NOT equal to Y");
    }
    return 0;
    
}

# OUTPUT:
![image](https://github.com/user-attachments/assets/9f5d7702-6520-4c92-a681-2777a94f69a4)

# RESULT:
Thus the program to read A values and check whether A is positive number or not has been executed successfully.

# EX-03- Operators-Expressions
## AIM:
Write a C program to check whether the given input (For ex: 9) is an alphabet or not using a conditional operator.

## ALGORITHM:
1. Start  
2. Declare a character variable `ch`  
3. Read a character from the user  
4. Use conditional operator to check:  
   - If `ch` is between 'A'–'Z' or 'a'–'z', print "It is an alphabet"  
   - Else, print "It is not an alphabet"  
5. End
## PROGRAM:
#include <stdio.h>
int main()
{
    char ch;
    scanf("%c",&ch);
    ((ch>='a' && ch<= 'z') || (ch>='A' && ch<= 'Z'))
    ? printf("It is an ALPHABET")
    : printf("It is NOT AN ALPHABET");
return 0;
}
## OUTPUT:
![image](https://github.com/user-attachments/assets/b7e964c5-eb7f-45f5-99ef-3d9761916c4d)

## RESULT:
Thus the program to find minimum between two fraction numbers using conditional operator or ternary operator has been executed successfully.

# EX-04- Using Conditional Statements

## AIM:
Write a C program to read a, b values and check whether  a Not equal to b. 


## ALGORITHM:
1. Start  
2. Declare two integer variables `a` and `b`  
3. Read values of `a` and `b` from the user  
4. Check if `a` is not equal to `b` using `if` condition  
   - If true, print "a is not equal to b"  
   - Else, print "a is equal to b"  
5. End

## PROGRAM:
#include <stdio.h>
int main()
{
  int x,y;
  scanf("%d%d",&x,&y);
  if(x!=y){
      printf("a is not equal to b");
  }
  return 0;   
}

## OUTPUT:
![image](https://github.com/user-attachments/assets/9222276c-2589-4d0b-a2c4-4a99ad3683cd)

## RESULT:
Thus the program to check whether the input value is equal to 1 using simple if statement has been executed successfully



# EX-05- Calculating Total, Percentage, And Division Using Conditional Statements 
## AIM:
Write a C program to read the marks of three subjects and calculate the total, percentage and division using conditional statements?

if percentage >=60 display "First"

if  percentage<60 and >=48 display "Second"

if percentage <48 and >=36 display "Pass"

if percentage <36 display "Fail"

## ALGORITHM:
1.	Start
2.	Declare integer variables m1, m2, m3 for marks, and float variables tot, per.
3.	Input the marks for three subjects.
4.	Calculate total marks: tot = m1 + m2 + m3
5.	Calculate percentage: per = tot / 3
6.	Display total and percentage.
7.	Check if all marks are greater than or equal to 40:
8.	If yes:
a.	If percentage >= 60: Print “Division = First”
b.	Else if percentage >= 48: Print “Division = Second”
c.	Else if percentage >= 36: Print “Division = Pass”
9.	Else: Print “Division = Fail”
10.	End
## PROGRAM:
#include <stdio.h>
int main()  
{
    int s1,s2,s3,total;
    float per;
    scanf("%d%d%d",&s1,&s2,&s3);
        total=s1+s2+s3;
        per=(total/3.0);
    printf("Total Marks = %d\n",total);
    printf("Percentage = %.2f\n",per);
    if(s1<40 || s2<40 || s3<40 || per<36){
        printf("Division = Fail\n");
    }else{
   if (per>=60){
        printf("Division = First\n");
    }else if(per >=48){
        printf("Division = Second\n");
    }else if(per>=36){
        printf("Division = Pass\n");
    }}
    return 0;
}

## OUTPUT:
![image](https://github.com/user-attachments/assets/076c2278-e6c1-4ad0-ab8f-d00dc01d9919)


## RESULT:
The program successfully takes three subject marks, calculates the total and percentage, and correctly determines the division based on predefined grading logic.

