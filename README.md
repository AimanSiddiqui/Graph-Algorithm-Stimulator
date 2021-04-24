# Graph-Algorithm-Stimulator

## Introduction: 
Our project is about Tomasulo’s Algorithm Simulation. It is basically dynamic scheduling of instructions that allows out of order execution and enables more efficient use of pipelining in modern microprocessors. Previously, when two instructions depended on each other, if the first uses the result of the second then first instruction has to wait until the second is finished, and one functional unit is idle. But if a different instruction, following the other two in the instruction sequence does not depend on their results, so it can be executed on the free functional unit. Data hazards must be handled properly. Hence, to solve this and make efficient use of microprocessor Tomasulo’s Algorithm is used.      

## Specifications:
We have developed a front-end in which we ask you for an option to select from run with values and run without values and then according to the selected option, we display, an Instruction Status Table which shows the status of instructions such as issue, execute, and write result. A Reservation Table which shows what instructions being executed and what resources being used. A Register Status Table which shows what is the content of registers after each instruction is executed.  
We have used following languages:
•	HTML5
•	CSS
•	JS

## Working & Achieved Results:
We are using some load, add, sub, div, mul, store instructions to simulate the algorithm. Instructions are issued sequentially so that the effects of a sequence of instructions such as exceptions raised by these instructions occur in the same order as they would in a non-pipelined processor, regardless of the fact that they are being executed non-sequentially.
All general-purpose and reservation station registers hold either real or virtual values (called as tags here). If a real value is unavailable to a destination register during the issue stage, a virtual value (tag) is initially used. The functional unit that is computing the real value is assigned as the virtual value (tag). The virtual register values are converted to real values as soon as the designated functional unit completes its computation and puts it on the bus. 
Functional units use reservation stations with multiple slots. Each slot holds information needed to execute a single instruction, including the operation and the operands. The functional unit begins processing when it is free and when all source operands needed for an instruction are real. 





## Simulation output: 
 
![image](https://user-images.githubusercontent.com/50028549/115969754-0dabcc80-a558-11eb-8581-2e13bfc8bcff.png)
![image](https://user-images.githubusercontent.com/50028549/115969756-12708080-a558-11eb-8c7b-8d4953341c63.png)
![image](https://user-images.githubusercontent.com/50028549/115969763-1bf9e880-a558-11eb-9577-bb7a96ccb189.png)
![image](https://user-images.githubusercontent.com/50028549/115969767-20be9c80-a558-11eb-8b1f-8d171cc6cf11.png)
![image](https://user-images.githubusercontent.com/50028549/115969772-24522380-a558-11eb-9305-af6e6e851ba6.png)

 
 
 
 
## Conclusion:
Hence, Tomasulo's Algorithm is a great way to exploit efficient use of resources when pipelining in modern microprocessors by removing dependencies and through this program we have successfully achieved the results.
