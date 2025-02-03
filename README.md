Simple Calculator Program  
Description:   
      This is a simple calculator program written in C that performs basic arithmetic operations: addition, subtraction, multiplication, and division.  
      It allows the user to input two floating-point numbers and choose an operation to perform.   
      The program will display the result of the operation, and users can continue using the calculator until they choose to exit.  
Features:    
        *Add two numbers  
        *Subtract two numbers  
        *Multiply two numbers  
        *Divide two numbers (with error handling for division by zero)  
        *Continuously accept user input until the user chooses to exit  
#After the program starts, it will prompt you to choose an operation:   
        Press 1 for Addition  
        Press 2 for Subtraction  
        Press 3 for Multiplication  
        Press 4 for Division  
        Press 5 to Exit the program  
Enter Numbers:  
              After selecting an operation, you will be asked to input two floating-point numbers. The program will then display the result of the chosen operation.  
Exit the Program:   
             To exit the program, press 5 at the operation menu.  
Error Handling:  
             If you attempt to divide by zero, the program will display an error message: Error: Division by zero.  
             If you enter an invalid menu option, the program will display Invalid choice! and prompt you again for a valid input.  
Code Structure:  
Functions:  
             add(float a, float b) — Adds two numbers and prints the result.  
             subtract(float a, float b) — Subtracts two numbers and prints the result.  
             multiply(float a, float b) — Multiplies two numbers and prints the result.  
             divide(float a, float b) — Divides two numbers and prints the result, with an error check for division by zero.  
Main Function:   
             The main loop continuously displays the menu, prompts the user for input, and calls the appropriate function based on the user's choice.  
Requirements:  
             A C compiler (e.g., GCC) is required to compile and run the program.  
#Explanation:  
    Functions  : The program uses separate functions for each operation.  
      Menu     : The user can select the desired operation and input two numbers.  
      Loop     : The program runs in a loop, allowing the user to perform multiple operations until they choose to exit.  
#Simple Calculator(INPUT AND OUTPUT)  
1. Add  
2. Subtract  
3. Multiply  
4. Divide  
5. Exit  
Enter your choice: 1   
Enter two numbers: 5.2 3.8  
Result: 9.00  

Simple Calculator  
1. Add
2. Subtract
3. Multiply
4. Divide
5. Exit
Enter your choice: 4
Enter two numbers: 10 0
Error: Division by zero
