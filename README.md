
# CPU SCHEDULING ALGORITHM VISUALISER

### FCFS (First Come First Serve):  <br>
FCFS Algorithm. is a non-preemptive algorithm and it execute processes according to its arrival time(process that comes first in the ready queue). FCFS also suffers from starvation which arise if the first process has larger burst time. <br>

![fcfs](https://github.com/PrinceSinghhub/CPU-SCHEDULING-ALGORITHM-VISUALISER/assets/71000042/3dedd47e-c940-4ac7-bb34-19cc0d528655)


### SJF (Shortest Job First):   <br>
SJF Algorithm. is a non-preemptive algorithm in which the process having shortest /smallest burst time is executed first. It significantly reduces the average waiting time for other processes awaiting execution. <br>


![sjf](https://github.com/PrinceSinghhub/CPU-SCHEDULING-ALGORITHM-VISUALISER/assets/71000042/eef6c64c-a190-4528-8ab0-99d4187dc55e)


### RRS (Round Robin Algorithm):  <br>
Round robin is a pre-emptive algorithm. The process that is preempted is added to the end of the queue. This algorithm also offers starvation free execution of processes.  <br>

![rrs](https://github.com/PrinceSinghhub/CPU-SCHEDULING-ALGORITHM-VISUALISER/assets/71000042/18792508-5482-4200-a5fd-e99da6850ef1)


### LJF (Longest Job First):  <br> 
LFJ algorithm is a pre-emptive algorithm. The process having the largest burst time is chosen for the next execution. When a job comes in, it is inserted in the ready queue based on its burst time. <br>

![ljf](https://github.com/PrinceSinghhub/CPU-SCHEDULING-ALGORITHM-VISUALISER/assets/71000042/b1dd5d75-623a-4829-9c1c-dd1924191fb8)


### Priority CPU Scheduling:  <br>
It is a non-preemptive algorithm. In this algo if the new process arrived at the ready queue has a higher priority than the currently running process, the CPU is preempted, which means the processing of the current process is stoped and the incoming new process with higher priority gets the CPU for its execution.  <br>

![proty](https://github.com/PrinceSinghhub/CPU-SCHEDULING-ALGORITHM-VISUALISER/assets/71000042/b097b7f0-37a3-4232-afe0-10b4e19e3191)


### LRTF (Longest Remaining Time First):   <br>
LRTF is a pre-emptive algorithm. Here the job that has the highest burst time is allocated CPU first. The operating system to schedule the incoming processes so that they can be executed in a systematic way. In case of LRTF the average waiting time is high.  <br>

![lrtf](https://github.com/PrinceSinghhub/CPU-SCHEDULING-ALGORITHM-VISUALISER/assets/71000042/d6ba43d7-c175-4254-9641-6b468e65d92b)



### SRTF (Shortest Remaining Time First):  <br>
SRTF is a pre-emptive algorithm. At the arrival of every process, the short term scheduler schedules the process with the least remaining burst time among the list of available processes and the running process. Processes which have long burst time will have to wait for long time for execution  <br>

![srtf](https://github.com/PrinceSinghhub/CPU-SCHEDULING-ALGORITHM-VISUALISER/assets/71000042/c0506b2d-c5e6-4506-826b-1210d567d7ea)

