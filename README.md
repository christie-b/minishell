# minishell

[![jaeskim's 42Project Score](https://badge42.herokuapp.com/api/project/cboutier/minishell)](https://github.com/JaeSeoKim/badge42)

Validated on November 1st, 2021

100/100 

This project is about creating a simple shell.  
Minishell features:  
- Working history
- Redirections (`<`, `>`, `<<`, `>>`)
- Pipes
- Environment variables are expanded, except when there are in double quotes `""`
- `$?` for the exit status
- Signals (`ctrl-c`, `ctrl-d`, `ctrl-\`)
- Built-ins:
    - echo (`-n` option is also implemented),  
    - cd (with or without an absolute or relative path, `-` and `~` are also implemented),   
    - pwd (without options),  
    - export (without options),  
    - unset (without options),  
    - env (without options),  
    - exit (can be followed by a number which will be the exit code).  
- Single and Double Quotes management,  
- System calls errors management,  
- The `SHLVL`variable.   

Project was done on Linux, not working on Mac as the readline function rl_replace_line does not exist on Mac.  

**HOW TO RUN THE PROGRAM**  
`make`  
`./minishell`
