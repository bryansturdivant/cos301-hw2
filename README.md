Bryan Sturdivant
COS 301
HW #2
10/10/2025

Manifest:

- README.md: This file: Overview and instructions
- hw02.py: Main Python script of the modified calc.py file 

Requirements:

- Python 3

Running:

Windows: python hw02.py
Mac: python3 hw02.py

This will start the program. There is no prompting or additional information provided. For example: 
    input: 3+4 
    output: 7
    input: x = 3+4
    output: //blank// but will store the result of x in a variable dictionary
    input: x
    output: 7
    input: 
    output: 

Modifications:
- Removal of all prompting
- Have errors sent to standard error stream instead of output, as requested
- Support of real numbers in the conventional manner: 3.14, 40.2
- Support of Floor Division and Modulo operators: //, %
- Numbers in integer form will be expressed as integers

Bugs and Limitations:

I believe it works as intended. I tested it, and everything seems to be working as the assignment has requested.

Resources used:

- Course lectures
- PLY Reading and examples
- w3schools.com as a reference guide for various syntax reminders
- Python documentation 

