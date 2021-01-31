# intro-to-algorithms
class the intro to algorithms
# Fundamental concepts
## Define concepts and characteristics  of  algorithms
### Concept
Lists of instructions for resolving a calculation or abstract problem, that is, a finite number of steps convert data from a problem **(input)** into a solution **(output)**. 
### Characteristics
 - An algorithm must be accurate and indicate the order in which each step is performed.
 - An algorithm must be defined. If you follow an algorithm twice, you must get the same result each time.
 - An algorithm must be finite. the algorithm must be terminated at some point; that is, you must have a finite number of steps. 
 - An algorithm must be readable: The text describing it should be clear, so that it allows you to understand and read it easily.

# Algorithm representation
## Differentiate control structures in the design and construction of an algorithm:

### -Selective structures
It is used to establish a series of steps with alternative to follow. This decision is regularly made after value conditions that will define the path. In this structure of this type the result is a Bolean value, that is, true or false.
### -Repetitive structures
It is used to control the repetition of a suction, a group of instructions or a complete algorithm
### - Nested structures
A set of statements or actions that precede each other.

## Describe the types of algorithm representation:
### - Graph: Flow chart
Are graphical representations of sequences of steps to be performed. Flow lines indicate the execution order. Flowcharts are used to represent small algorithms, as they
all space.
### - Written: pseudocode
Describe an algorithm similar to a programming language but without its
rigidity, more similar to natural language. They have the advantage of being more compact flowcharts, easier to write for complex and easier instructions
transfer to a programming language. The pseudocode is not governed by any standard. In these notes we will use the words READ/PRINT to represent the actions of data reading (the program receives data from somewhere) and data output (the program writes information in some medium).
The file explorer is accessible using the button in left corner of the navigation bar. You can create a new file by clicking the **New file** button in the file explorer. You can also create folders by clicking the **New folder** button.

# Data types and expressions
## Define the characteristics of the variables and constants
### Distinguish the types of computational data:
**- Numeric**
Numbers, both integers and decimals. The point is used to separate decimal places. Examples: 12 23 0 -2.3 3.14
**- Logic**
You can only take two values: TRUE or FALSE.
**- String and characters**
characters or character strings enclosed in quotation marks
(can be double or simple). Examples 'hello' "hello world" '123' 'FALSE'
'etc'
**- Arrangements**
Arrays are homogeneous data structures that can store a certain number of data under a single identification, and then them using one or more subscripts. Arrays can be thought of as vectors, matrices, etc.
In order to use an array, sizing is required first; Is
define it by declaring the ranges of its subscripts, which determines how many elements will be stored and how they will be accessed.
### Describe the representation of computational data:

**-Variables**
•Identifiers, or variable names, must consist only of letters,numbers and/or underscore (_), always starting with a letter.
• Variable data types are not explicitly declared, but
infer from their us
**-Constants**
• Character constants are enclosed in quotation marks ( " ).
• In numeric constants, the period ( . ) is the decimal separator.
• Logical constants are True and False.
### Explain the types of computational operations:

#### Operators:

**- Arithmetic**
***Binary:*** binary operators indicating simple increment (addition or multiplication) and decrement (subtraction, division, and module) operations, these are the binary operators:
 
**(+)** Represents the sum of two or more or variables.
**(-)**  Represents the subtraction of two or more values or variables.
**(*)** Represents the multiplication of two or more values or variables.
**(/)** Represents the division of two or more values or variables.
**(%)**  Represents the module (obtaining the residue of a division) of two or more values or variables.
 
***Unary:*** unary operators represent simplified operations of incrementing decrement and modifying signs, these are the unary operators:
 
**(++)** Increases the value of a variable in a unit.
**(--)** Decreases the value of a variable in a unit.
**(-)**  Changes the sign of a variable, it is like multiplying by -1.

**- Logic**
They are join operators, also called logical gates, these operators can join two or more pairs compared by the relationships operators and given by these symbols:

**(&&)** Y Operator (Y) means that all conditions must be for an action to run.

**(||)** : OR operator (O) means that of all conditions it should only be and it is assumed that that is enough to take action.
 
**(!)**  Operdaro NO (NO) means that the statement is denied to change its value, i.e. from true to false and from false to true. 

**- Relationships**
They are operators that are responsible for joining and comparing two or more values, are always used in pair comparisons and are given by symbols:

**(==)**  The same as 

**(!=)** Different from

**(>)** Greater than

**(<)** Less than

**(>=)**  Greater than

**(<=)**  Less equal to
These operators are used to compare variable values by pairs, i.e., no more than 2 values can be compared over time:
- a > b > c //ERROR 
- (a > b) && (b > c) //WELL

#### Operands:

**-Variables**
A variable is a memory space reserved to store a value that corresponds to a data type by the programming language. A represented variable is and used through a tag (a name) assigned to it by a programmer or already unknown.

Variables can be of type:

- Boolean
- Whole
- floating-point decimal
- character, text string
- Arrangement 
- Matrix
- user-defined type

**-Constants**
A constant is an identifier of a data that does NOT change value throughout the execution of a program.
A constant is like a variable but with the difference that once it takes a value it cannot vary during script execution, another particularity of the constants is that they are global, so they can be read from inside a function without having to pass them as a parameter. Unlike variables, constants do not need the dollar sign ($) to express themselves, they are defined using the function define (Canstant Name, ItsValue).

### Expressions:

**- Arithmetic**
Similar to mathematical formulas. It is an expression that manipulates values
(constants, names) and their arithmetic operators (algebra) and the result
it's a number value 
In an assignment the expression is assigned and the result is assigned a variable **A**

**- Logic**
Logic is a discipline that studies form of reasoning uses rules and
techniques for determining whether a statement or proposition is false or true.
