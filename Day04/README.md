#  Day 4: Star Pattern Program

## Concepts Covered
- for loops
- Nested loops
- Pattern printing

## 📝 Java Program

public class StarPattern {
    public static void main(String[] args) {

        int rows = 5;

        for (int i = 1; i <= rows; i++) {

            for (int j = 1; j <= i; j++) {
                System.out.print("* ");
            }

            System.out.println();
        }
    }
}

##  Output

```
*
* *
* * *
* * * *
* * * * *
```

## 💡 Fun Fact
Nested loops are commonly used for pattern printing, matrix operations, and game development.

🚀 Day 4 completed successfully!
