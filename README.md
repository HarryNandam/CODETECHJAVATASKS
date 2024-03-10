# CODETECHJAVATASKS
#basic calculator
Importing Scanner: The program imports the Scanner class from the java.util package to facilitate user input.

Main Method: The main method is the entry point of the program.

Welcome Message: Prints a welcome message to greet the user.

Input First Number: Prompts the user to enter the first number.

Input Second Number: Prompts the user to enter the second number.

Choose Operation: Displays a menu of operations (addition, subtraction, multiplication, division) and prompts the user to choose one.

Perform the Selected Operation: Uses a switch-case statement to perform the selected operation based on the user's choice. It handles division by zero error.

Output the Result: Prints the result of the operation to the console.

Closing Scanner: Closes the Scanner object to release system resources.
#number guessing game 
Importing Scanner and Random: The program imports the Scanner and Random classes from the java.util package to handle user input and generate random numbers, respectively.

Generating Random Number: It generates a random number between 1 and 100 using the Random.nextInt() method.

Variable Initialization: It initializes variables to store the user's guess, the number of attempts, and a boolean flag to track if the correct number has been guessed.

Welcome Message: Displays a welcome message to the user, informing them about the range of numbers they need to guess from.

Guessing Loop: Enters a loop that continues until the correct number is guessed (hasGuessedCorrectly becomes true). Within the loop, it prompts the user to enter their guess, increments the attempt count, and checks if the guess is correct.

Correct Guess Handling: If the guess is correct, it sets hasGuessedCorrectly to true and prints a congratulatory message with the number of attempts taken to guess the correct number.

Feedback for Incorrect Guesses: If the guess is incorrect, it provides feedback to the user, informing them if their guess was too low or too high.

Closing Scanner: Closes the Scanner object to release system resources.
#studentrecordmanagementsystem
Importing Scanner and HashMap: The program imports the Scanner and HashMap classes from the java.util package to handle user input and store student records, respectively.

Main Method: The main method is the entry point of the program. It initializes a Scanner object for user input and a HashMap to store student records.

Main Menu Loop: The program runs in a loop until the user chooses to exit. It displays the main menu options and prompts the user to enter their choice.

Handling User's Choice: Based on the user's choice, the program calls appropriate methods to add or view student records, or exit the program.

Adding a Student Record: The addStudentRecord method prompts the user to enter a student's name and roll number, adds the record to the HashMap, and displays a success message.

Viewing a Student Record: The viewStudentRecord method prompts the user to enter a student's name, retrieves the corresponding roll number from the HashMap, and displays the student record if it exists.


