# SyntaxMaster-A-PLY-Based-Context-Free-Grammar-Validator-for-C-Constructs

SyntaxMaster is a Python-based tool designed to validate the syntax of C++ programming constructs using Context-Free Grammar (CFG) and the PLY (Python Lex-Yacc) toolkit. This project aims to assist developers and students in checking the correctness of fundamental C++ code structures.

## Features

- **For Loops**: Validate the correct syntax of `for` loops.
- **Function Declarations and Definitions**: Check the syntax of C++ function declarations and definitions.
- **If-Else Statements**: Ensure proper syntax for `if-else` and `nested if-else` constructs.
- **Switch Case**: Validate `switch-case` statements, including `default` and `break` conditions.

## Getting Started

### Prerequisites

Ensure you have Python installed (preferably Python 3.6 or higher). You'll also need to install the PLY library:

```bash
pip install ply  

## Usage

Clone the repository and navigate to the project directory:
git clone https://github.com/yourusername/SyntaxMaster.git  
cd SyntaxMaster  
Run the Python script to validate C++ code snippets:  
python syntax_validator.py  
You can modify the data variable in the script with your own C++ code snippet for validation.

## Example
Here's an example of how to use SyntaxMaster:
data = """
for (int i=0; i < 10; i++) {
    if(i==2){
        x=x+1;
    }
    else{
        x=x/2;
    }
}
"""

result = parser.parse(data)
If the syntax is valid, you'll receive a "Parsed successfully" message.
