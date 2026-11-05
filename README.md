Module 1 — Terminal Fundamentals
- History of terminals and teletypewriters
- Physical terminals
- Virtual consoles (TTY1, TTY2, etc.)
- Terminal emulators
- TTY devices


Module 2 — TTY and PTY Internals
- What is a TTY?
- What is a PTY?
- PTY master and slave
- /dev/tty
- /dev/ptmx
- /dev/pts
- Terminal allocation


Module 3 — Shell Internals
- Shell vs terminal
- Bash vs Dash vs Zsh
- Interactive and non-interactive shells
- Login and non-login shells
- Environment variables
- Shell job control


Module 4 — Process I/O
- stdin, stdout and stderr
- File descriptors
- File descriptor tables
- Redirection
- Pipes
- Named pipes (FIFOs)
- /proc/PID/fd


Module 5 — Terminal Control
- Foreground and background processes
- Process groups
- Sessions
- Controlling terminals
- Signals (SIGINT, SIGTSTP, SIGHUP)
- termios


Module 6 — Real-world Applications
- How SSH allocates PTYs
- How Docker's -it works
- How tmux and screen work
- Terminal behavior in scripts
- Interactive applications