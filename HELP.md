# Help — Simple Line Editor in C

## Overview
This program is a simple command-line line editor written in C. It allows users to manage lines of text through the terminal.

## Features
- Insert a line of text
- Delete a line
- Display the document with line numbers

## How to Compile
Open a terminal in the project folder and run:

```bash
gcc line_editor.c -o line_editor
```

## How to Run
On Windows, run:

```bash
.\line_editor.exe
```

## How to Use
1. Start the program.
2. Follow the menu displayed in the terminal.
3. Choose the operation you want to perform.
4. Enter the requested line number or text.
5. Use the display option to view the document.

## Example
A document might contain:

```text
1. Hello
2. Welcome to my line editor
3. This is a C project
```

Use the options shown by your program to insert, delete, or display lines.

## Notes
Enter valid line numbers when prompted. The exact available commands depend on the features implemented in `line_editor.c`.
