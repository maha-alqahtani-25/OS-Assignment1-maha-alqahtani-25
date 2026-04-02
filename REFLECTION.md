# Reflection Questions

## Instructions
Answer the following questions about your learning experience. Each answer should be **at least 5-7 sentences** and show your understanding.

---

## Question 1: What did you learn about multithreading?

**Your Answer:**

[Through this assignment, I learned how multithreading allows multiple tasks to run concurrently within the same program. I understood how to create threads in Java using the Runnable interface and how to start them using Thread.start(). I also learned about different thread states such as running, waiting, and terminated, especially when using methods like sleep() and join(). One important concept I learned is how threads share CPU time using scheduling algorithms like Round-Robin. I found it interesting how each process runs for a fixed time quantum and then yields the CPU to another process. This helped me understand how operating systems manage fairness between processes. Overall, I gained a clear understanding of how multithreading improves performance and responsiveness.]

---

## Question 2: What was the most challenging part of this assignment?

**Your Answer:**

[The most challenging part of this assignment was implementing the waiting time feature correctly. It was difficult to understand how to track the time a process spends waiting in the ready queue across multiple cycles. Since processes are re-added to the queue multiple times, calculating the total waiting time required careful tracking of timestamps. I also faced some difficulty with small coding errors such as method naming and variable typos, which caused compilation issues. Additionally, understanding where exactly to update the waiting time in the scheduling loop was confusing at first. This challenge is directly related to understanding how scheduling works in operating systems. However, solving it helped me better understand process behavior and timing.]

---

## Question 3: How did you overcome the challenges you faced?

**Your Answer:**

[To overcome these challenges, I followed a step-by-step debugging approach. First, I carefully reviewed my code to identify syntax and logical errors. I used the NetBeans IDE debugging and run features to test the program multiple times and observe the output. I also referred to the assignment instructions and re-read the code structure to understand where each feature should be implemented. Breaking the problem into smaller parts helped me focus on one issue at a time. I also tested each feature separately before combining everything together. This approach made it easier to fix errors and improve the code gradually.]

---

## Question 4: How can you apply multithreading concepts in real-world applications?

**Your Answer:**

[Give specific examples from real applications you use (web browsers, games, mobile apps, etc.). Explain why threads are useful in those scenarios. Connect to what you learned in this assignment.]

---

## Additional Reflections (Optional)

### What would you like to learn more about?

[Any topics related to threading, concurrency, or operating systems that you're curious about?]

---

### How confident do you feel about multithreading concepts now?

[Rate yourself and explain: Beginner / Intermediate / Confident]

[Explain your rating - what do you understand well? What needs more practice?]

---

### Feedback on the assignment

[Any comments about the assignment? Was it helpful? Too easy/hard? Suggestions for improvement?]
