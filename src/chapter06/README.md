# Chapter 06: Synchronization using keyword

1. Use *synchronized* keyword to specify the variable only accessed by a thread at the moment, and other threads can not acquire that variable.  
The code block of *synchronized* is called *critical section*. And this section is locke based on the specified variable.
