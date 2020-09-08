# CT78504
ENTERPRISE APPLICATION DESIGN AND DEVELOPMENT

## Java Basics(Review)

--> Top-Down Approach to the concepts.

### 1) Object-oriented Programming

- Model real-world scenarios in a natural way

- Object is used to represent real world entity

- Objects are defined by a class. Class is like a blueprint and objects are instances of a class.


### 2) Variables

- Container that hold something

- A type of data varialbe can hold is defined at the variable creation time itself by stating the variable types.

- Java is a statically-typed language.

- Variable types: primitive  & object references.

- 8 primitive data types.

  - Variable kinds
  
      o) Instances
    
      o) Static 
    
      o) Local 
  
      - Instance variable are unique to each object and they hold an object state. 
  
      - Static variable are class variables that are shared across all objects of the class.
  
      - Local variables are defined within mehthods or constructors. Even method paraemeter and constructor parameter are considered as local varialbes.
  
  
 ### 3) Arrays
  
 - In Java, Array is an object.
 
 - It get stored on the heap like other regular java object.
 
 - It stores fixed no of elements of a single type.Type can be either primitive or object reference.
 
 - Supports fast random access. Constant time O(1).
 
 
 ### 4) Methods
 
 - Define or represents behavior.
 
 - Java always uses pass by value mechanism while passing data to methods.Even for object references it passes a copy of the memory address of the object.
 
 - To overload, parameter list MUST be different.
 
 
 ### 5) Constructors:
 
 - Invoked when object is being created.
 
 - Initializes the object state.
 
 - We can have multiple constructor on the same class.
 
          - this()
              o) invokes overloaded constructor
              
              o) MUST be constructor's first element.
 
 
 
### 6) Arithmetic Operators:
 
 - Operands ~ primitive <b> numeric </b> types. all primitives except boolean.
 
 - One exception was plus(+) operator which is used for concatenating strings.
 
 - Rules:
     - Operator Precedence : It is useful when expression involves multiple operators on the order in which operations would be applied is not clear from the expression.
                            Rule 1: Preference to multiplicative operator to additive operator
                            Rule 2: Operator within ssame group will be evaluated from left to right.
                            
     - Operand Promotion: Operand smaller than int data type are promoted to int data type.
     
     - Same -type operands: if both operands are of same type then the final value of the operation will also be of the same type as the two operands.
     
     - Mixed - type operands : then smaller type is automatically promoted to larger data type.
     
 ### 7) Comparison and Logical Operators:
 
 -> Comparison : Compare one operand with another (referred to as relation operator)
 
           - == and != can compare object references (helps for performing null checks and avoiding runtime errors like <b>NullPointerException</b>
 
 -> Logical : Test multiple conditions
 
                 - && and || are short-circuited
                 
                 
### 8) Bitwise & Bit Shift:

-> Useful in resource contrained applications.

-> Bitwise operands ~ integer and boolean primitives.

-> Bitshift operands ~ integer primitives

          - Left-shift ~ multiplication by powers of 2
          
          - Unsigned right-shift ~ division by powers of 2
          
-> Applications: Compiler , hashing, embedded  & games programming



# 9) Switch Statement

-> Switch expression  ~ integer, String or enum

-> When to prefer switch over if?
    
    - Readability
    
    - Intent
    
    - Speed
    
             Note: Can use JProfiler to make the decision?
             
    - Effective Jave: Item 46: Prefer for-each loops to traditional for loops
    
    - Prefer for loops to while loops
    
    
              - 
 
 
 
