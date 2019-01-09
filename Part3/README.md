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
 > *Your answer here*
 
 ### What are the differences between processes, threads, green threads, and coroutines?
 > *Your answer here*
 
 ### Which one of these do `pthread_create()` (C/POSIX), `threading.Thread()` (Python), `go` (Go) create?
 > *Your answer here*
 
 ### How does pythons Global Interpreter Lock (GIL) influence the way a python Thread behaves?
 > *Your answer here*
 
 ### With this in mind: What is the workaround for the GIL (Hint: it's another module)?
 > *Your answer here*
 
 ### What does `func GOMAXPROCS(n int) int` change? 
 > *Your answer here*
