# Student Performance Evaluation System

A simple Java console application that accepts a student's name and marks, validates the input, calculates the grade, and displays the student's performance report.

## Features

* Accepts student name and marks as input.
* Validates that marks are between **0 and 100**.
* Calculates percentage.
* Assigns grades based on marks.
* Displays a performance remark.
* Generates a formatted student performance report.

## Grade Criteria

|    Marks | Grade | Performance       |
| -------: | :---: | ----------------- |
| 90 – 100 |   A+  | Excellent         |
|  80 – 89 |   A   | Very Good         |
|  70 – 79 |   B   | Good              |
|  60 – 69 |   C   | Average           |
|  40 – 59 |   D   | Needs Improvement |
|   0 – 39 |   F   | Fail              |

## Requirements

* Java JDK 8 or later
* Command Prompt, PowerShell, or any Java IDE (IntelliJ IDEA, Eclipse, VS Code)

## Project Structure

```text
StudentPerformance.java
README.md
```

## How to Compile

```bash
javac StudentPerformance.java
```

## How to Run

```bash
java StudentPerformance
```

## Sample Input

```text
Enter Student Name: Jatin
Enter Marks (out of 100): 86
```

## Sample Output

```text
----- Student Performance Report -----
Student Name : Jatin
Marks        : 86/100
Percentage   : 86%
Grade        : A
Performance  : Very Good
```

## Input Validation

* Marks less than **0** or greater than **100** are rejected.

Example:

```text
Enter Marks (out of 100): 120
Invalid Marks! Please enter marks between 0 and 100.
```

## How It Works

1. Reads the student's name.
2. Reads the student's marks.
3. Validates the marks.
4. Determines the grade and performance using `if-else` conditions.
5. Displays the complete performance report.

## Technologies Used

* Java
* Scanner Class
* Conditional Statements (`if-else`)
* Console Input/Output

## Author

**Jatin Mahur**
