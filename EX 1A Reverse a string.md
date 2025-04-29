# EX 1A Length of a String
## DATE:11/03/2025
## AIM:
To write a program to create a recursive function to Length of a string.

## Algorithm
1. Define a recursive function string_length(s) that takes a string as input.

2. Check if the string is empty (if s == ""). If yes, return 0.

3. Otherwise, return 1 + string_length(s[1:]) to count one character and continue with the rest.

4. In the main block, get a string from the user.

5. Call the recursive function and display the result.
 

## Program:
```
/*
def length(str):
    if str=="":
        return 0
    else:
        return 1+len(str[1:])
str=input()
print("length of",str,"is",length(str))
Developed by: Jeevitha E
Register Number: 212222230054
*/
```

## Output:

![image](https://github.com/user-attachments/assets/8757f7e4-0ba5-494b-bf5e-6f97a282aaa6)


## Result:
The program successfully calculates the length of the input string using a recursive function. It prints the number of characters present in the string.


