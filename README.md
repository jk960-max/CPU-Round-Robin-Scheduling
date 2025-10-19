# CPU-Round-Robin-Scheduling

Name: Joseph Kang


# Description of Round Robin Algorithm 
The Round Robin (RR) CPU scheduling algorithm is a CPU scheduling algorithm that assigns each task to execute its time. Tasks are assigned in a circular queue. When the time quantum expires but the task has remaining time, it moves to the end of the queue which means it’s preempted. If a process completes its execution before the quantum expires, it’s removed from the queue. This method gives an equal opportunity to execute and guarantees fairness of each process.


# Description of my Round Robin Visualization Scheduling Project Code
My code shows a Round Robin CPU scheduling algorithm visualization using Pygame. In the beginning, I put the settings with time quantum, process color, CPU color, background, text color, and finished color. I wrote the processes in a queue. This algorithm cycles through the processes using a fixed time quantum (I put 2 seconds but it can be changeable by the user), reducing each process’s remaining execution time. If a process still has remaining time after its quantum, it is moved to the back of the queue; otherwise, it is removed. It also updates each second to reflect the changing queue until all processes are completed and this algorithm ends. 

