0x11. C - printf
Group project
 By: Julien Barbier, co-founder & CEO
 Weight: 5
 Project to be done in teams of 2 people (your team: Anana Anana, Oladimeji Akiosi)
 Project will start Jul 21, 2023 6:00 AM, must end by Jul 26, 2023 6:00 AM
 Checker will be released at Jul 22, 2023 12:00 PM
 An auto review will be launched at the deadline
Concepts
For this project, we expect you to look at these concepts:

Group Projects
Pair Programming - How To
Flowcharts
Technical Writing

This a repository for the ALX team project for the printf.

The printf() function prints output to stdout, according to format and other arguments passed to printf(). 
The string format consists of two types of items - characters that will be printed to the screen,
and format commands that define how the other arguments to printf() are displayed. Basically,
you specify a format of string that has text in it, as well as "special" characters
that map to the other arguments of printf().

Requirements
General
Allowed editors: vi, vim, emacs
All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89
All your files should end with a new line
A README.md file, at the root of the folder of the project is mandatory
Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl
You are not allowed to use global variables
No more than 5 functions per file
In the following examples, the main.c files are shown as examples. You can use them to test your functions, but you don’t have to push them to your repo (if you do we won’t take them into account). We will use our own main.c files at compilation. Our main.c files might be different from the one shown in the examples
The prototypes of all your functions should be included in your header file called main.h
Don’t forget to push your header file
All your header files should be include guarded
Note that we will not provide the _putchar function for this project
GitHub
There should be one project repository per group. The other members do not fork or clone the project to ensure only one of the team has the repository in their github account otherwise you risk scoring 0%

More Info
Authorized functions and macros
write (man 2 write)
malloc (man 3 malloc)
free (man 3 free)
va_start (man 3 va_start)
va_end (man 3 va_end)
va_copy (man 3 va_copy)
va_arg (man 3 va_arg)
Compilation
Your code will be compiled this way:
$ gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c