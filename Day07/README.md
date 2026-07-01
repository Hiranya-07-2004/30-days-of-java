# 🌀 Day 7: Fibonacci Series Generator

## 📚 Concepts Covered
- for loop
- Variables
- Sequence generation

## 📝 Java Program

public class FibonacciSeries {
    public static void main(String[] args) {

  int n = 10;
  int first = 0;
  int second = 1;

  ystem.out.println("Fibonacci Series:");

 for (int i = 1; i <= n; i++) {
  System.out.print(first + " ");

  int next = first + second;
  first = second;
   second = next;
        }
    }
}

## Output


Fibonacci Series:
0 1 1 2 3 5 8 13 21 34

 The Fibonacci sequence appears in nature, including flower petals, pinecones, seashells, and even galaxy formations. It is also used in dynamic programming and algorithm design.

##  Learning Outcome
By completing this program, you learned how to:
- Use loops to generate a sequence
- Update multiple variables efficiently
- Understand one of the most frequently asked coding interview problems

🚀 Day 7 completed successfully!
