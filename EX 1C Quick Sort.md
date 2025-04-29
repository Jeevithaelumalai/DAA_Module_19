# EX 1C Quick Sort
## DATE:11/03/2025
## AIM:
To write a python program to implement quick sort using tha last element as pivot on the list of float values.

## Algorithm
1. Define a function partition(arr, low, high) to place the pivot (last element) in its correct position and arrange elements around it.

2.Define the main function quickSort(arr, low, high) that recursively sorts the sublists.

3.In the main block, read float values from the user and store them in a list.

4.Call the quickSort() function with the list.

5.Display the sorted list.
 
   

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
Developed by: 
Register Number: 212222230054 
*/
```

## Output:
![image](https://github.com/user-attachments/assets/335e556d-bf67-45de-9738-a79259881421)



## Result:
The program successfully sorts the input array using the QuickSort algorithm, arranging the elements in ascending order.
