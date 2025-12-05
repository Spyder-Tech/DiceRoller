# Dice Roller Program

This Java program simulates rolling one or more dice. It prompts the user to enter the number of dice to roll, then displays each die with its face, the individual roll results, and the total sum of all dice rolled.

## Features

- User input for the number of dice
- Visual representation of each die face
- Displays individual roll results
- Calculates and shows the total sum

## How to Run

1. Clone or download this repository.
2. Compile the Java program:
   ```bash
   javac Main.java
   ```
3. Run the program:
   ```bash
   java Main
   ```
4. Enter the desired number of dice when prompted.

## Example Output

```
Enter the # of dice to roll: 3

               -------
              |       |
              |   •   |
              |       |
               -------
You rolled a: 1

               -------
              | •     |
              |       |
              |     • |
               -------
You rolled a: 2

               -------
              | •   • |
              |   •   |
              | •   • |
               -------
You rolled a: 5

Total: 8
```

## Code Overview

The program uses Java's `Scanner` class for user input and `Random` class for generating random die rolls. It includes a method `printDie()` that displays the ASCII art for each die face based on the roll.

## License

This project is for educational purposes. Feel free to modify and use the code as needed.

---

Feel free to customize further or add more features!
