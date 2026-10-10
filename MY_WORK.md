# 📝 MY_WORK: Student Information, Development Log, Reflection & Answers

> This is the **only file** your instructor reads to grade Parts 3 and 4 (documentation and video). Everything you write here must be **in your own words**.

---

## 🛑 STOP: Read This Before You Do Anything Else

> ### 1️⃣ Read the whole `README.md` first
> The `README.md` in this repository contains the full instructions: class descriptions, feature specifications, question prompts and the video script. **If you skip it, you will lose marks.**
>
> ### 2️⃣ Understand the full code before answering any question
> Open `SchedulerSimulation.java` and read it **from top to bottom**. You must be able to explain what `Process`, `run()`, `runToCompletion()`, `addProcessToQueue()`, `Thread.start()`, `Thread.join()` and `Thread.sleep()` do **before** you write a single answer in Parts B and C. Run the program at least once and watch the output.
>
> ### 3️⃣ Commit many times, not once
> A single commit, or all commits made in the last hour, costs you **-0.5 mark**. See the [Commit Rules](#-commit-rules-mandatory) below.

**How to use this file:**
1. Fill in your **Student Information** (below) right now.
2. Follow the steps in the **Work Roadmap** in order.
3. Update the **Development Log** *every time* you work on the assignment, not at the end.
4. Do not delete any section header. Replace the `[...]` placeholders with your own text.

---

## 👤 Student Information

> ⚠️ **WARNING:** Fill this in first. Your name and ID must match the student ID you set in `SchedulerSimulation.java` (line 150) and the one you say in your video.

| Field | Your Answer |
|-------|-------------|
| **Full Name** | Reem Sultan Aldosari |
| **Student ID** | 446058146 |
| **University Email** | 446051846@std.psau.edu.sa |
| **GitHub Username** |Reem-Sultan1 |
| **Repository Link** | https://github.com/Reem-Sultan1/OS-Assignment1-Reem-Sultan |
 
---

## 🎥 Video Link

**Video Link**: [ (https://drive.google.com/file/d/1baRVIazQzLPmhzaCY7eL1Nd718Ts_DyD/view?usp=drivesdk) ]

> ⚠️ **WARNING:** The video must be **publicly accessible** ("Anyone with the link can view") on **Google Drive**, **YouTube (Unlisted or Public)** or any other cloud file-sharing system. A private, restricted or broken link counts as a **missing video (-1 mark)**.
>
> 💡 **TIP:** Open the link in a **private/incognito window** before you submit. If it asks you to log in or request access, it is not public.
>
> 📌 **NOTE:** The link goes in **this file only** (`MY_WORK.md`), **not** in `README.md`. Name your video file `StudentID_Assignment1_Demo.mp4`. It must last **2 to 3 minutes**.

---

## 🗺️ Work Roadmap (follow in this order)

| Step | What to do | Where | Marks |
|:----:|------------|-------|:-----:|
| 0 | Read `README.md`, then read and run the full code | Your IDE | – |
| 1 | Fork, rename, keep the repo **PUBLIC**, set your student ID (line 150), **commit** | GitHub + code | Part 1 (1) |
| 2 | Feature 1: Process Priority, **commit** | Code | Part 2 (0.25) |
| 3 | Feature 2: Context Switch Counter, **commit** | Code | Part 2 (0.25) |
| 4 | Feature 3: Waiting Time Tracking, **commit** | Code | Part 2 (0.5) |
| 5 | Development Log (5+ entries, different dates) | This file, Part A | Part 3 (0.5) |
| 6 | Reflection (4 questions) | This file, Part B | Part 3 (0.5) |
| 7 | Technical Answers (4 questions) | This file, Part C | Part 3 (0.5) |
| 8 | Record the video, upload it, paste the link above | Video + this file | Part 4 (1.5) |
| 9 | Final check, then submit the repo link on Blackboard | Blackboard | – |

> 💡 **TIP:** Tick each step off as you go. Do not leave the log, the reflection or the video for the last day.

---

## 🔁 Commit Rules (MANDATORY)

> ### ⚠️ MANY COMMITS ARE REQUIRED. A single bulk commit is penalized (-0.5 mark).

**Minimum: 3 meaningful commits. Aim for 6 or more.**

| # | Commit | Example message |
|:-:|--------|-----------------|
| 1 | Student ID set | `Set my student ID: 441234567` |
| 2 | Feature 1: Priority | `Feature 1: Added priority field to Process class` |
| 3 | Feature 2: Context switches | `Feature 2: Implemented context switch counter` |
| 4 | Feature 3: Waiting time | `Feature 3: Added waiting time tracking and summary table` |
| 5 | Development log entries | `Docs: Added development log entries 1-3` |
| 6 | Reflection and answers | `Docs: Completed reflection and technical answers` |
| 7 | Video link | `Docs: Added demo video link` |

**Rules:**
- ✅ **One commit per feature.** Do not put all three features in one commit.
- ✅ **Commit after each work session**, and after each part of this file.
- ✅ **Spread your commits over different dates.** Not all in one day.
- ❌ **Do not make all commits in the last hour** before the deadline.
- ❌ **No vague messages** like `done`, `update` or `final version`.

> 💡 **TIP:** Your commit history is checked and you **show it in your video** (at least 3 commits visible). Your development log dates should match your commit dates.
>
> 💡 **TIP:** **Use VS Code** (see *Recommended Development Environment* in `README.md` for the full setup). Sign in to GitHub in VS Code, then commit from the Source Control panel (Ctrl+Shift+G) → stage → write a message → Commit → Sync/Push. You can edit and commit this file the same way. **Pushing** matters: commits that are not pushed to GitHub are invisible to the instructor.

---

# Part A: Development Log (0.5 mark)

> ⚠️ **WARNING:** Minimum **5 entries**, spread over **different dates**. Five entries written on the same day, or written all at once at the end, will lose marks and look like a copy. Entry dates should be **between the start of the assignment and the deadline (October 10, 2026)**.
>
> 💡 **TIP:** Write an entry at the **end of each work session**, while you still remember what happened. It takes 5 minutes.
>
> 💡 **TIP:** Be specific. "Worked on the code" is a weak entry. "Added a `static int contextSwitches` counter and incremented it before `currentThread.start()`" is a strong one.
>
> 📌 **NOTE:** Each entry needs: date and time, what you did, details, challenges, solution, and time spent. Real challenges are fine (and expected). Do not invent fake ones.

## Example Entry (do not copy it, write your own)

### Entry 1 - [September 22, 2026, 2:30 PM]
**What I did**: Forked the repository and set up my student ID

**Details**:
- Created GitHub account with university email
- Forked the starter repository and renamed it
- Changed student ID on line 150 to my actual ID (441234567)
- Compiled and ran the program successfully
- Committed and pushed: `Set my student ID: 441234567`

**Challenges**: Had to install JDK first because `javac` wasn't recognized

**Solution**: Downloaded JDK 17 and set the PATH variable

**Time spent**: 30 minutes

---

## Your Development Log

### Entry 1 - October 8, 2026 - 2:50 AM

What I did:
Implemented Feature 1: Process Priority.

Details:
Added a priority field to the Process class, updated the constructor to receive the priority, generated a random priority from 1 to 10 for each process, added a getPriority() method, and displayed the priority when each process entered the ready queue.

Challenges:
I got a constructor error after adding the new priority parameter. I also had an issue with special characters displaying incorrectly in the VS Code terminal and had some difficulty pushing my commit to GitHub.

Solution:
I updated the Process constructor call to include the priority value and tested the program again. I enabled UTF-8 support to fix the terminal display, then verified that the feature worked correctly. I also checked that my local main branch was up to date with origin/main after pushing the commit.

Time spent:
About 2 hours.

### Entry 2 - October 9, 2026 - around 2:00 AM

What I did:
Implemented Feature 2: Context Switch Counter.

Details:
Added a static context switch counter to SchedulerSimulation. I incremented the counter each time a process started running and displayed the total number of context switches at the end of the simulation. The final output showed 15 context switches.

Challenges:
I needed to determine the correct place to increment the counter so that it counts each time the CPU starts running a process without affecting the existing Round-Robin scheduling.

Solution:
I placed the increment directly before currentThread.start(), then ran the full simulation to test it. I verified the result by checking how many times the processes needed CPU execution based on their burst times and time quantum.

Time spent:
About 45 minutes.
---

### Entry 3 - October 10, 2026 - around 2:30 AM

What I did:
Finalized and tested Feature 3: Waiting Time and Turnaround Time Tracking.

Details:
I completed the waiting time tracking for each process and added turnaround time calculation using waiting time plus burst time. I also created a final process summary table that displays the process name, burst time, waiting time, and turnaround time. I ran the full simulation again and verified that the table included all processes.

Challenges:
The main challenge was tracking the waiting time correctly because a process can return to the ready queue more than once in Round-Robin scheduling. I also needed to make sure that turnaround time was calculated correctly for every process.

Solution:
I tracked each waiting period using System.currentTimeMillis() and added the waiting periods to the total waiting time. When an unfinished process returned to the ready queue, I started a new waiting period. I calculated turnaround time as waiting time plus burst time and manually checked several rows in the final output to confirm the calculations were correct.

Time spent:
About 1 hour.

---

### Entry 4 - [Date and Time]
**What I did**:

**Details**:

**Challenges**:

**Solution**:

**Time spent**:

---

### Entry 5 - October 10, 2026 - around 3:30 AM

What I did:
Completed the remaining documentation in MY_WORK.md, including the Development Log Summary and final review of the written sections.

Details:
I reviewed my reflection and technical answers, completed the summary sections, and checked that my answers were connected to my actual code and program output. I also reviewed the assignment checklist to see what was still missing before submission.

Challenges:
The main challenge was making sure that all required sections were completed and that no placeholders were left in the file.

Solution:
I reviewed MY_WORK.md section by section and compared it with the final checklist to make sure the required documentation was complete.

Time spent:
About 30 minutes.

---

### Entry 6 - October 10, 2026 - around 11:30 PM

What I did:
Recorded and completed the final video demonstration for the assignment, uploaded it to Google Drive, and added the video link to MY_WORK.md.

Details:
In the video, I showed my public GitHub repository, explained the three implemented features, ran the program using VS Code, explained the ready queue concept using my program output, and showed my commit history. After editing the video, I uploaded it to Google Drive and changed the sharing permission to "Anyone with the link can view."

Challenges:
The main challenge was keeping the video within the required 2–3 minute duration while still showing and explaining all of the required parts.

Solution:
I prepared each section before recording, kept the explanations short and focused, and edited the final video to include all required parts within the time limit.

Time spent:
About 1 hour.
---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**: [X hours]

**Most challenging part**:

**Most interesting learning**:

**What I would do differently next time**:

---

# Part B: Reflection (0.5 mark)

> 🛑 **STOP:** Do **not** start this part until you have read the `README.md`, read the **entire** `SchedulerSimulation.java`, run it, and finished the three features.
>
> ⚠️ **WARNING:** Each answer must be **5 to 7 sentences**, in **your own words**. Copied or AI-generated answers without understanding get **0 marks for the whole assignment**. You may be asked to explain them in person.
>
> 💡 **TIP:** Mention concrete things you actually did: a method you wrote, an error you hit, a line of output you saw. Generic answers score low.
>
> 💡 **TIP:** Draft your answer in a few bullet points first, then turn them into sentences.

## Question 1: What did you learn about multithreading?

> 💡 **TIP:** Talk about thread creation (`Runnable`, `Thread.start()`), waiting with `Thread.join()`, simulating work with `Thread.sleep()`, and what surprised you.

**Your Answer:** *(5-7 sentences)*

[I learned how Java can use threads to simulate multiple processes sharing CPU time. Each Process implements Runnable, and a Thread object is created to run that process. I learned that Thread.start() begins the execution of a thread, while Thread.join() makes the main thread wait until the current thread finishes its time quantum. I also understood how Thread.sleep() can be used to simulate the amount of time a process is executing. The Round-Robin ready queue helped me understand how processes can run for a limited time and then return to the queue if they are not finished. What surprised me most was how the thread methods, ready queue, and time quantum all work together to simulate CPU scheduling.]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

[The most challenging part for me was tracking the waiting time correctly in Feature 3. A process does not always finish during its first time quantum, so it can return to the ready queue and wait again. At first, it was confusing to decide when the waiting period should start and when it should stop. I also had to make sure that the turnaround time was calculated correctly using the total waiting time and burst time. Another challenge was understanding where to place the new code without changing the original Round-Robin scheduling behavior. Testing the final summary table helped me confirm that the calculations were working correctly.]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

[I worked on the assignment in small steps instead of changing the whole program at once. After adding each feature, I ran the program and checked the terminal output before making a commit. I re-read the README whenever I was unsure about a requirement, especially for the priority range, context switches, and waiting time tracking. I also used the existing comments and structure of the starter code to decide where my changes should go. When I had errors, such as the constructor error after adding priority, I checked which method call no longer matched the updated constructor and fixed it. This approach made debugging easier because I could identify which small change caused a problem.]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

[Multithreading can be used in many applications to perform different tasks without making the whole program wait for one task to finish. For example, a web browser can use different threads to load pages, play media, and respond to user input at the same time. A music application can use one thread to play audio while another thread updates the user interface or downloads content. Games can also use separate threads for graphics, input, networking, and background calculations. This assignment showed me how threads can share processing time and how scheduling controls when each task gets a chance to run. The same idea can help real applications stay responsive while several tasks are happening at the same time.]

### Optional: What would you like to learn more about?

[Any topics related to threading or operating systems that you're curious about?]

I would like to learn more about how operating systems handle multiple threads at the same time and how synchronization prevents conflicts between them.
### Optional: How confident do you feel about multithreading concepts now?

[Beginner / Intermediate / Confident. What do you understand well? What needs more practice?]

I feel more confident with the basic multithreading concepts, especially Thread.start(), Thread.join(), and how the ready queue works. I still need more practice with more complex synchronization problems.

### Optional: Feedback on the assignment

[Any comments? Was it helpful? Too easy or hard? Suggestions?]
The assignment was challenging at first, especially because it was my first time working with GitHub in this way, but it helped me understand multithreading and Round-Robin scheduling better through practical implementation.
---

# Part C: Technical Answers (0.5 mark)

> 🛑 **STOP:** You cannot answer these questions without understanding the code. Re-read `SchedulerSimulation.java` and **run it** first. Your answers must reference **your own code and your own output** (your student ID makes your output unique).
>
> ⚠️ **WARNING:** Each answer must be **3 to 5 sentences**, with specific examples from your code or output. Use correct terms: thread, process, time quantum, ready queue, context switch, burst time.
>
> 💡 **TIP:** Keep your program output in a text file or screenshot so you can copy real snippets for Question 2.

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes? Mention at least **TWO** specific differences (e.g., memory sharing, creation overhead, communication speed), and reference relevant parts of `SchedulerSimulation.java`.

> 💡 **TIP:** Note that the class named `Process` in our code is a *simulated* process, and it is run by a real Java *thread*. Explain that distinction and point to the `new Thread(process)` line in `addProcessToQueue()`.

**Your Answer:** *(3-5 sentences)*

[A process is an independent program with its own memory space, while a thread is a smaller unit of execution that runs inside a process and can share memory with other threads. Threads are usually faster to create and have less overhead than creating separate operating system processes, and they can communicate more easily through shared objects. In this assignment, the Process class represents a simulated process, but each simulated process is actually executed using a real Java Thread. This can be seen in addProcessToQueue(), where the code creates a thread using new Thread(process), allowing the scheduler to manage the processes using the shared ready queue and process map.]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

[In my program run, I used P4 as an example because its burst time was 9060 ms while the time quantum was 5000 ms. P4 could not finish during its first CPU turn, so it was added back to the ready queue once. It then received another turn and completed its remaining execution time. This shows how Round-Robin scheduling gives unfinished processes another chance to run while allowing the other processes in the queue to execute.]

Example from my output:
```[  ▶ P4 executing quantum [5000ms] 
  ⚡ Quantum progress: [███████████████] 100%
  ⏸ P4 completed quantum 5000ms │ Overall progress: [███████████░░░░░░░░░] 55%
     Remaining time: 4060ms
  ↻ P4 yields CPU for context switch

  ➕ P4 added to ready queue | Priority: 3 │ Burst time: 9060ms
┌─ Ready Queue ─────────────────────────────────────────────────────────────────
│ [P6 → P7 → P8 → P9 → P10 → P3 → P4]
```

**Explanation of example:**
[In my program run, P4 had a burst time of 9060 ms while the time quantum was 5000 ms. Because P4 could not finish within its first time quantum, it was re-queued once and later received another CPU turn to complete its remaining execution time. This is how Round-Robin scheduling handles processes that need more than one time quantum. Re-queuing is important for fairness because it allows the other processes in the ready queue to receive CPU time instead of allowing one long process to use the CPU continuously.

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: [When is P1 in the New state?]
P1's thread is in the New state when it is created in addProcessToQueue() using new Thread(process) but has not started yet.
2. **Runnable**: [When does P1 become Runnable?]
P1 becomes Runnable when currentThread.start() is called, making the thread ready to be scheduled by the CPU.
3. **Running**: [When is P1 Running?]
 P1 is Running when its thread is selected to execute and the run() method begins processing its time quantum
4. **Waiting**: [When and why would a thread be Waiting?]
 During Thread.sleep(runTime), P1's thread temporarily waits while the execution time is simulated; separately, the main thread waits for P1 to finish by calling currentThread.join().
5. **Terminated**: [When is P1 Terminated?]
 P1's thread is Terminated when its run() method finishes. If the simulated process still has remaining time, it is re-queued and a new Thread is created for its next CPU turn.
## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [CPU Scheduling for Multiple Running Programs]

**Description**:
[Describe the real-world scenario.]
A user may have several programs running at the same time, such as a web browser, VS Code, and a music player. The operating system must schedule the processes or threads belonging to these programs so they can share CPU time instead of allowing one task to use the CPU continuously.
**Why Round-Robin works well here**:
[Fairness, responsiveness, predictability?]
Round-Robin gives each ready process or thread a limited time quantum before the CPU switches to another one. This improves fairness because every ready task gets a chance to run, responsiveness because one long-running task cannot block the others for too long, and predictability because tasks receive CPU time in repeated turns. The time quantum and context switches in this scenario are similar to the scheduling behavior in my simulation.
### Example 2: [Web Server Handling Multiple User Requests]

**Description**:
[Describe the real-world scenario or application.]
A web server may receive requests from many users at the same time, such as opening pages, submitting forms, or requesting data. These requests can be handled by different worker threads, and the system needs to give each active request a chance to make progress.
**Why Round-Robin works well here**:
[Fairness, responsiveness, predictability?]
Round-Robin can schedule the active worker threads in turns so that one request does not dominate CPU time. This improves fairness between requests, keeps the server responsive to different users, and makes CPU access more predictable because each ready thread gets repeated opportunities to run. This is similar to my simulation, where processes use a time quantum and the CPU performs context switches between them.
## Summary

**Key concepts I understood through these questions:**
1. The difference between a process and a thread.
2.How Round-Robin scheduling uses a ready queue, time quantum, and context switches.
3.The main stages of the thread lifecycle and how Java thread methods affect them.

**Concepts I need to study more:**
1. Thread synchronization and safe sharing of data between threads.
2.More advanced CPU scheduling algorithms and how they compare with Round-Robin.

---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [ ] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [ ] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [ ] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [ ] Student ID is set in `SchedulerSimulation.java` (line 150)
- [ ] Code compiles and runs with no errors
- [ ] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [ ] Each feature has clear comments

**Commits**
- [ ] **At least 3 meaningful commits, ideally 6 or more**
- [ ] **One commit per feature**
- [ ] Commits are spread over **different dates** (not all in the last hour)
- [ ] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [ ] Full name and student ID filled in at the top
- [ ] Development log has **5+ entries** on different dates
- [ ] Reflection: 4 questions, 5-7 sentences each
- [ ] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [ ] No `[...]` placeholders left
- [ ] No section headers deleted

**Video**
- [ ] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [ ] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [ ] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [ ] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.
