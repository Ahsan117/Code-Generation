# Code-Generation
The program takes equations from a CSV file and generates TAC instructions accordingly. It analyzes the equations and uses a set of predefined operators and operands to generate the code. The generated TAC instructions represent a low-level representation of the equations, breaking them down into simple operations.

The program begins by reading the input CSV file and displaying its contents. It then processes each equation and generates TAC instructions based on the structure of the equation.

The TAC generation logic involves identifying variables, operators, and operands in the equations. It assigns register names to variables and uses the TAC instructions to perform assignments, additions, subtractions, multiplications, and divisions.

The generated TAC instructions are printed out, providing a step-by-step representation of the equations. The program also includes error handling for file not found, arithmetic errors, index out of range, and general exceptions.

In summary, this program serves as a code generator for Three Address Code, specifically tailored for processing equations stored in a CSV file. It automates the process of converting equations into low-level TAC instructions, facilitating further analysis or transformation of the equations.
