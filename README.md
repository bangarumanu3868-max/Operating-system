# Operating-system
This repository contains notes, explanations, and examples of Operating System fundamentals including process management, memory management, scheduling algorithms, and file systems. Created for learning and academic purposes.

#Implementing System calls
#Description
This repository contains basic Operating System programs implemented in C. These programs are part of OS laboratory practice and help in understanding process management, system calls, and CPU scheduling algorithms.
#program include:procces management
file management
directory management


#FCFS Scheduling – Operating Systems
#Description
First Come First Serve (FCFS) is the simplest CPU scheduling algorithm. In this method, the process that arrives first in the ready queue is executed first.Execute process sequentically and calculate turnaround and waiting times.
Alorithm
1.arrange process in order they arrive in queue
2.execute process in the order they enter in queue,calclute turnaround time and waiting time for each process
3.calclute avg turnaroundtime and avg waiting time for all process

RoundRobin is define a time quantum for wach process execution.cycle through process,executing for the defined time quantum.update turnqround and waiting time based on quantum expiration.
-it is preemitive scheduling 
-All processes are placed in a ready queue
-CPU picks the first process
-Process executes for:
its burst time OR
the time quantum (whichever is smaller)
If the process is not finished:
it is moved to the end of the queue


# Priority Scheduling  
#Description
Priority Scheduling is a CPU scheduling algorithm where the process with the highest priority runs first. It is often examined in Operating Systems to learn about process management and scheduling methods.  
- To understand how priority-based CPU scheduling works  
- To look at process execution based on priority values  
Algorithm  
1. Each process gets a priority value  
2. The process with the highest priority is chosen for execution  
3. If two processes have the same
