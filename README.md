# Command Line (CLI) Introduction

A command line, also known as a command-line interface (CLI) or terminal, is a text-based way to interact with a computer or operating system. Instead of using a graphical user interface (GUI) with windows, icons, and buttons, you enter text-based commands into a terminal or command prompt to perform various tasks and operations on a computer. These commands are typically issued by typing specific commands and arguments into a text-based interface.

Here are a few key characteristics and examples of command lines:

1. **Text-Based**: In a command line, you interact with the computer by typing commands as text.

2. **Commands**: These are specific instructions or actions you give to the computer. For example, you can use commands to create, delete, move, and manipulate files and directories, as well as manage system settings and configurations.

3. **Arguments**: Many commands accept additional parameters, known as arguments, to provide more specific details about what you want the command to do. For example, in the command "ls -l," "ls" is the command to list files, and "-l" is an argument that specifies a long format for the list.

4. **Scripting**: You can create scripts, which are sequences of commands, to automate tasks by saving a series of commands in a script file.

5. **Cross-Platform**: Command lines are often available on various operating systems, including Unix-based systems (Linux, macOS), Windows (Command Prompt or PowerShell), and others.

Common command line interfaces include:

- **Unix/Linux Terminal**: These operating systems use shells like Bash or Zsh.

- **macOS Terminal**: It provides access to the Unix-based command line.

- **Windows Command Prompt**: A text-based interface for running commands on Windows.

- **Windows PowerShell**: A more advanced command-line environment with scripting capabilities.

- **Windows Subsystem for Linux (WSL)**: Allows running a Linux distribution alongside Windows, complete with its command line.

- **Command-line tools and utilities**: Many software packages and programming languages come with their own command-line tools for specific tasks.

Learning to use the command line can be very useful for tasks like system administration, programming, file manipulation, and automation. It offers a high degree of control and can be more efficient for certain tasks compared to graphical interfaces.

## What's a Shell ?

A shell is a command-line interface program that provides users with a way to interact with an operating system or computer. It serves as an intermediary between the user and the operating system's kernel, which is the core part of the OS responsible for managing system resources and executing commands. Shells interpret user commands and translate them into system actions.

Here are some key features and functions of a shell:

1. **Command Interpretation**: Shells interpret text-based commands entered by the user and execute the corresponding system operations. Users can issue commands to perform tasks such as managing files and directories, launching programs, configuring system settings, and more.

2. **Scripting**: Shells support scripting, which involves writing sequences of commands in a script file. These scripts can be executed to automate tasks and perform complex operations.

3. **Variable Management**: Shells allow the use of variables to store and manipulate data, making it easier to work with data in scripts and commands.

4. **I/O Redirection**: Shells enable the redirection of input and output, allowing users to read from or write to files, pipes, and other streams.

5. **Command Pipelines**: Shells support creating command pipelines, where the output of one command is used as the input for another, allowing for powerful data processing and manipulation.

6. **Customization**: Users can customize their shell environments by defining aliases, setting environment variables, and configuring various options to suit their preferences.

Common types of shells include:

- **Bash (Bourne Again Shell)**: A widely used shell on Unix and Linux systems. It's an enhanced version of the original Bourne Shell and provides extensive features and scripting capabilities.

- **Zsh (Z Shell)**: Known for its advanced customization options and extensibility. It's often used as an interactive shell and offers powerful auto-completion features.

- **Fish (Friendly Interactive Shell)**: Designed to be user-friendly with a focus on providing a pleasant interactive experience. It features syntax highlighting and auto-suggestions.

- **PowerShell**: Developed by Microsoft for Windows systems, PowerShell is both a shell and a scripting language. It's particularly powerful for managing Windows environments.

- **tcsh (TENEX C Shell)**: An enhanced version of the C Shell with additional features. It's commonly used in some Unix-based systems.

- **cmd.exe**: The default command prompt for Windows, which is less feature-rich than PowerShell but still used for running command-line operations.

The choice of a shell depends on the specific needs and preferences of the user and the requirements of the operating system. Different shells may have varying syntax and capabilities, but they all serve the fundamental purpose of allowing users to interact with and control their computers through text-based commands.

## What're the basic Unix Commands?

Unix and Unix-like operating systems, such as Linux, provide a wide range of command-line utilities for managing the system and performing various tasks. Here are some basic Unix commands that can help you get started:

1. **pwd (Print Working Directory)**: Shows the current directory/path.
   ```
   pwd
   ```

2. **ls (List)**: Lists files and directories in the current directory.
   ```
   ls
   ```

   Additional options:
   - `-l`: List in long format with details.
   - `-a`: List all files, including hidden ones.

3. **cd (Change Directory)**: Allows you to change your current directory.
   ```
   cd directory_name
   ```

   Use `".."` to move up one directory level.

4. **mkdir (Make Directory)**: Creates a new directory.
   ```
   mkdir directory_name
   ```

5. **rmdir (Remove Directory)**: Deletes an empty directory.
   ```
   rmdir directory_name
   ```

6. **rm (Remove)**: Deletes files or directories.
   ```
   rm filename
   ```

   Additional options:
   - `-r` or `-rf`: Recursively remove directories and their contents.

7. **cp (Copy)**: Copies files or directories.
   ```
   cp source_file destination
   ```

   Additional options:
   - `-r`: Copy directories and their contents.

8. **mv (Move)**: Moves or renames files and directories.
   ```
   mv source destination
   ```

9. **touch**: Creates an empty file or updates the timestamp of an existing file.
   ```
   touch filename
   ```

10. **cat (Concatenate)**: Displays the contents of a file.
   ```
   cat filename
   ```

11. **less (Pager)**: View file content one page at a time.
   ```
   less filename
   ```

   To navigate, use the arrow keys or the spacebar.

12. **head and tail**: Display the beginning or end of a file.
   ```
   head filename
   tail filename
   ```

   You can specify the number of lines to display, e.g., `head -n 10 filename`.

13. **grep (Global Regular Expression Print)**: Searches for text patterns in files.
   ```
   grep pattern filename
   ```

   It can be used with regular expressions for more complex searches.

14. **man (Manual Pages)**: Shows the manual page for a command, providing documentation and usage information.
   ```
   man command_name
   ```

15. **ps (Process Status)**: Lists currently running processes.
   ```
   ps
   ```

   Common options:
   - `aux`: Detailed process listing.

16. **kill**: Terminates processes.
   ```
   kill process_id
   ```

   Use `kill -9` to forcefully terminate a process.

17. **chmod (Change Mode)**: Changes file permissions.
   ```
   chmod permissions filename
   ```

   Permissions are represented in octal (e.g., 644 for read/write for owner and read for others).

18. **chown (Change Owner)**: Changes the owner of a file or directory.
   ```
   chown new_owner filename
   ```

19. **df (Disk Free)**: Shows disk space usage.
   ```
   df
   ```

20. **du (Disk Usage)**: Displays the size of directories and files.
   ```
   du
   ```

These are just a few basic Unix commands. Unix systems offer many more commands and utilities for various system administration, file manipulation, text processing, and networking tasks. You can use the `man` command to access the manual pages and learn more about specific commands and their options.