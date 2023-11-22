# Introduction to Algorithms Project
### Objective

In this project, our main focus will be on understanding the fundamentals of algorithms, and their relationship with data structure.

### Concepts

The project solution heavily relies on these concepts as they form the core foundation. If any of these concepts are unfamiliar to you, we recommend referring to the provided resources for better understanding

| Concept | Resources |
| --- | ----------- |
| What Is An Algorithm | [What Is An Algorithm Concept](https://github.com/lamabeta/Introduction-to-algorithms/blob/main/resources/01-what-is-an-algorithm.md) |
| The Relationship Between Data Structures and Algorithms | [Relationship Between Data Structures and Algorithms Concept](https://github.com/lamabeta/Introduction-to-algorithms/blob/main/resources/02-the-relationship-between-data-structures-and-algorithms.md) |


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
