# Multiplication Table Generator

## Overview
This is a simple Java program that generates the multiplication table for a given number. The user is prompted to enter a number, and the program displays its multiplication table from 1 to 10. It is a beginner-friendly program that demonstrates basic Java concepts such as loops, user input handling, and console output.

---

## Code Explanation

```java
package MultiplicationTable;

import java.util.Scanner;

public class MultiplicationTable
{
    public static void main(String[] args)
    {
        Scanner s = new Scanner(System.in); // Creating a Scanner object to take user input
        System.out.println("Enter the Number"); // Asking the user to enter a number
        int num = s.nextInt(); // Reading the inputted number
        
        for(int i=1; i<=10; i++) // Loop runs from 1 to 10
        {
            System.out.println(num+"❌"+i+"="+num*i); // Printing the multiplication result
        }
    }
}
```

### Step-by-Step Process
1. **Package Declaration**: The code begins with `package MultiplicationTable;`, which is optional and used if you are organizing the code in a package.
2. **Importing Scanner**: The `import java.util.Scanner;` statement is used to enable user input functionality.
3. **Class Definition**: The program is contained within the `MultiplicationTable` class.
4. **Main Method**: Execution starts in the `main()` method.
5. **Creating Scanner Object**: `Scanner s = new Scanner(System.in);` allows the program to take user input from the console.
6. **Prompting User Input**: `System.out.println("Enter the Number");` displays a message asking the user to enter a number.
7. **Reading Input**: `int num = s.nextInt();` stores the entered number.
8. **Loop Execution**: The `for` loop runs from 1 to 10, multiplying the entered number with the loop index `i`.
9. **Displaying Output**: The result is printed in the format `num ❌ i = result`.

---

## Usage
- **Learning Java Basics**: Helps beginners understand loops and user input in Java.
- **Mathematical Computation**: Useful for quickly generating multiplication tables.
- **Console-Based Applications**: Demonstrates a simple approach to interact with users via the console.

---

## How to Run the Program
1. Install **Java** (if not already installed).
2. Copy the above Java code into a file named `MultiplicationTable.java`.
3. Open a terminal or command prompt and navigate to the file location.
4. Compile the program using:
   ```sh
   javac MultiplicationTable.java
   ```
5. Run the compiled program using:
   ```sh
   java MultiplicationTable
   ```
6. Enter a number when prompted and view the multiplication table output.

---

## Example Output
### Input:
```
Enter the Number
5
```
### Output:
```
5❌1=5
5❌2=10
5❌3=15
5❌4=20
5❌5=25
5❌6=30
5❌7=35
5❌8=40
5❌9=45
5❌10=50
```

---

## Clone
```
https://github.com/Ananthadatta02/Java-Multiplication_Table.git
```
