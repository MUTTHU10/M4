# EX-16-LEFT AND RIGHT-SHIFT-OPERATION
## AIM
To write a C Program to perform the basic left and right shift operation for 22 integer number.

## ALGORITHM
1.	Start the program.
2.	Assign values of a as 22.
3.	Use left shift operator (<<) and shift the value of two times.
4.	Use right shift operator (>>) and shift the value of two times.
5.	Display the result.
6.	Stop the program.

## PROGRAM
```
#include <stdio.h>
int main()
{
    int num=22,rshift,lshift;
    rshift=num>>2;
    lshift=num<<2;
    printf("After Left Shift Operation value of a is:%d\n",lshift);
    printf("After Right Shift Operation value of a is:%d",rshift);
    
}
```
## OUTPUT



<img width="1030" height="280" alt="Screenshot 2025-10-20 142752" src="https://github.com/user-attachments/assets/3ae2749c-c784-45ed-bd8d-591d1b15f5ee" />






## RESULT
Thus the program to perform the basic left and right shift operation for 22 integer number with 2 shifts has been executed successfully.




 
 


# EX-17-PROFIT_OR_LOSS


## AIM

Write a C program to check whether profit or loss using simple if statement

## ALGORITHM

1.	Start the program.
2.	Read Actual price and selling price.
3.	If selling price is greater than actual price, then display profit.
4.	Otherwise display loss.
5.	Stop the program.

## PROGRAM
```
#include <stdio.h>
int main()
{
    int actpri,selpri;
    scanf("%d %d",&actpri,&selpri);
    if(selpri-actpri>0)
    printf("Profit!!");
    else if(selpri-actpri<0)
    printf("Loss!!");
}
```

## OUTPUT

<img width="671" height="314" alt="Screenshot 2025-10-20 143140" src="https://github.com/user-attachments/assets/5e33ee07-1f9b-4408-ba87-352a4609a84f" />


       
## RESULT

Thus the program to check whether profit or loss using simple if statement has been executed successfully
 
 


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
```
#include <stdio.h>
#include <string.h>
#include <ctype.h>
int main()
{
    char ch[20];
    scanf("%s",ch);
    
    int i=0;
    while (ch[i]!='\0')
    {
        ch[i]=tolower(ch[i]);
        i++;
    }
    printf("Lower case String is:%s",ch);
}
```
## OUTPUT

<img width="876" height="304" alt="Screenshot 2025-10-20 143353" src="https://github.com/user-attachments/assets/eac19dc7-2d2c-45fc-9b01-7a66dde1c44e" />



## RESULT
Thus the program to convert the given string into lowercase has been executed successfully
 
 


# EX-19-COUNT-OF-WORDS-IN-A-STRING
## AIM
Write a C Program to count the total number of words in a given string using While loop.

## ALGORITHM
1.	Start the program.
2.	Read a string variable.
3.	Using for loop, inspect the string character by character.
4.	Whenever a space is encountered increment count by 1.
5.	Display the result.
6.	Stop the program.

## PROGRAM
```
#include <stdio.h>
#include <string.h>
 
int main()
{
  	char str[100];
  	int i, totalwords;
  	totalwords = 1;
  	i = 0;
 
  	scanf("%[^\n]s",str);
  
  	 	   	
  	while(str[i] != '\0')
	{
	    if (str[i]==' ')
		{
		    totalwords+=1;
		}
		i++;
	}	
	printf("%d", totalwords);
	
  	return 0;
}
```
## OUTPUT


<img width="689" height="302" alt="Screenshot 2025-10-20 143626" src="https://github.com/user-attachments/assets/3e3c27ad-b540-411b-9a36-2a0943b2d4b5" />




## RESULT
Thus the program to count the total number of words in a given string using While loop has been executed successfully
 
 


# EX  -20 -COMPARING TWO STRINGS
## AIM
write a Program to compare two strings without using strcmp().
## ALGORITHM
Step 1: Start the program.
Step 2: Declare two character arrays c1 and c2 of size 100 to store the strings.       
Step 3: Read the first string c1 using scanf("%[^\n]", c1); — this reads input until a newline is encountered 
            (i.e., can include spaces).
Step 4: Read the second string c2 using scanf("%s", c2); — this reads input until a space or newline (i.e., no 
            spaces in the second string).
Step 5: Find the length of two strings and assign it to the variable l1,l2.
Step 6: If l1 is less than l2, then print str1 is less than str2.
Step 7: Otherwise, print str2 is less than str1.
Step 8: End the program.

## PROGRAM
```
#include <stdio.h>
#include <string.h>
int main()
{
    char str1[100],str2[100];
    scanf("%s",str1);
    scanf("%s",str2);
    int l1=strlen(str1);
    int l2=strlen(str2);
    if (l1<l2)
    {
        printf("str1 is Less than str2");
    }
    else
    {
        printf("str2 is Less than str1");
    }
}
```

## OUTPUT
 <img width="806" height="359" alt="Screenshot 2025-10-20 144433" src="https://github.com/user-attachments/assets/c307add1-fc74-4ec0-9eed-6683420cf44e" />


## RESULT
Thus the C Program to compare two strings without using strcmp() has been executed successfully.

