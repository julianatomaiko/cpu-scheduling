# cpu-scheduling
## Operating Systems project that simulates CPU scheduling algorithms
### The goal of this project was to simulate four CPU algorithms on one CPU system using discrete events. The four algorithms are First Come First Serve (FCFS) non-preemptive, Shortest Remaining Time First (SRTF) which is pre-emptive by comparison of run times, and Round Robin (RR) with two different quantum values. For these four algorithms, I computed the average turnaround time, the total throughput, the CPU utilization, and the average processes in the ready queue. To achieve the simulator portion of the project, I implemented arrival and departure processes and a ready queue for waiting processes. To handle these events, I used linked lists to describe future events and to sort the time for each event.
