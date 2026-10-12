# c-system-programming

System programming in C on Linux: working directly with the OS through system calls.

Each topic folder holds small, focused programs, each with a short comment at the top explaining what it demonstrates.

## Repository Structure

```
c-system-programming/
├── 01-file-io/          # open, read, write, close, lseek, stat
├── 02-processes/        # fork, exec, wait, exit status
├── 03-signals/          # signal handling, sigaction, kill
├── 04-pipes-fifo/       # pipe, named pipes (FIFO)
├── 05-ipc/              # shared memory, message queues, semaphores
├── 06-threads/          # pthreads, mutex, condition variables
├── 07-sockets/          # TCP/UDP client and server
├── 08-memory/           # malloc, mmap, memory layout
├── Makefile
├── .gitignore
└── README.md
```

## Requirements

- Linux
- GCC
- Make

## Build and Run

Build everything:

```bash
make
```

Build one topic:

```bash
make -C 02-processes
```

Remove compiled files:

```bash
make clean
```

## Progress

- [ ] File I/O
- [ ] Processes
- [ ] Signals
- [ ] Pipes and FIFOs
- [ ] IPC
- [ ] Threads
- [ ] Sockets
- [ ] Memory

## Notes

Programs are written for learning, so each one is kept small and does one thing. Error handling is checked on every system call.

## Author

Dinesh. GitHub: [dineshpec25-sys](https://github.com/dineshpec25-sys)
