#Chapter 2 Review Questions
Name: Daita Manjusri
Course: 5143 Operating Systems
Date: 16 Feb 2016 

##Question1
What are three objectives of an OS design?
Objectives of os design:
User friendly :
Different people must be able to use the operating system with equal ease.
Performance :
Operating system should perform tasks in least amount of time.So the performance must be satisfactory for a user.
Efficient:
Efficiency in the way os utilizes the hardware resources in an efficient way with an output with least effort.

##Question2
What is the kernel of an OS?
1.Kernal is called the central part of the operating system.Kernal controls the computer hardware and computing.
2.It can also be called as computer program that manages the i/o requests from the software and translates them into data processing instructions for the CPU.
3.The main concept of kernal of os is to manage the communication between the software (user level applications) and the hardware (CPU,disk memory).

##Question3
What is multiprogramming?
1.MultiProgramming is a form of parallel programming where several programs run at the same time on a uniprocessor.
2.Here os operates one part of one program,another part of another program simultaneoulsy.
3.For user it appers that the all programs are being executed at the same time

##Question4
What is a process?
Process is an environment in which a program  is executed.It can also be defined as unit of execution.

##Question 5
How is the execution context of a process used by the OS?
Execution context includes information for execution and managing of processess.It consists of program counter,data register
OS uses the data from this during process execution.

##Question6
List and briefly explain five storage management responsibilities of a typical OS.
Five Storage management responsbilities of os:
1.Process isolation
Prevention of data and instruction from interfering with each other process isolation helps this happen.
2.Automatic allocation and management
This is the process whereby allocation is handovered to programmer
3.Modular programming:
Programs are divided into modules. We can reate, destroy and alter the size of modules dynamically
4.Security and access:
Security is provided by controlling the access and thus integrity is protected
5.Storage:
Helps in storage of memory for a long time 

##Question7
Explain the distinction between a real address and a virtual address.?
Virtual address is also called as logical address.
Physical address is called as real address.
Virtual address serves as a implication point on virtual memory.
Physical address is a reference to the computers memory on a hardware tool which is physical
Virtual address is programmed on the software of computer.
Physical address is normally found on the memory of the physical computer
Benefit of having a logical address is that needed privacy is provided in terms of true postal address.
The physical address is not affiliated with email address or postal address.

##Question8
Describe the round-robin scheduling technique.?
In Round robin scheduling processess are inserted into a FIFO queue,here processess are given a limited cpu time called quantum.
Here when a process doesnot complete before the CPU's time expires then the next process waiting in the queue is allowed.
The preempted process is again ready to enter the queue later. 
Since this scheduling technique is a preemptive its is efficient in time sharing enivironment where the system needs to give efficient response time for interactive users
In this scheduling if quantum is set too short then more number of constant switches  occurs with lower CPU efficiency.Here generally the waiting time is more.

##Question9
Explain the difference between a monolithic kernel and a microkernel.
1.Monolithic kernal is very much older when comparared to micro kernal
2.Os using monolithic kernals are Unix,Linux where as os using micro kernal are Qnx,mach 
3.Monolithic kernals are a way faster then micro kernals.
4.Device drivers recide in kernal space in monolithic kernal whereas in micro kernal they reside in user space
5.Monolithic kernals are less secure. Micro kernals are more secured.
6.Monolithic kernal uses signals and sockets.Micro kernal uses message queues.

##Question10
What is multithreading?
1.The ability of an operating system to execute different parts of a program, called threads, simultaneously.
2.The programmer must carefully design the program in such a way that all the threads can run at the same time without interfering with each other.
3.In Multithreading threads work on same set of data so that they share same cache leading to better sybchronization on its values.
4.Multithreading is supported by operating system where CPU executes multiple threads concurrently.

##Question11
List the key design issues for an SMP operating system.
Bottlenecks of memory management:
In this processing,processing units may require more than available main memory ,though the proccessors have their own individual memory 
Speed and freqency issues of memory units may sometimes effect the entire processing
Scheduling:
Every process undergoes scheduling so the process should not face any conflicts while scheduling.



 
