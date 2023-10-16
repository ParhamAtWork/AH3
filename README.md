## Solution
```java
import java.util.Scanner;

public class FizzBuzz {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int n = scanner.nextInt();
        int count3 = 1;
        int count5 = 1;
        for (int i = 1; i <= n; i++) {
            if (count3 == 3 && count5 == 5) {
                System.out.println("FizzBuzz");
                count3 = 0;
                count5 = 0;
            } else if (count3 == 3) {
                System.out.println("Fizz");
                count3 = 0;
            } else if (count5 == 5) {
                System.out.println("Buzz");
                count5 = 0;
            } else {
                System.out.println(i);
            }
            count3++;
            count5++;
            scanner.close();
        }
    }
}
```

# AH3

## 1. FizzBuzz
Problem statement:

Write a Java program that prints numbers from 1 to n. For multiples of 3, print "Fizz" instead of the number.
For multiples of 5, print "Buzz" instead of the number. For numbers which are multiples of both 3 and 5,
print "FizzBuzz".
 
### Instructions
- Write a function fizzBuzz that takes an integer n as a parameter and prints the numbers from 1 to n based
on the conditions below:

	1. If the number is a multiple of 3, print "Fizz" instead of the number.

	2. If the number is a multiple of 5, print "Buzz" instead of the number.

	3. If the number is a multiple of both 3 and 5, print "FizzBuzz" instead of the number.

Implement the function in a way that it follows the given specifications.


Example
Input: n = 15

Output:
1
2
Fizz
4
Buzz
Fizz
7
8
Fizz
Buzz
11
Fizz
13
14
FizzBuzz

### Submission:
Push your work to your OWN repo.


## 2. Recursive FizzBuzz
Algo Hour Bonus Challenge 
💪🎬🌊💻🧭🧠👐

Achieve the same functionality of FizzBuzz but using a recursive implementation instead of classical iteration.

Output: same as in Problem statement 1.

## Submission:
Push your work to your OWN repo.
