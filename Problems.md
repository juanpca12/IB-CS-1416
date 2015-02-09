# Problems!

## 1. Fibonacci Sequence - Golden Ratio Relationship

The Fibonacci Sequence is the sequence of numbers where

t<sub>n</sub> = t<sub>n-1</sub> + t<sub>n-2</sub> and t<sub>1</sub> =  1, t<sub>2</sub> = 1

1. Write an algorithm which generates the first ```n``` Fibonacci numbers and calculates the ratio between two consecutive terms.
2. Generalize the algorithm by making the initial values (```t1``` and ```t2```) arbitrary (i.e. not hard coded as 1).

#### *Optional:*

1. Implement the algorithm using a Python program.
2. Produce a plot and show that the ratio (```r```) tends to the Golden ratio as ```n``` becomes larger (plot ```n-vs-r```.)

Here is a sample plot:
![n-vs-r plot](https://raw.githubusercontent.com/abhikpal/IB-CS-1416/master/images/prob_0001.png)

More on [The Golden Ratio](http://en.wikipedia.org/wiki/Golden_ratio) and [The Fibonacci Sequence](http://en.wikipedia.org/wiki/Fibonacci_number)

## 2. Modified Mandlebrot

- [ ] rephrase the problem properly and then type this thing up.

## 3. Sorting algorithms

1. Write at least 3 algorithms for sorting a list of numbers (try to come up with these algorithms on your own).
2. Calculate the complexity of each sorting algorithm (using the Big-O notation)
3. Find a better sorting algorithm.

## 4. File I/O

1. Write an algorithm to input a numbers stored inside a text file (```file_1.txt```), make them into a list and sort them. The user should interact with the program in the following manner:
```shell
$> mu_sort file_1.txt
```
2. Write an algorithm (```mu_sort```) to read data stored inside a text file (```file_1.txt```), sort it and output the sorted numbers to another file (```file_2.txt```). The user should interact with the program in the following manner:
```shell
$> mu_sort file_1.txt file_2.txt
```
3. Implement the two algorithms in Python.