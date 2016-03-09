# SequentialCyclometricProjectASE
Implemented sequential cyclomatic complexity in a chain of function calls using C# and Oracle database which introduces a new application in finding complexity of program.

McCabe’s Cyclomatic Complexity (CC) is well known software metric which indicates the complexity of a software unit such as a function or  an algorithm. It directly measures the number of linearly independent paths through a program's source code.  In the existing method of evaluating CC, chain of function calls will not be considered. However, it may not give the true complexity when a function includes other function calls. In this project, we are  modifying conventional CC for a chain of function calls. We consider that this will reflect the actual complexity of the function. 

Further, we extended this concept to evaluate the complexity of an entire program.
