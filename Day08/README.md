# 📊 Day 8: Find the Largest Element in an Array

## 📚 Concepts Covered
- Arrays
- for loop
- Comparison using if statement

## 📝 Java Program

 public class LargestElement {
    public static void main(String[] args) {

   int[] numbers = {12, 45, 7, 89, 23, 56};

  int largest = numbers[0];

   for (int i = 1; i < numbers.length; i++) {
            if (numbers[i] > largest) {
                largest = numbers[i];
            }
        }

   System.out.println("Largest element is: " + largest);
    }
}
 
## Output


Largest element is: 89

## Fun Fact
Arrays store elements in contiguous memory locations, making them efficient for accessing data using an index.

## Learning Outcome
By completing this program, you learned how to:
- Declare and initialize arrays
- Traverse an array using a loop
- Find the maximum value efficiently

## Time Complexity
- O(n)– We traverse the array only once.

## Real-World Use Case
Finding the highest score in an exam, the maximum temperature in a week, or the highest sales amount in a month.

---
🚀 Day 8 completed successfully!
