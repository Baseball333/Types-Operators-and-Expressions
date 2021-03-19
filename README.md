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
