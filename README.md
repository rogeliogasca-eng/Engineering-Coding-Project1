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
- When the code ends the equation it is no longer just going to stop there, instead it is going to give the option to give your name
- Code is going to have the option of giving your name
- Name will be displayed in the beginning and in the end

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



Final Checkpoint
1. Does your code fulfill exactly what you have written in your README.txt file?
   Yes, my code exactly fulfills what I have written in my README.text file.
   
2. Do you leave comments (using #) within your code to explain what a function does, or what the purpose of a while loop is in your code (this is especially important to keep track of and document if you have more than 1 while loop), or what a weird looking if statement does, etc.? Do you leave enough comments in your code that you or someone else could look at this a year from now and know exactly what each line does and how it helps make the program work?
   Yes, I have left comments in my code and somone else will be able to understand my code very easily. Due way in which I organized my comments my code is going to be very easy to understand, I organized my comments by sections of the code, each section of my code has a comment saying what it is about.
   
3. Does your code know how to handle alphabetic and non-alphabetic characters (numbers, special characters like "!", "~", "-", " ", etc.), or will it crash the program?
   Yes, my code knows how to handle alphabetic and non-alphabetic chacracters and it will not crash. If the user enters invalid characters my code will tell the user it is typing wrong characters and automatically stop itself, this will keep the code safe from crashing.
   
4. Are the instructions you give to the user clearly written? Will someone random be able to navigate the program and use ALL its features without you being there to help them?
   Yes, the instructions gven to the user are clearly written, and someone random will be able to navigate the program. My code is very user friendly and will be easy to navigate.
   
5. Does your code anticipate the user inputting a close-but-different variation of your "break" condition ("quit" or "Quit" or "DONE" or "n" for "no"?)? Essentially, how much freedom do you give the user to input different things, or if you don't give a wide variety of choices, do you clearly communicate how the user can get to where they want/do what they want in your code?
   Yes, I clearly communicate how the user can get to where they want. My code shows and tells the user the variety of options he has to enter, if the user enters a character that is obviously unvalid or not mentioned in the program, then it will tell the user.

7. Does your code use all the functions/features that you have in your program, or are there some old ideas that didn't get implemented that are just taking up memory?
   Yes, my ocde uses all the functions that I have in my program. 

   
   
