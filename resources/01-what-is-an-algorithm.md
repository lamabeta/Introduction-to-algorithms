# What Is An Algorithm ?
The tasks we do in our daily lives, such as waking up or going to work, can be seen as a **series of steps**. Similarly, in the world of computers, when a computer follows **specific steps to perform a task**, we call it an `algorithm`.

## Concept
An algorithm is simply
> a set of instructions for completing a specific task.

Even a process as simple as  **drinking juice** can be considered an algorithm, as it involves **following a defined set of steps to achieve the task** .
Here's a simple algorithm that **outlines the steps** for drinking juice:
1. Pick up the juice glass.
2. Slowly pour the juice from the container into the glass.
3. Stop pouring when the desired amount of juice is in the glass.
4. Close the lid or cap of the juice container tightly to preserve the remaining juice.
5. Take small sips to drink the juice.

What we are doing is, for a given problem (drinking juice), we are providing a step by step procedure for solving it.

When applied to computing, an algorithm refers to 
> the set of instructions given to a computer to achieve a particular task.

## Example
When we write `code`, we are essentially creating algorithms for the computer to **follow** and **execute**.
Here's an algorithm that stores two numbers, adds them, and prints the result using java:
1. Create a variable "firstNumber" and give it a value of **3**.
2. Create a variable "secondNumber" and give it a value of **4**.
3. Add "first_number" and "second_number" together, and store the result in a new variable, let's call it "sum".
4. Print the value of "sum" to display the result.
```java
public class SumCalculation {
    public static void main(String[] args) {
        int firstNumber = 3;
        int secondNumber = 4;
        int sum = firstNumber + secondNumber;
        System.out.println(sum);
    }
}
   ```
There are **two** main criteria for judging the merits of algorithms: 
1. `Correctness` (does the algorithm provide a **solution** to the problem in **a finite number of steps**?)
2. `Efficiency` (how many **resources** -in terms of **memory** and **time**- does it take to **execute** ).
