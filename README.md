# Practica-Cola
Mi ejercitacion para la implementacion del TDA de Cola como lista simplemente enlazada

#Compilacion
Para compilar, correr el comando:
  gcc -std=c99 -Wall -Wconversion -Wtype-limits -pedantic -Werror -g -o pruebas *.c

#Ejecucion con debugger
 
- archivo launch.json:

{
    // Use IntelliSense to learn about possible attributes.
    // Hover to view descriptions of existing attributes.
    // For more information, visit: https://go.microsoft.com/fwlink/?linkid=830387
    "version": "0.2.0",
    "configurations": [
        {
            "name": "(gdb) Launch",
            "type": "cppdbg",
            "request": "launch",
            "program": "${workspaceFolder}/pruebas",
            "args": [],
            "stopAtEntry": false,
            "cwd": "${workspaceFolder}",
            "environment": [],
            "externalConsole": true,
            "MIMode": "gdb",
            "setupCommands": [
                {
                    "description": "Enable pretty-printing for gdb",
                    "text": "-enable-pretty-printing",
                    "ignoreFailures": true
                }
            ]
        }
    ]
}
