# python_native_data_structures_algorithms
A collection of DSA problems in Python based around Tuple, Lists, Dictionaries and Sets.

### Problem 1
#### Find the largest integer in a given list
```
a=[7,11,45,20]

def largest(list):
    max = list[0]
    for i in list:
        if i > max:
            max = i
    return max
    
print(largest(a))
```
Result: 45


### Problem 2
#### Reverse a given string
```
str1 = 'abc'

def reverse(string):
    return string[::-1]
    
print(reverse(str1))
```
Result: cba

### Problem 3
#### Find odd and even integers in a given list
```
l1 = [3, 6, 9, 12, 15, 18, 21]

def odd(list):
    odd_list=[]
    for i in list:
        if i % 2 != 0:
            odd_list.append(i)
    return odd_list
    
def even(list):
    even_list=[]
    for i in list:
        if i % 2 == 0:
            even_list.append(i)
    return even_list
    
print("odd: ",odd(l1))
print("even: ",even(l1))
```
Result: 
odd:  [3, 9, 15, 21]
even:  [6, 12, 18]
