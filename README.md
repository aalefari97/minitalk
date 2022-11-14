# minitalk

-> About
The purpose of this project is to code a small data exchange program using UNIX signals.

It is help to send massages from the client to the server by using the server PID.

-> Mandatory

- Produce server & client executables.
- client must communicate a string passed as a parameter to server (referenced by its process ID) which then displays it.
- Use SIGUSR1 & SIGUSR2 signals ONLY.

-> Allowed Functions

[malloc]
[free]
[write]
[getpid]
[signal]
[sigemptyset & sigaddset]
[sigaction]
[pause]
[kill]
[sleep]
[usleep]
[exit]

-> Compiling

$ ./server

PID: <PID_SERVER>

(wait)

$ ./client <PID_SERVER> <STRING>
