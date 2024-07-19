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
  * the instructions include for example, what process needs to take place (addition, substraction, multiplication, data movement, etc.) and what memory locations are going to be involved in this process. Computer instructions usually consists of both the actual instruction and the list of memory locations that are used to carry it out.
* Data bus
  * fetch memory locations to be used in the calculations. Data bus is the connection between the CPU and memory. It is the actual wire that connects them. If we look out at the motherboard of our computer, the wires that go out from the memory are our data bus. 
* General-purpose registers
  * In addition to the memory on the outside of the processor, the processor itself has some special, high-speed memory locations called registers. There are two kinds of registers - general registers and special-purpose registers. General-purpose registers are where the main action happens.
  * Addition, subtraction, multiplication, comparisions, and other operations generally use general-purpose registers for processing. However, computers have very few general-purpose registers. Most information is stored in main memory, brought in to the registers for processing, and then put back into memory when the processing is completed. special-purpose registers are registers which have very specific purposes. 
* Arithmetic and logic unit
  * Now that the CPU has retrieved all of the data it needs, it passes on the data and the decoded instruction to the arithmetic and logic unit for further processing. Here the instruction is actually executed. After the results of the computation have been calculated, the results are then placed on the data bus and sent to the appropriate location in memory or in a register, as specified by the instruction.
  * This is a very simplified explanation. Processors have advanced quite a bit in recent years, and are now much more complex. Although the basic operation is still the same, it is complicated by the use of cache hierarchies, superscalar processors, pipelining, branch prediction, out-of-order execution, microcode translation, coprocessors, and other optimizations. 

## Interpreting Memory
Computers can only store numbers, so letters, pictures, music, web pages, documents, and anything else are just long sequences of numbers in the computer, which particular programs know how to interpret.




### Review
#### Know the Concepts
1. Describe the fetch-execute cycle!
__Fetch-execute cycle__ is done by the CPU which involves five elements. First, the CPU begins the __fetch-execution__  by looking at the program counter which hold the information (memory address) of the next instruction to be executed. Then fetching the number stored in the memory at the location specified. It is then passed on to the **instruction decoder** which figure out what the instruction means for example is it substraction, addition and etc. and the memory locations are going to be involved. Then the __data bus__ used by the computer