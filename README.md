# EX-16-LEFT-SHIFT-OPERATION
## AIM
To write a C Program to perform the basic left shift operation for 44 integer number with 3 shifts.

## ALGORITHM
1.	Start the program.
2.	Assign values of a and b as 44 and 3.
3.	Use left shift operator (<<) and shift the value of a three times.
4.	Display the result.
5.	Stop the program.

## PROGRAM
      #include <stdio.h>
      int main() {
         int a=44;
         printf("After Left Shift Operation value of %d is: %d",a,a<<3);
    }
## OUTPUT

![image](https://github.com/user-attachments/assets/fd9a43b3-b8de-4f88-829f-49a0affc05c2)








## RESULT
Thus the program to perform the basic left shift operation for 44 integer number with 3 shifts has been executed successfully.




 


# EX-17-TWO-NUMBERS-ARE-EQUAL-OR-NOT


## AIM

Write a C Program to check whether the two numbers are equal or not using simple if statement.

## ALGORITHM

1.	Start the program.
2.	Read two numbers.
3.	If first number is equal to second number, display both are equal.
4.	Otherwise display both are not equal.
5.	Stop the program.

## PROGRAM
     #include <stdio.h>
     int main() {
        int a,b;
        printf("Enter the first number : ");
        scanf("%d",&a);
        printf("Enter the first number : ");
        scanf("%d",&b);
        if(a==b) {
            printf("The two numbers are equal");
     }  else{
            printf("The two numbers are not equal");
       } 
    }

## OUTPUT
![image](https://github.com/user-attachments/assets/932ec62c-705d-44b7-b5a2-da63b7f52e9e)
         
## RESULT

Thus the program to check whether the two numbers are equal or not using simple if statement has been executed successfully
 
 


# EX-18-STRING-LOWERCASE-CONVERSION
## AIM
Write a C Program to convert the given string into lowercase.

## ALGORITHM
1.	Start the program.
2.	Read a string variable.
3.	Using tolower( ) function convert the given string into its lowercase.
4.	Display the result.
5.	Stop the program.

## PROGRAM
      #include <stdio.h>
      #include <ctype.h>
      int main() {
         char a[100];
         printf("Enter the string : ");
         scanf("%[^\n]",a);
         int i=0;
         while(a[i]) {
             a[i]=tolower(a[i]);
             i++;
        }
        printf("Lower case String is: %s",a);
    }

## OUTPUT

![image](https://github.com/user-attachments/assets/7fb25fc4-c6fa-4305-ad8f-5226d79bdbab)




## RESULT
Thus the program to convert the given string into lowercase has been executed successfully
 
 


# EX-19-COUNT-OF-WORDS-IN-A-STRING
## AIM
Write a C Program to count the total number of words in a given string using do While loop.

## ALGORITHM
1.	Start the program.
2.	Read a string variable.
3.	Using for loop, inspect the string character by character.
4.	Whenever a space is encountered increment count by 1.
5.	Display the result.
6.	Stop the program.

## PROGRAM
      #include <stdio.h>
      int main() {
    char str[1000];
    int i = 0, Count = 0;
    printf("Enter a string: ");
    fgets(str, sizeof(str), stdin);
    if (str[0] != '\n') {
        do {
            if ((str[i] != ' ' && str[i] != '\n') &&
                (str[i + 1] == ' ' || str[i + 1] == '\n' || str[i + 1] == '\0')) {
                Count++;
            }
            i++;
         } while (str[i] != '\0');
       }
        printf("Total number of words: %d\n",Count);
        return 0;
     }
## OUTPUT

![image](https://github.com/user-attachments/assets/1b5ab3d8-cdce-4bdb-8cf5-d08e79f7d6fe)




## RESULT
Thus the program to count the total number of words in a given string using do While loop has been executed successfully
 
 


# EX  -20 -COMPARING TWO STRINGS
## AIM
write a Program to compare two strings without using strcmp().
## ALGORITHM
Step 1: Start the program.
Step 2: Declare two character arrays c1 and c2 of size 100 to store the strings. Also, declare an integer variable
             flag and initialize it to 0, and i for indexing.      
Step 3: Read the first string c1 using scanf("%[^\n]", c1); — this reads input until a newline is encountered 
            (i.e., can include spaces).
Step 4: Read the second string c2 using scanf("%s", c2); — this reads input until a space or newline (i.e., no 
            spaces in the second string).
Step 5: Start comparing characters of both strings from index i = 0.
Step 6: Repeat the following while neither c1[i] nor c2[i] is '\0' (i.e., end of string):
•	If c1[i] is not equal to c2[i], set flag = 1.
•	Increment i by 1.
Step 7: After the loop, check the value of flag:
•	If flag == 0, print "strings are same".
•	Otherwise, print "strings are not same".
Step 8: End the program.

## PROGRAM


## OUTPUT
 

## RESULT
Thus the C Program to compare two strings without using strcmp() has been executed successfully.

