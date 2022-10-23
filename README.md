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
