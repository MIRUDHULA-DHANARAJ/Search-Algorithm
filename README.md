# Linear Search and Binary search
## Aim:
To write a program to perform linear search and binary search using python programming.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Linear Search:
1.	Start from the leftmost element of array[] and compare k with each element of array[] one by one.
2.	If k matches with an element in array[] , return the index.
3.	If k doesn’t match with any of elements in array[], return -1 or element not found.
## Binary Search:
1.	Set two pointers low and high at the lowest and the highest positions respectively.
2.	Find the middle element mid of the array ie. arr[(low + high)/2]
3.	If x == mid, then return mid.Else, compare the element to be searched with m.
4.	If x > mid, compare x with the middle element of the elements on the right side of mid. This is done by setting low to low = mid + 1.
5.	Else, compare x with the middle element of the elements on the left side of mid. This is done by setting high to high = mid - 1.
6.	Repeat steps 2 to 5 until low meets high
## Program:
i)	#Use a linear search method to match the item in a list.
```
''' 
Program for linear search method to match the item in a list
Developed by: Mirudhula D
RegisterNumber: 21002651
'''
def linearsearch(array, n, k):

    for i in range(0, n):
        if (array [i] == k):
            return i
    return -1

array = eval(input())
k =  eval(input())
n = len(array)
array.sort()
result = linearsearch(array, n, k)
if(result == -1):
    print(array)
    print("Element not found")
else:
    print(array)
    print("Element found at index: ", result)



```
ii)	# Find the element in a list using Binary Search(Iterative Method).
```
'''
Program to find the element in a list using Binary Search(Iterative Method)..
Developed by: Mirudhula D
RegisterNumber: 21002651
'''
def linearsearch(array, n, k):

    for i in range(0, n):
        if (array [i] == k):
            return i
    return -1

array = eval(input())
k =  eval(input())
n = len(array)
array.sort()
result = linearsearch(array, n, k)
if(result == -1):
    print(array)
    print("Element not found")
else:
    print(array)
    print("Element found at index: ", result)





```
iii)	# Find the element in a list using Binary Search (recursive Method).
```
''' 
Program to find the element in a list using Binary Search(Iterative Method)..
Developed by: Mirudhula D
RegisterNumber: 21002651
'''
def linearsearch(array, n, k):

    for i in range(0, n):
        if (array [i] == k):
            return i
    return -1

array = eval(input())
k =  eval(input())
n = len(array)
array.sort()
result = linearsearch(array, n, k)
if(result == -1):
    print(array)
    print("Element not found")
else:
    print(array)
    print("Element found at index: ", result)




```
## Sample Input and Output

![linear1](https://user-images.githubusercontent.com/94828147/153797759-55f11ac6-7507-481e-8274-82549873e565.png)
![linear2](https://user-images.githubusercontent.com/94828147/153797795-ce5593f7-9c14-4682-ab81-64ccd7659cc1.png)
![linear3](https://user-images.githubusercontent.com/94828147/153797805-ebdf8825-01e4-4256-9534-6b2aa80a583a.png)
![linear4](https://user-images.githubusercontent.com/94828147/153797819-55ba87f9-ab1e-4aa4-9312-1f01862528a6.png)
![linear5](https://user-images.githubusercontent.com/94828147/153797841-3d0cd07a-8daa-484d-b95c-ddab4c2b2d3b.png)
![linear6](https://user-images.githubusercontent.com/94828147/153797859-a5dacaef-0e34-463d-9398-b8efe03fc6e9.png)





## Result
Thus the linear search and binary search algorithm is implemented using python programming.
