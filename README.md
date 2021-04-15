# Types-Operators-and-Expressions
This is the next chapter in "the C Programming Language" which extends the scope of C and provides mathematical depth to such an otherwise syntactically simple language

First Commit:
This repository is the next chapter of the fundamental text which describes the mentioned constructs. Variables and constructs are considered the basic data types
within a program. Operators describe the computational aspects of a data type, whilst expressions combine variables and constants to produce new values. The type
of an object describes its sets of values and operations. This is considered the basis of C since its inception in 1972.

Second Commit:
The next commit will describe the semantics of naming variables.

Third Commit:
Each programming language contains semantics which define the naming of variables. Names consist of letters and digits in which the first name must be a letter. 
Underscores are included to facilitate code readability. Upper/lower case variables are distinct and it is often common practice to apply lower case names to variables and upper case for symbolic constants. Keywords are specifically designated by the language. The general practice in choosing variable names is to choose such names which are related to the variable's execution. Short names are used for local variables and long names for external variables. 

Fourth Commit:
The data types in C are as follows. 
char: a single computational byte holding one character
int: An integer reflecting the natural size of integers on the host machine. 
float: Single precision floating point. 
double: Double precision floating point. 

In computer science a floating point is the representation of real-numbers as an approximation between range and precision, whereas a data type is an attribute of 
data which the machine receives as a manipulation of the programmer.

Fifth Commit:
In computer programming a constant is a fundamental data type which cannot be altered during normal execution. I will expand on this in a future commit.

Sixth Commit:
The semantics of a constant is based around which data type they occupy. Each data type contains a constant with a character the most prominent. A character constant is written in single quotes whose value is the numeric correspondent of the specific character. These constants participate in numeric operations akin to any other structure in C, as they are often compared to other characters. 
Certain characters can be represented in character and string constants by escape sequences such as \n. The following program represents hexidecimal digits.

Seventh Commit:
No.

Eighth Commit:
Other constants also exist in C among the most common being a constant expression. A constant expression is one which is evaluated during compilation and contains
constants.

#define MAXLINE 1000
char line[MAXLINE + 1]

A string constant is a sequence of zero or more characters surrounded by double quotes.

Ninth Commit:
There is no limit to a string's length though a program is able to scan a string completely to determine its length. The standard library function strlen(s) scans 
a string, which is represented through the following program.

Tenth Commit:
There are instances in which enum is mentioned and executed in a program. If not all values are specified the progression continues from the previous specified 
value. The following file is an example. 
.
Eleventh Commit:
The file is written in an enumeration constant which describe Unix escape sequences and the progression of a Gregorian year.

Twelfth Commit:
This file describes declaration.

Thirteenth Commit:
In C a declaration is completed by a variable. A declaration also specifies a type and also contains a list of one or more types. Variables can be distributed among declarations, and a variable can be initialized for computation.

Fourteenth Commit:
The next file describes arithmetic operators.

Fifteenth Commit:
Arithmetic operators describe arithmetic. The binary arithmetic operators +, -, *, and the modulus operator %.

Sixteenth Commit:
The x % y expression produces the remainder x divided by y. The program describes a leap year convention with an if statement and an escape sequence. Furthermore,
% cannot be applied to float or double types.

Seventeeth Commit:
The next commit describes relational/logical operators.

Eighteenth Commit:
Relational operators are such which relate the logic of a programming language. They are intertwined with logical operators. The C textbook references precedence between such operators, though they must be named. Relational operators are >, <, >=, <=; logical operators are && and ||.

Nineteenth Commit:
The precedence of relational operators is below arithmetic ones, though high within C compilation. Logical expressions are evaluated from left to right. The following file is an example of this.

Twentieth Commit:
In this example the precedence of != is higher than the assignment which require extra parenthesis. The final section of this portion describes the != operator. This operator is referred to as a unary negation operand. The unary negation operand converts a non-zero operand into 0.

Twentyfirst Commit:
The next commit describes type conversions.

Twentysecond Commit:
When an operator has operands of different types they are converted to a single type. The main form of conversion are ones which convert a narrow operand into a wider one without a loss of information.

Twentythird Commit:
The type char is a small integer applied freely in arithmetic operations. The implementation of the atoi function is one which converts a string of digits into numerical equivalents. The next file describes the atoi function.

Twentyfourth Commit:
The following commits describe increment/decrement operators.

Twentififth Commit:
C provides two variables for increment/decrement of variables.
The increment operator ++
The decrement operator --
These are applied are increment/decrement operators.

Twentisixth Commit:
In a context where no value is wanted prefix/postfix are the same.

Twentiseventh Commit:
Each time a non-c occurs it is copied into the current j position which is incremented to be the next character.

Twentieighth Commit:
Another instance of prefix/postfix distinction is in the following code.

Twentininth Commit:
The previous file can be replaced by the following code.

