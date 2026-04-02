# Development Log

## Instructions
Document your development process as you work on the assignment. Add entries showing:
- What you worked on
- Problems you encountered
- How you solved them
- Time spent

**Requirements**: Minimum 5 entries showing progression over time.

---

## Example Entry Format:

### Entry 1 - [April 1, 2026, 2:30 PM]
**What I did**: Forked the repository and set up my student ID

**Details**: 
- Created GitHub account with university email
- Forked the starter repository
- Changed student ID on line 92 to my actual ID (441234567)
- Compiled and ran the program successfully

**Challenges**: Had to install JDK first because javac wasn't recognized

**Solution**: Downloaded JDK 17 from Oracle website and set PATH variable

**Time spent**: 30 minutes

---

## Your Development Log:

### Entry 1 - [March 28,2026 ,5:00 PM]
**What I did**: Set up the project and prepared the environment

**Details**: - Created a GitHub account using my university email
- Forked the starter repository
- Renamed the repository to include my name
- Opened the project using NetBeans IDE (as allowed by the instructor)
- Added my student ID in SchedulerSimulation.java
- Compiled and ran the program successfully inside NetBeans

**Challenges**: 
Initially, I was unsure how to run the project in NetBeans and configure Java properly
**Solution**: 
Configured JDK inside NetBeans and used the built-in run feature to execute the program
**Time spent**: 
48 minutes
---

### Entry 2 - [March 29, 2026, 10:30 AM]
**What I did**: 
Implemented Feature 1 (Process Priority)
**Details**: 
- Added priority field to Process class (1–5)
- Modified constructor to include priority
- Generated random priority for each process
- Displayed priority when process enters the ready queue
**Challenges**: 
Understanding where to integrate the priority field without breaking existing logic
**Solution**: 
Carefully followed the structure of the Process class and added the field with minimal changes
**Time spent**: 
1 hour
---

### Entry 3 - [March 30, 2026 ,3:02 PM]
**What I did**: 
Implemented Feature 2 (Context Switch Counter)
**Details**: 
- Created a static variable to count context switches
- Incremented the counter each time a process starts execution
- Displayed total context switches at the end of simulation
**Challenges**: 
Determining the correct place to increment the counter
**Solution**: 
Added it inside the scheduler loop before starting each thread
**Time spent**: 
45 minutes
---

### Entry 4 - [March 31, 2026, 7:00 PM]
**What I did**: 
Implemented Feature 3 (Waiting Time Tracking)
**Details**: 
- Added fields: creationTime, totalWaitingTime, lastReadyTime
- Calculated waiting time using System.currentTimeMillis()
- Updated waiting time before each execution
- Stored completed processes in a list
**Challenges**: 
Understanding how to correctly calculate waiting time across multiple queue entries
**Solution**: 
Tracked when process enters and leaves the queue using timestamps
**Time spent**: 
1.5 hours
---

### Entry 5 - [April 1, 2026, 3:00 PM]
**What I did**: 
Created summary table for waiting time
**Details**: 
- Displayed process name, burst time, priority, and waiting time
- Calculated average waiting time
- Formatted output into a clean table
**Challenges**: 
Formatting output neatly and calculating average correctly
**Solution**: 
Used String.format() and tested multiple outputs
**Time spent**: 
1 hours
---

### Entry 6 - [April 2, 2026 ,6:00 PM]
**What I did**: 
Testing and debugging the program
**Details**: 
- Fixed method naming error (updateWaitingTime)
- Fixed typo in processQueue
- Ensured no runtime errors
- Verified output correctness
**Challenges**: 
Debugging small syntax errors that caused compilation failure
**Solution**: 
Carefully reviewed code and tested multiple runs
**Time spent**: 
1 hour
---

## Summary

**Total time spent on assignment**: [~6 hours]

**Most challenging part**: Tracking and calculating waiting time accurately for each process

**Most interesting learning**: Understanding how threads are scheduled using Round-Robin and how context switching works

**What I would do differently next time**: Start earlier and test each feature immediately after implementation to avoid debugging multiple issues at once
