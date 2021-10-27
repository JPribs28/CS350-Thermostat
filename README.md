# CS350-Thermostat

## Summarize the project and what problem it was solving.
The purpose of this project was to create a working thermostat that could detect the ambient air temperature, 
create a set point where the heat will turn on if the temperature falls below that point, and display output 
to the user as well as provide functionality to change the set point. This was achieved by implementing drivers 
to use the resources on the board such as serially communicating with another device, reading input from the 
sensors and buttons on the board, and manipulating the GPIO to turn on/off LEDs on the board.<br/><br/>

## What did you do particularly well?
One thing I did well was read the header files of the provided TI drivers to support the functionality of the 
board. This helped me with problem solving, sharpened my skills with understanding the C programming language, 
and helped me gain a better understanding of how the software interacts and controls the hardware.<br/><br/>

## Where could you improve?
One place I would like to improve my skills is working with state machines. State machines are ways to 
accurately control the hardware on the board without overcomplicating the code. I feel that I have a good 
understating of how they work and how to implement them, but I need to practice more with designing them to 
flawlessly incorporate them into my designs.<br/><br/>

## What skills from this project will be particularly transferable to other projects and/or course work?
Gaining a better understanding of the C programming language was one big advantage of working on this project. 
Many other programming languages are implemented with C so understanding what is going on behind the scenes 
could be a huge help when using these other languages. Also, with the increase of devices in our daily lives, 
working directly with the hardware in these devices is becoming increasingly common. Being familiar with common 
hardware interfaces such as GPIO, UART, and I2C is a valuable skill to have as this technology works its way 
into more aspects of our lives.<br/><br/>

## How did you make this project maintainable, readable, and adaptable?
Documenting and organizing the code is one of the most import things you can do to keep a project maintainable 
and readable. This gives others the ability to understand what you were trying to accomplish with a certain 
piece of code, as well as informing yourself if you ever need to come back to it. Just because it made sense 
when you wrote it doesn’t mean you will remember when you come back to it. Making use of functions was also 
another way to keep the code clean and readable. This helps keep the logic cleaner and provides a way to reuse 
pieces of code without writing it over and over again. This will also allow anyone to make changes more easily 
since they only have to make the change in one place. 
