# Interactive-Memory-Manipulation
Implemented an interactive command-line utility which provides the ability to modify and examine
memory and provides basic memory test functionality.

Functionalitity
Help Function -  Invoking the help function will minimally list, to standard output, the available
				 commands and how to invoke them.

Allocate Memory - The user specifies the number of 32-bit words of memory to allocate.

Free memory - Used to release the previously allocated block.

Read memory - Display data stored at the memmory address specified by the user.

Write memory - User specifies an address and the 32-bit unsigned hexadecimal value to write. 
			   Memory at the indicated location is modified accordingly.

Invert block - Inverts all memory bits in a specified area of memory (address and number of 32-bit words). 
			   On completion, this command reports the amount of time taken to perform the operation.

Write pattern -  Write a pseudo-random pattern in a user specified (address and number of 32-bit words) area of
				 memory using a user specified seed value. 

Verify pattern - Verify a pseudo-random pattern in a specified area of memory using a specified seed value.
				 If pattern does not match, command should print expected and actual value and memory address 
				 where the discrepancy was found.
				 On successful completion, this command reports the amount of time taken to perform the operation.

# COMMANDS
![alt text](https://github.com/deep6000/Interactive-Memory-Manipulation/blob/master/MemoryCommands.PNG)
