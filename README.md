Name-Mansha Sanger
Roll No-22000396
Project Title: Hinglish Compiler

Project Description:
This project is a compiler for a Hinglish-based programming language. Hinglish here likely refers to a syntactic or lexical blend of Hindi and English, customized into a specific language format (with .hgl files as source code). The compiler interprets or compiles .hgl code into an intermediate form, such as three-address code (output.tac), demonstrating parsing, lexical analysis, and compilation steps.

Objective:
	•	To design a compiler that can read, analyze, and process Hinglish-style syntax.
	•	To generate intermediate code from source programs written in .hgl files.
	•	To demonstrate use of tools like Lex and Yacc (evidenced by files like h.l, h.y, lex.yy.c, and h.tab.c/h.tab.h).

What the Project Does:
	1.	Lexical Analysis: Handled by h.l using Lex/Flex, generating lex.yy.c.
	2.	Syntax Parsing: Defined in h.y (a Yacc/Bison grammar), generating h.tab.c and h.tab.h.
	3.	Intermediate Code Generation: Likely managed by rules in the Yacc file, which generate output like output.tac.
	4.	Executable: compiler.exe is the compiled output that takes .hgl input files and produces output.
	5.	Sample Inputs: Several .hgl files (input.hgl, input2.hgl, etc.) are provided to test the compiler.

Instructions to Run the Project:
For Linux/macOS (using terminal):
	1.	Install required tools (if not already installed):
sudo apt install flex bison build-essential
	2.	Navigate to the compiler directory:
cd path_to/archimansha/archimansha/hinglish_compiler
	3.	Build the compiler (if not using compiler.exe):
make
	4.	Run the compiler on an input file:
./compiler input.hgl
	•	Output will typically be stored in output.tac.

For Windows:
	1.	Use compiler.exe directly (if compatible with your system).
	2.	Open Command Prompt and navigate to the folder:
cd path\to\archimansha\archimansha\hinglish_compiler
	3.	Run the compiler with an input:
compiler.exe input.hgl