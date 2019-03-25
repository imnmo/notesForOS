## Linux Processes
* Process life cycle:
  * Any commands, something which get done in the Kernel like we saw the process like Web browser,
  etc.. which spawns a process
  * PROCESS has two parts:
    * Address space(virtual address): The RAM where it gets written or used
    * Kernel data structures that keep track of processes(schdeuler, nw, signal masks)
* PID
* IF you do the **Top** then you get the pid and other details. For PID 1 is the init
* ps aux | grep init runs the start up scripts


### Signals and processes

* SIGTERM 15 for natural termintion  and SIGKILL 9 for forced termination
* kill PID
* ctrl+c provides the SIGINTRPT
* pkill better like killall or pgrep are much more fine grained than the pgrep
* **htop** selectable and killable

### /proc systems
* /proc - active processes everything
* ls -alh is super useful
* strace

### lsof files

* 
