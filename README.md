This project belongs to the practical course Advanced Systems Programming in C/Rust

1. [task1_syscalls](https://github.com/YukioZzz/sys-prog-task1-syscalls): use `syscall API` and `asm assembly` to implement read/write; use `ptrace` mechanism to trace a subprocess's `read/write` syscall and its return value
2. [task2_fileio](https://github.com/YukioZzz/sys-prog-task2-fileio): use `FUSE API` to implement a in-memory filesystem
3. [task3_process](https://github.com/YukioZzz/sys-prog-task3-processes): implement an `interactive shell`(including pipeline and builtin commands)
4. [task4_concurrency](https://github.com/YukioZzz/sys-prog-task4-concurrency): implement `spinlock`(based on CAS), `lock-based hashmap` and `lock-free hashmap`
5. [task5_memory](https://github.com/YukioZzz/sys-prog-task5-memory): implement an efficient heap memory management(malloc, free, calloc, realloc) by reusing/spliting/merging free blocks; implement a `thread-safe` malloc by TLS
6. [task6_sockets](https://github.com/YukioZzz/sys-prog-task6-sockets): implement a TCP/IP server(with multithreaded `epoll`) and client
7. [task7_performance](https://github.com/YukioZzz/sys-prog-task7-performance): `gdb`, `perf`, `bcc`, `flamegraph`, etc.
8. [task8_container](https://github.com/YukioZzz/sys-prog-task8-container): build a sandbox based on the Linux `namespace` mechanism
