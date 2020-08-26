Instructions
===================================
To build the file just type in the command line 'make' this will produce an executable file called 'terminal' to run the project just type './terminal'

While running, you will have your "shell" like UI user can type in what ever he wants and the program will display back what he typed, and also his input tokenized. 
Ex: 
    $ hello world 
    hello world
    Tokenize:[hello], [world],

The user is able to see his history by typing '!0"
Ex: 
    $ !0
    1: hello world
    
And also the user can re run any of his previous command by typing in '!<command to run>'
Ex: 
    $ !1
    hello world
    Tokenize:[hello], [world],

