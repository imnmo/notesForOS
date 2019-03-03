* Processor, Memory(volatile) and Disk
* We had to look at the shell and execution or interaction with the kernel and how the major three processes
  * Fork()
  * exec()
  * exit() are used within the context of OS
* Then usage of the file descriptor fd
  -> open
  -> read
  -> write
  -> close
 * the 0,1,2 of the FD tables such as stdinput, stdoutput and stderror

**File manipulation  (conventional way)**
 * sort > file.txt < tmp1
 * uniq > tmp1 < tmp2
 * wc < tmp3
 * rm tmp1 tmp2 tmp3

* OS usually provides gates in which it can access something, remember story who can access within the **root** access and which can
access as the someoneelse. As resources are shared between all users

**PIPES**
+  sort < file.txt | uniq | wc
* based on the scheduling the producer or consumer works or acts accordingly.
* Wc will always work until the EOF is reached, even though it started in parllel but it waits until EOF.
*
