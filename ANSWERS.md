# Assignment Questions

## Instructions
Answer all 4 questions with detailed explanations. Each answer should be **3-5 sentences minimum** and demonstrate your understanding of the concepts.

---

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes?

**Your Answer:**

A process is a program in execution that has its own memory space and system resources, while a thread is a smaller unit of execution

---

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from your program output.

**Your Answer:**

In Round-Robin scheduling, if a process does not finish within its time quantum, it is paused and moved to the end of the ready queue. This allows other processes to take their turn and ensures fairness among all processes. The process will not continue immediately but waits until it comes back to the front of the queue again. This behavior prevents any process from taking too much CPU time. It also keeps the system responsive when multiple processes are running.

Example from my output:
```
[Paste a relevant snippet from your program output here showing a process being re-queued]
```

**Explanation of example:**
[Explain what's happening in the output snippet you pasted]

---

## Question 3: Thread States

**Question**: A thread can be in different states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (P1) from your simulation.

**Your Answer:**

In this simulation, each process goes through several thread states during its execution lifecycle. Process P1 starts as a thread and moves between different states depending on how it is scheduled and executed by the CPU. These states reflect how the thread interacts with the scheduler and how it uses CPU time. By tracing P1 in the program, we can clearly see how Java threads transition between states during execution. Below is a step-by-step explanation of each state:

1. New:  
P1 is in the New state when the thread is first created using new Thread(process) but before calling start().

2. Runnable:  
P1 enters the Runnable state after start() is called, where it becomes ready to run and waits for the CPU scheduler to assign it execution time.

3. Running:  
P1 is in the Running state when the CPU executes its run() method during its time quantum.

4. Waiting:  
P1 enters the Waiting state when Thread.sleep() is called, which pauses the thread temporarily to simulate execution time.

5. Terminated:  
P1 reaches the Terminated state when it completes execution and its remainingTime becomes zero.

---

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. Explain why this scheduling algorithm works well for those scenarios.

**Your Answer:**

### Example 1: [Name of application/scenario]

**Description**: 
[Describe the real-world scenario or application]

**Why Round-Robin works well here**: 
[Explain why Round-Robin scheduling is suitable. Consider fairness, responsiveness, predictability, etc.]

### Example 2: [Name of application/scenario]

**Description**: 
[Describe the real-world scenario or application]

**Why Round-Robin works well here**: 
[Explain why Round-Robin scheduling is suitable. Consider fairness, responsiveness, predictability, etc.]

---

## Summary

**Key concepts I understood through these questions:**
1. 
2. 
3. 

**Concepts I need to study more:**
1. 
2. 
