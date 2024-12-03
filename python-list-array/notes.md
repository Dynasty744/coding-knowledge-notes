# What's the difference between Python lists and arrays?

## Python lists behind the scenes are actually implemented as arrays, arrays of pointers, or as arrays of pointers to Py objects

## In Python, arrays are rarely used, lists would be the norm

### arrays
- an ordered sequence of homgeneous elements
- all items are of the same type
- the size of the array is set when we create the array
- basically, this is just a wrapper for c arrays
- example:
    - import array
    - numbers = array.array('i', [1, 2, 3, 4, 5])
    - print(numbers)
    - array('i', [1, 2, 3, 4, 5])
- example:
    - import array
    - numbers = array.array('i', [1, 2, 3, 4, 5])
    - numbers.append(6)
    - print(numbers)
    - array('i', [1, 2, 3, 4, 5, 6])
- example:
    - import array
    - numbers = array.array('i', [1, 2, 3, 4, 5])
    - numbers.append("apple")
    - TypeError: an integer is required

### lists
- An ordered sequence of heterogeneous elements