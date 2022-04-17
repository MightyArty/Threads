# Threads
## Third assigment in Operating System course
The original code was taken from https://beej.us/guide/bgnet/html/#a-simple-stream-server

We needed to make the server be able to support multiple clients using threads insted of fork().

## What is a Thread?
A thread is a single sequence stream within in a process. Because threads have some of the properties of processes, they are sometimes called lightweight processes.

## What are the differences between process and thread?
Threads are not independent of one other like processes as a result threads shares with other threads their code section, data section and OS resources like open files and signals. But, like process, a thread has its own program counter (PC), a register set, and a stack space.

## Running Programm:
```bash
# Clone the repository
$ git clone https://github.com/MightyArty/Threads.git
# Go into the repository
# Open two or more terminals
# One for the server, the others for the clients
$ Run "make"
$ Run "./server"
$ Run "./client"
```