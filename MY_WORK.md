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
| **Full Name** | [yazeed althobaiti] |
| **Student ID** | [444052147] |
| **University Email** | 444052147@std.psau.edu.sa |
| **GitHub Username** | [Yazeed-Althobaiti] |
| **Repository Link** | [https://github.com/Yazeed-Althobaiti/OS-Assignment1-yazeed-Althobaiti] |
 
---

## 🎥 Video Link

**Video Link**: [https://drive.google.com/file/d/1EdVH5sQqPxMyKpBjubKXtF7ganv0LCdf/view?usp=drive_link]

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

### Entry 1 - [October 9, 2026, around 1:00 PM]
**What I did**: create account on githup and start to be ready

**Details**:
set my student id in the code
download the vs and git and java
ran the code in vs to make sure it work

**Challenges**:
I needed to make sure the project, Java, and Git repository were set up correctly before starting the features.


**Solution**:
I checked the tools from the terminal, ran the program in VS Code, and verified the repository before continuing.

**Time spent**: About 3 hours including setup and starting Feature 1

---

### Entry 2 - [October 9, 2026, around 6:00 PM]

**What I did**: I worked on Feature 1 and added priority to the processes

**Details**:
I made the priority random from 1 to 10
I showed the priority when the process enters the ready queue
I ran the code to make sure it works


**Challenges**:
 I was not sure if the priority should change the order of the processes.


**Solution**:
 checked the requirement and kept the Round Robin order the same


**Time spent**: About 2 hours

---

### Entry 3 - [October 9, 2026, around 8:00 PM]

**What I did**: I worked on Feature 2 and added the context switch counter

**Details**:
I added a static counter for the context switches
I compared the previous process with the current process
I printed the total context switches at the end
I saved the previous process name


**Challenges**:
I was not sure when I should count a context switch.

**Solution**: 
I counted it when the CPU changed from one process to a different process , I did not count the first process.

**Time spent**: About 1 hour

---

### Entry 4 - [October 9, 2026, around 9:00 PM]

**What I did**: I worked on Feature 3 and added the waiting time.

**Details**:
I used System.currentTimeMillis() to track the time
I recorded when the process enters the ready queue
I calculated the waiting time for each process
I added a summary table at the end

**Challenges**:
was not sure how to calculate the waiting time because a process can enter the ready queue more than one time


**Solution**:
I recorded the time every time the process entered the ready queue and added the waiting time when the process started running

**Time spent**: About 1 hour and 30 minutes

---
4
### Entry 5 - [October 10, 2026, around 1:00 PM]
**What I did**: I worked on the MY_WORK.md file and documented my work

**Details**:
I added my student information
I wrote the development log for the three features
I reviewed what I did in each feature

**Challenges**:
 needed to remember the steps and problems I had while working on the assignment


**Solution**:
I reviewed my code and commit history to remember what I did in each feature.

**Time spent**:
About 3 hours
---

### Entry 6 - [Optional - Date and Time]
**What I did**:

**Details**:

**Challenges**:

**Solution**:

**Time spent**:

---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**: [About 10 hours and 30 minutes]

**Most challenging part**:
The coding and understanding where to add the new features

**Most interesting learning**:
Learning how Round-Robin gives each process time to use the CPU


**What I would do differently next time**:
I would read the code and requirements more carefully before starting

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

[
    I discovered that the processes are executed through threads
    Thread.start() starts the thread and runs the process
    Thread.join() makes the program wait until the current thread finishes
    I also discovered that the CPU running time may be simulated using Thread.sleep()
    A process returns to the ready queue if there is still time left
    One thing I did not know before is that we need a new thread when the process goes back to the queue




]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

[
    The most challenging part for me was the coding
    The scheduler code was first a little confusing
    I had to understand where to add each feature without changing the original code
    The waiting time feature was harder because the process can enter the ready queue more than one time
    I also had to make sure the old features still worked after adding new code


]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

[
I tried to do the challenges step by step
I read the requirements again when I was not sure what to do
I added small parts of the code instead of adding everything at once
After each feature, I ran the program to check if it was working correctly
I also checked the output to make sure the new feature worked without breaking the old features



]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

[

Multithreading can be useful in many real applications
For example a web browser can use different threads for different tasks
One thread can run a page while another thread plays a video
This helps the application do more than one task without stopping everything
This assignment helped me understand how threads can be used to manage different tasks

]

### Optional: What would you like to learn more about?

[Any topics related to threading or operating systems that you're curious about?]

### Optional: How confident do you feel about multithreading concepts now?

[Beginner / Intermediate / Confident. What do you understand well? What needs more practice?]

### Optional: Feedback on the assignment

[Any comments? Was it helpful? Too easy or hard? Suggestions?]

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

[
     A process is a task like P1 or P2, and it is run by a thread
     The Process class stores information like burst time, priority, and remaining time
     I used new Thread(process) to create a thread that runs the process
     A process has its own memory, but threads in the same program can share memory and threads are faster to create

]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

[

    If a process does not finish in its time quantum, it goes back to the ready queue
    In my output, P12 had a burst time of 12463ms and the time quantum was 5000ms
    P12 was re-queued two times before it finished
T   his gives the other processes a chance to run and makes the scheduling fair

]

Example from my output:
```
[
    
P12 executing quantum [5000ms] 
  ? Quantum progress: [███████████████] 100%
  ? P12 completed quantum 5000ms │ Overall progress: [████████░░░░░░░░░░░░] 40%
     Remaining time: 7463ms
  ? P12 yields CPU for context switch

  ? P12 added to ready queue │ Burst time: 12463ms │ Priority: 7


  
  ? P12 executing quantum [5000ms] 
  ? Quantum progress: [███████████████] 100%
  ? P12 completed quantum 5000ms │ Overall progress: [████████████████░░░░] 80%
     Remaining time: 2463ms
  ? P12 yields CPU for context switch

  ? P12 added to ready queue │ Burst time: 12463ms │ Priority: 7



  P12 executing quantum [2463ms] 
  ? Quantum progress: [███████████████] 100%
  ? P12 completed quantum 2463ms │ Overall progress: [████████████████████] 100%
     Remaining time: 0ms
  ? P12 finished execution!



]
```

**Explanation of example:**
[
    
    
    P12 did not finish in the first time quantum
    so it went back to the ready queue
    It was re-queued two times because it still had remaining time
    In the last turn, P12 ran for the remaining 2463ms and finished




]

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: P1 is in the New state when a new thread is created

2. **Runnable**: P1 becomes Runnable when Thread.start() is called and it is ready to run

3. **Running**: P1 is Running when its run() method is executing

4. **Waiting**: P1's thread waits for a short time when Thread.sleep() is called, while the main thread waits for P1 using join()

5. **Terminated**: P1's thread is Terminated when the run() method finishes

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [CPU Scheduling]

**Description**:
[

The operating system can use Round-Robin to share CPU time between running programs
Each program gets a time quantum to use the CPU
When the time ends, the CPU can switch to another program

]

**Why Round-Robin works well here**:
[
    
Round-Robin gives each program a chance to use the CPU
This makes the system fair and keeps other programs not  waiting too long

]

### Example 2: [Web Browser]

**Description**:
[

    A web browser can have different tasks running at the same time
    For example one task can load a page while another task plays a video
    Each task can get time to run before switching to another task

]

**Why Round-Robin works well here**:
[
    
    Round-Robin gives each task a chance to run
    The context switch moves between the tasks so one task does not take all the CPU time
    This helps the browser stay responsive

]

## Summary

**Key concepts I understood through these questions:**
1. The difference between a process and a thread
2. How Round-Robin uses the ready queue and time quantum
3. How context switching works between processes

**Concepts I need to study more:**
1. Context switching
2. Time quantum

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
