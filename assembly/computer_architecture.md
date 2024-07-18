# Computer Architecture

We need to at least know how computer interprets programs. The modern computer architecture is bason Neumann architecture which divides the computer into two main parts; the CPU (Central Processing Unit) and the memory. This architecture is used in all modern computer including cell phones.

## Structure of Computer Memory

To better understand how computer memory work, imagine a local post office that has a room filled with PO Boxes. Those boxes are similar to computer memory in that each are numbered sequences of fixed-size storage locations. For example if we have 256 megabytes of computer memory, it means that our computer contains roughly 256 million fix-size storage locations. Or refering to local post analogy, 256 million PO Boxes. Each location has a number, and each location has the same, fixed-length size. There is one thing to remember that we can store akk different kinds of things in a PO Box, but we cannot do the same in computer memory, we can only store a single number in a computer memory storage location. 

The computer memory is organized that way because it is simple to implement. Everything that is "stored" is stored in memory. Imagine the following:

* The location of our cursor on the screen
* The size of each window on the screen
* The shape of each letter of each font being used
* The layout of all of the controls on each window
* The graphics for all of the toolbar icons
* The text for each error message and dialog box
* The list goes on ...

## The CPU

Storing data doesn't do much help for computer to function. We need more than just store, we need to be able to access, manipulate, and move it. This is what CPU do. The CPU reads in instructions from memory one at a time and executes them. This is known as the __fetch-execute cycle__. In order to do that, the CPU contains the following:

* Program Counter:
  * tell the computer where to fetch the next instruction from
  * holds the memroy address of the next instruction to be executed
  * How? The CPU begins by looking at the program counter and fetching whatever number is stored in memory at the location specified which then passed on to the __instruction decoder__
* Instruction Decoder
  * figure out the meaning of the instruction passed by program counter.
  * the instructions include:
* Data bus
* General-purpose registers
* Arithmetic and logic unit
