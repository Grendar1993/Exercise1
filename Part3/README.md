# Reasons for concurrency and parallelism


To complete this exercise you will have to use git. Create one or several commits that adds answers to the following questions and push it to your groups repository to complete the task.

When answering the questions, remember to use all the resources at your disposal. Asking the internet isn't a form of "cheating", it's a way of learning.

 ### What is concurrency? What is parallelism? What's the difference?
 > *Concurrency allows for multiple action i a program can be executed out-of-order or in partial order, without affecting the final outcome. Parallelism is more or less the same thing, but requires mutiple cores and is acctually exetuting the actions at the same time.*
 
 ### Why have machines become increasingly multicore in the past decade?
 > *We want the computer to run faster and faster on increasingly more complex programms, therefor it is a need for multiple cores to run parts of the prosessing in paralell, it also requiers lett power to run multiple smaller cores instead of one big powerfull core.*
 
 ### What kinds of problems motivates the need for concurrent execution?
 (Or phrased differently: What problems do concurrency help in solving?)
 > *Using concurrent execution makes the program more more expsandeble and useable on i wide varieties of computers. It also looks pretty and makes the code easily understandable.*
 
 ### Does creating concurrent programs make the programmer's life easier? Harder? Maybe both?
 (Come back to this after you have worked on part 4 of this exercise)
 > *After doing exercise 4 i would say it makes the programmer's life both harder end easier. It makes the code look really apealable and simple but there is alot of more stuff happening in the background that the programmer does not see*
 
 ### What are the differences between processes, threads, green threads, and coroutines?
 > *A process is a task or a programm that needs to be executed by a prosessor, threads are programm sections inside the process that can happen at the same time, green threads are threads that can simulate a thread envirement without having the capabilitys for threading in the os, corutines are simular to threads but they provide concurrency and not parrallelism*
 
 ### Which one of these do `pthread_create()` (C/POSIX), `threading.Thread()` (Python), `go` (Go) create?
 > **
 
 ### How does pythons Global Interpreter Lock (GIL) influence the way a python Thread behaves?
 > *It forces concurrency, since only one thread can use it at a time*
 
 ### With this in mind: What is the workaround for the GIL (Hint: it's another module)?
 > **
 
 ### What does `func GOMAXPROCS(n int) int` change? 
 > *GOMAXPROCS sets the maximum number of CPUs that can be executing simultaneously and returns the previous setting. If n < 1, it does not change the current setting. The number of logical CPUs on the local machine can be queried with NumCPU. This call will go away when the scheduler improves.*

