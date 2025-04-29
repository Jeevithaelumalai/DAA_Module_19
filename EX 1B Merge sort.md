# EX 1B Merge Sort
## DATE:11/03/2025
## AIM:
To write a python program to sort the first half of the list using merge sort.

## Algorithm
1. Define a function mergeSort(arr) that recursively divides the array and merges the sorted halves.

2.Implement the merge step to combine two sorted halves into one.

3.In the main program, get the list of elements from the user.

4.Apply merge sort only on the first half of the list.

5.Combine the sorted first half with the unchanged second half and display the result.
   

## Program:
```
/*
def Merge_Sort(s):
    while len(s)<2:
        return s
    mid = int(len(s)/2)
    y = Merge_Sort(s[:mid])
    z = Merge_Sort(s[mid:])
    i=0
    j=0
    result = []
    while i<len(y) and j<len(z):
        if y[i]<z[j]:
            result.append(y[i])
            i = i+1
        else:
            result.append(z[j])
            j = j + 1
    result+=y[i:]
    result+=z[j:]
    return result
S = []
num = int(input())
for i in range(num):
    S.append(float(input()))
print("The Original array is: ",S)
print("Array after sorting is: ",Merge_Sort(S))
Developed by: Jeevitha E
Register Number:  212222230054
*/
```

## Output:

![image](https://github.com/user-attachments/assets/ff9815cd-2870-4135-b4ee-dbc1a6d154f1)


## Result:
The program successfully sorts the first half of the given array using merge sort. where only the first half is sorted, and the second half remains unchanged.
