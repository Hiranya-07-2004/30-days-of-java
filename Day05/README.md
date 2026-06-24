# Day 5: Palindrome Number Checker

## Concepts Covered
- while loop
- Variables
- Conditional statements
- Number manipulation

## Java Program

 public class PalindromeNumber {
    public static void main(String[] args) {

   int number = 121;
   int original = number;
    int reverse = 0;
 while (number > 0) {
            int digit = number % 10;
            reverse = reverse * 10 + digit;
            number = number / 10;
        }

  if (original == reverse) {
            System.out.println(original + " is a Palindrome");
        } else {
            System.out.println(original + " is not a Palindrome");
        }
    }
}
 
## 🎯 Output

121 is a Palindrome
 
## 💡 Fun Fact
A palindrome reads the same forward and backward. Examples: 121, 1331, 12321.

---
🚀 Day 5 completed successfully!
