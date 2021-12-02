# Requirements

The main aim of this project is to design a basic calculator using a microcontroller Atmega328,LCD and a keypad and should be able to perform basic operations such as addition,substraction ,multiplication and division on two operands that are entered by the user .


# Research/State of Art 
A simple calculator takes input from a keypad and displays the answer on a 16*2 LCD display. To build a simple calculator that adds and subtracts, four stages are needed.
The first stage takes the serial input of a number from a keyboard, converts the number into hex, and stores it into memory. The second stage also takes serial input from the keypad only this time it is an operation key.  The third stage repeats the first stage by storing a second hex number to memory.
Finally, the fourth stage is performed when the equal sign is pressed. It uses a 4 x 4 keypad to take input from user and display it on he LCD. 


# SWOT Analysis 

### Strengths:
 •	Provides fast and efficient solution.
 
 •	It is low in cost .
 
 •	It is easy to use for consumers.
 
 •	System is small in size and portable  .
 
 ###  Weakness:
  • Only provides 2 digit operations
  
  • Many complex mathematical operations cannot be performed.
  
### Opportunities:
• Affordable calculating system. 

 • Further making modifications  in the system it can be more fast and perform high level operations . 
 
 
 
 ### Threats:
 • In case of power failure it will not work.
 
 • No option to save history in case of system failure.
 
 

# 4 W’s and 1H
#### What  :

The main objective of this project is to perform basic mathematical calculations such as addition ,multiplication,sustraction adnd division with the use of of Microcontroller, Key pad and LCD .

#### Where  :
  It can  be implemented in any places like our Houses, Institutions, Banks etc
 
#### Who   : 
 The project also exhibits low cost system wh ich is widely needed  in our daily  life. The system is user friendly and  the cost of the system is low it can be used by everyone in their everyday life.
 
#### When :

The use of this calculator is neccessary in eveyday life and digital calculator is benefitial to provide automated mistake free and automated matheematical soltions to the users .  

#### How:
This design of calculator using an Atmega328 microcontroller can be used to perform basic mathematical operations such as addition, substracction, multiplication and division and display the results on a LCD screen . 

# High level Requirements 
| ID | Description  |Status|
| ------ | ------ |------|
| HLR  1 | System should display enter expression.| Implemented|
| HLR  2 | It should display the digits entered by user  |Implemented |
| HLR  3 | It should perform basic operartion and display the result on LCD Screen . | Implemented |

# Low level Requirements 
| ID | Description  | Status |
| ------ | ------ | ------|
| LLR  1 | Take input from user from the keypad input   | Implemented |
| LLR  2 | Take the operation to be performed from the user | Implemented |
| LLR  3 | Perform the operation and display result on 16 x 2 LCD  | Implemented |

