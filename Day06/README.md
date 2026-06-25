# Day 6: Prime Number Checker

## Concepts Covered
- for loop
- if statement
- Boolean variables
- Number theory basics

## Java Program

public class PrimeNumber {
    public static void main(String[] args) {

        int number = 29;
        boolean isPrime = true;

        if (number <= 1) {
            isPrime = false;
        } else {
            for (int i = 2; i <= number / 2; i++) {
                if (number % i == 0) {
                    isPrime = false;
                    break;
                }
            }
        }

        if (isPrime) {
            System.out.println(number + " is a Prime Number");
        } else {
            System.out.println(number + " is not a Prime Number");
        }
    }
}
}

## 🎯 Output

```
29 is a Prime Number
```

## 💡 Fun Fact
A prime number has exactly two factors: 1 and itself. Examples: 2, 3, 5, 7, 11, 13.

---
🚀 Day 6 completed successfully!
