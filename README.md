This is a group project developed with my teammate [Lucía (@lualon09)](https://github.com/lualon09) for the Compilers course at UCM.

# Project description
HaskPlus is a hybrid programming language combining concepts from Haskell and C++, designed to explore language design and compilation techniques taught in the course.

# Instructions to run the project
¡Hola!
If you are reading this, it means you want to execute our practice.

Inside the folder AnalizadorSintaticoCUP, you will find a script called ejecutar_todos.sh.
Simply run:

bash ejecutar_todos.sh

from your terminal while inside the AnalizadorSintaticoCUP folder.

This will automatically test the 27 provided examples.

Examples containing show() will display their results on screen.

Additionally, the first 20 numbers from input.txt will always be displayed. These correspond to 20 random numbers used for examples that require read() to read from a file.

If you want to test read() directly from the console:

Remove the < input.txt part from the script.

By default, it will read from the console.

You will need to adjust main.js, line 62, changing:

await readInput(20)

to

readInput(n)

where n is the number of elements you want to read from the console.
Alternatively, you can leave it as 20 and provide exactly 20 numbers.
