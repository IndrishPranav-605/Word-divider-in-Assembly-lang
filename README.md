README for Assembly Program
🖥️ Assembly Language Program - Character Display with Commas

📌 Project Overview
This is an 8086 Assembly Language Program that:

Takes a user input string.
Displays each character individually, separated by commas.
Uses DOS interrupts for input and output operations.
🛠️ Features
User input handling using INT 21h.
Character-by-character display with comma separation.
Efficient program termination with INT 21h (4Ch).
📂 File Structure
bash
Copy
Edit
📦 Assembly-Program
 ┣ 📜 main.asm      # Assembly source code
 ┣ 📜 README.md     # Documentation
 ┗ 📜 run.bat       # Script to assemble and run the program
🚀 How to Run
Requirements
DOSBox or an emulator that supports 8086 assembly execution.
MASM (Microsoft Macro Assembler) or TASM (Turbo Assembler).
Steps
Assemble the code using MASM:

css
Copy
Edit
masm main.asm;
link main.obj;
(For TASM, use tasm main.asm & tlink main.obj)

Run the program:

css
Copy
Edit
main.exe
