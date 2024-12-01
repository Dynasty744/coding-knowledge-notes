# Big O Notation is used to analyze the efficiency of an algorithm as its input approaches infinity

> and is used to represent the upper bounds of a function

## Orders of Growth

![complexity](/assets/images/Big-OComplexityChart.png)
(https://www.bigocheatsheet.com/)

- *O*(1) - **Constant**
    - will execute in the same amount of time regards the size of the data
    - random access of an element in an array or inserting at the beginning of linked list

- [*O*(log n)](https://www.youtube.com/watch?v=wjDY5RbILno) - **Logarithmic**
    - when data is being used is decreased roughly by 50% each time through the algorithm (binary search)
        - a logarithm is the power that a number needs to be raised to get some other number
        - in CS, unless otherwise specified, we can always assume the number we want to raise is equal to 2
        - 2^3 = 2 x 2 x 2 = 8
            - Log base 2 of 8 is 3

        ![logn](/assets/images/O(logn).png)
        (YouTube: Kantan Coding)

- *O*(n) - **Linear**
    - time to complete will increase in direct proportion of the amount of data (linear search)
    - looping through elements in an array or searching through a linked list

- [*O*(n log n)](https://www.youtube.com/watch?v=K3NluEdHkao) - **Linearithmic**
    - the algorithm has a linear component (processing each item) along with a logarithmic component (dividing or merging data). This complexity is common in efficient sorting algorithms like mergesort and heapsort.
    - quick sort, merge sort, heap sort

    ![nlogn](/assets/images/O(nlogn).png)
    (YouTube: Kantan Coding)

- [*O*(n^2)](https://www.youtube.com/watch?v=0eCT74f5hGA) - **Quadratic**
    - time to complete will be proportional to the square of the amount of data (bubble sort, or think of a matrix, 2D array)

- [*O*(n^3)](https://www.youtube.com/watch?v=IBddtmZBSEA) - **Cubic**
    - time to complete will be proportional to the cube of the amount of data (3 nested for loops, or 3D array)

- *O*(2^n) - **Exponential**
    - something

- *O*(n!) - **Factorial**
    - something

### Asymptotic Analysis
- Inventory
    - 10,000 ms to read inventory from disk
    - 10 ms to process each transaction
    - n tractions takes (10,000 + 10n)
        - so the second number would be more important if n is large


### Binary Numbers
| binary | integer |
| -----  | ---|
| 0000   | 0  |
| 0001   | 1  |
| 0010   | 2  |
| 0011   | 3  |
| 0100   | 4  |
| 0101   | 5  |
| 0110   | 6  |
| 0111   | 7  |
| 1000   | 8  |
| 1001   | 9  |
| 1010   | 10 |
| 1011   | 11 |
| 1100   | 12 |
| 1101   | 13 |
| 1110   | 14 |
| 1111   | 15 |
| 10000  | 16 |


starting from right, if see 1, flip to 0, keep doing that as long as you see 1, and then the first time you see a 0, make it a 1, then we're done