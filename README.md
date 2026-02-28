Checkpoint 1
1. What do you want your code to do (explain both what you want it to do generally and what criteria you are aiming to fulfill)
Goal: I want my code to work as a calculator that will let users:
- Enter two numbers
- Choose an operation ( +, -,*, /)
- Get the correct answer

My criteria:
My goals for this project are:

-Create 3 functions
- Make sure all functions are used
- Use error handling to catch mistakes
- Handle at least 2 types of errors
- Handle 3 different errors
- Use at least 3 different string methods


Conclusion:
I want my program to be easy to use, not to crash when mistakes happen, and follow the rules I give it.

What does your code currently do (to gauge how much progress you believe you have made towards your goal)?
- Shows a "Welcome" message.
  
What areas would you like guidance on?
- Knowing how to add more operations, like roots
- Make a menu system



Checkpoint 2
1. Have you changed what you want your code to do? (If so tell me how its purpose has changed)
- When the code ends the equation it is no longer just going to stop there, instead it is going to give the option to add more equations
- Code is going to have the option of choosing a root equation

What have you added since last time to accomplish your goal? (New code?)
- I have finished the code

Here is a breakdown of the completed section since checkpoint 1:

String Section
- This section uses string methods to format and display messages in a way that looks neat
- It converts text to uppercase
- Removes extra spaces from text
- It capitalizes the word "Ready"
- It prints a line of dashes to separate sections of code
- This part is only for improving how the program visually looks

Get Digits From User Section ( #Function 2)
- This section will be asking the user to enter the first two numbers:
  1.Ask the user for the first number
  2.Ask the user for the second number
- Converts both inputs into decimal numers using float()
- Returns the two numbers
- If the user types something that is not a number:
  1. The program will catch the error
  2. Prints an error message
  3. It returns None values so that the program can safely stop the math calculation
  4. This will maintain the program from crashing due to the invalid inputs entered by the user

 Calculating num1 and num2 Functions Section (#Function 3)
 - Will ask the user to choose an operation: +, -, *, or /
 - Removes any extra spaces from the user's input
 - Verifies what operation was selected
 - Performs the right calculation, and only if valid inputs were entered
 - Prints the result
 - Handles errors such as:
   1. If the user tries to divide by zero: It shows an error message
   2. If the user enters an invalid operation: It shows an error message
   3. If anything unexpected or inavlid happens: It shows an error message
   - This will make the calculator safe to run at anytime and user-friendly so users do not get caught by surprise if code crashes

  Main Program Section (#Main Program)
  - This is where all the code runs
  - Calls the welcome function, which prints a welcome message
  - Calls the get numbers function, to get the input from the user
  - Checks if the input is valid
  - If valid, it will call function calculate to  perform the math
  -  Prints a final thank you message
    
   
4. What areas would like guidance on for this last checkpoint before the project is actually due?
- I don't currently have in mind any areas I need guidance on before the project is actually do.
   
   
