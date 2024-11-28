# Algorithmic complexity / Big-O / Asymptotic analysis

## Big O Notation is used to analyze the efficiency of an algorithm as its input approaches infinity

### Orders of Growth
- *O*(1) - **Constant**
    - will execute in the same amount of time regards the size of the data

- [*O*(log n)](https://www.youtube.com/watch?v=wjDY5RbILno) - **Logarithmic**
    - when data is being used is decreased roughly by 50% each time through the algorithm (binary search or recursive functions)
        - a logarithm is the power that a number needs to be raised to get some other number
        - in CS, unless otherwise specified, we can always assume the number we want to raise is equal to 2
        - 2^3 = 2 x 2 x 2 = 8
            - Log base 2 of 8 is 3

        ![logn](/assets/images/O(logn).png)

- *O*(n) - **Linear**
    - time to complete will increase in direct proportion of the amount of data (linear search)

- [*O*(n log n)](https://www.youtube.com/watch?v=K3NluEdHkao) - **Linearithmic**
    - something

    ![logn](/assets/images/O(nlogn).png)

- [*O*(n^2)](https://www.youtube.com/watch?v=0eCT74f5hGA) - **Quadratic**
    - time to complete will be proportional to the square of the amount of data (bubble sort, or think of a matrix, 2D array)

- [*O*(n^3)](https://www.youtube.com/watch?v=IBddtmZBSEA) - **Cubic**
    - time to complete will be proportional to the cube of the amount of data (3 nested for loops, or 3D array)

- *O*(2^n) - **Exponential**
    - something

- *O*(n!) - **Factorial**
    - something