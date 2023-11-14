# Data Structure Project 01

### Objectives

In this project, our main focus will be on understanding the fundamentals of algorithms.

### Concepts

The project solution heavily relies on these concepts as they form the core foundation. If any of these concepts are unfamiliar to you, we recommend referring to the provided resources for better understanding

| Concept | Resources |
| --- | ----------- |
| What Is An Algorithm | [click here](https://github.com/lamabeta/Introduction-to-algorithms/blob/main/what-is-an-algorithm.md) |



### Problem
Provided to you a code snippet, optimize its algorithm by reducing unnecessary iterations or implementing a more efficient approach.


### Implementation
The current code is responsible of printing all even numbers from 1 to 100. You are requested to enhance the algorithm of the given code to improve its efficiency and optimize its performance ([add your code here](https://github.com/lamabeta/Introduction-to-algorithms/blob/main/PrintEvenNumbers.java))
 ```java
public class PrintEvenNumbers {
    public static void main(String[] args) {
        int number = 1;
        while (number <= 100) {
            if (number % 2 == 0) {
                System.out.println(number);
            }
            number++;
        }
    }
}
```
