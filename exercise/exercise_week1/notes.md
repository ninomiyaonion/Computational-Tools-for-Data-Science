Run the script in terminal: ./helloworld.sh

## Bash script

### Introducing the shell (MacOS):

* **prompt** 提词 **$**
* `ls -F /` a **command**, some **flags** (also called options/switches), and a **argument**. **Flags** start with a single ot two dashes `-` and change the behaviour of a command. **arguments** tell the command what to operate on. Each part is separated by spaces.

#### The heart of a command-line interface is a **read-evaluate-print loop** (REPL).

1. Read what was typed (`ls -F /` in our example)
   The shell uses the spaces to split the line into the command, flags, and arguments
2. Evaluate:
   a. Find a program called `ls`
   b. Execute it, passing it the flags and arguments (`-F` and `/`) to interpret as the program sees fit
3. Print the output produced by the program

### Navigating Files and Directories:

Questions

- How can I move around on my computer?
- How can I see what files and directories I have?
- How can I specify the location of a file or directory on my computer?

Objectives

- Explain the similarities and differences between a file and a directory.
- Translate an absolute path into a relative path and vice versa.
- Construct absolute and relative paths that identify specific files and directories.
- Demonstrate the use of tab completion, and explain its advantages.



