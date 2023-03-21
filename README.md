# documentation-automate-AST
![Obsidian graph image](https://github.com/kroq86/documentation-automate-AST/blob/main/image.png)

The purpose of the code is to generate documentation for Python code, and it does so by reading through all .py files in a given directory and its subdirectories. The code parses the AST (Abstract Syntax Tree) of each file to identify classes, methods, and attributes, and builds a directed graph with classes as nodes and methods/attributes as edges. It then generates Markdown files for each class with links to its methods and attributes, as well as an index file and a main file that links to the index and all classes. These Markdown files can be viewed as a graph in Obsidian's graph view, which provides a visual representation of the call stack.

To optimize the code's performance, cProfile has been added to profile the execution time of the functions. This allows developers to identify bottlenecks and optimize the code accordingly. 

The call stack graph generated by the code is a valuable tool for understanding how the code works and how it generates documentation for Python code. It can also help developers identify any potential issues or errors in the code.
