# procps
Rust reimplemtation of the procps project

Provides command line and full screen utilities for browsing procfs, a "pseudo" file system dynamically generated by the kernel to provide information about the status of entries in its process table (such as whether the process is running, stopped, or a "zombie").

Ongoing::
* `pwdx`: Shows the current working directory of a process.

TODO:
* `kill`: Sends a signal to a process, typically to terminate the process.
* `ps`: Displays information about active processes.
* `free`: Shows the amount of free and used memory in the system.
* `pgrep`: Searches for processes based on name and other attributes.
* `pidwait`: Waits for a specific process to terminate.
* `pmap`: Displays the memory map of a process.
* `skill`: Sends a signal to processes based on criteria like user, terminal, etc.
* `slabtop`: Displays detailed kernel slab cache information in real time.
* `tload`: Prints a graphical representation of system load average to the terminal.
* `top`: Displays real-time information about system processes.
* `uptime`: Shows how long the system has been running, including load average.
* `vmstat`: Reports information about processes, memory, paging, block IO, traps, and CPU activity.
* `w`: Shows who is logged on and what they are doing.
* `watch`: Executes a program periodically, showing output fullscreen.
* `pkill`: Kills processes based on name and other attributes.
* `snice`: Changes the scheduling priority of a running process.

Note:

 * /bin/kill is already implemented in https://github.com/uutils/coreutils

