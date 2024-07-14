Line of code (Calculator.java): 188
Line of code (Start.java): 26
Line of code (Calculator.java + Start.java): 214

Calculate method:

-Cyclomatic complexity: 12 (using Codalyze, in Visual Studio Code)
-Cognitive complexity: 13 (without using any tools)

Static analysis report:

After informal review of the code, the following conclusions were reached:

CALCULATOR FILE:

- Line 4 - Code Smell (Major) - Class 'Calculator' shouldn't be Public
- Line 18 - Code Smell (Blocker) - Rename method "ToString" to prevent any misunderstanding/clash with method
            "toString" defined in superclass "java.lang.Object"
- Line 183 - Code Smell (Minor) - 'Return' is considered redundant and should be erased

START FILE:
 
- Line 8/19 - Code Smell (Major) - System.out should be replaced by a logger
