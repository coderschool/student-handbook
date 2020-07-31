# Technical Interviewing Guide

This post is meant to help our CoderSchool graduates succeed their technical job interviews. This post will hopefully address some of the commonly asked questions. This post covers two questions:

* _**What are the most technical job interviews like?**_
* _**How should I prepare for them?**_

### The 3 types of technical Interviews

1. **The programming interview:** algorithms, data structures, coding
2. **The “what you’ve done interview”:** you and your projects
3. **The domain-specific interview:** quizzed about a tech stack you claim to know

We’ll explain these in more depth below, adding details on how to prepare for each category. Note that not every interview falls precisely into one of the three categories, and some interviews are a mix of multiple categories.

### Prep before the interview

To leave a good impression on employers, make sure you are well-prepared for it before actually attending the interview

1. **Do Employer Research:** The biggest mistake that people normally make in a job interview, according to recruiters is knowing little to nothing about the company with which you are interviewing! So make sure you do:
   * Research about the company, their business, clients, their technologies... This can be gound through GG, Linked in , website, fanpage,...
   * Analyze the Job Description \(JD\) to well understand what the job is about and their requirements.
2. **Finish your projects,** especially the final project, and present it to interviewers
3. **Practices your answers**: The good way is to stand in front of minor, practice and film yourself =&gt; Re-watch it, and correct yourself. The top questions that you should practice are:
   * Introduce yourself: your education, experience, technical expertise?
   * Walkthrough your projects
   * Your strengths & weaknesses
   * Technical questions
   * What do you know about the company? What's their mission? Why would you like to work here?
   * Expected Salary? and Why you deserve it?
4. **Dress nicely**
5. **Bring the laptop** to showcase your projects
6. **Be there 10 minutes** before the interview. On-time means late!

### In the interview

1. **Create a Good First Impression**: Interviewers will size you up in the first 30 seconds of your interview. Make sure that you create a good first impression by being aware of:  
   * Good eye contact  
   * Smile  
   * Strong, dry handshake  
   * Clear introduction 
   * **Be Confident and Positive!!!**
2. **Begining the interview by Introducing about Yourself**

* Keep it succinct! This should be a minute or two at most. Hit the important points about your technical skills and experience. 

{% hint style="info" %}
Have a well-prepared intro that highlights one project that you are most proud of: share about:

* where you got that idea from? 
* What was the project?
* What was the scope of the project? \(i.e., how much time, how big was it\)
* What was your role in the project?
* What did you learn?
* What were some of the challenges in the project?

This will help to narrow down the scope of technical questions that interviewers may ask. They will ask mainly about your projects \(which you already know well about\) instead of asking a tons of technical areas that they used and you may no liitle to nothing about.
{% endhint %}

Additionally, be prepared for questions that **highlight your interest in the company**. For example, why you want to work here, what you like about the product, a feature or improvement you might like to work on during a hackathon.

### 1: The programming interview <a id="1-The-programming-interview"></a>

The **programming interview** is the most common type of interview, especially if you’re not interviewing for a specific team. This is how most people envision computer science interviews: you’re asked one or more programming questions, and you implement solutions on a collaborative editor like [CodeShare](https://codeshare.io/) or [Collabedit](http://collabedit.com/).

These interviews can be further divided into two topics:

1. Questions involving loops, lists, or strings \(easier\)
2. Questions involving specific data structures \(harder\)

The first category is easier, and it includes questions like: _Remove duplicates from a list_ or _Generate all of the permutations of a string_.

The second category trickier, and sometimes the question will be hard or near impossible if you don’t know about a specific data structure or algorithm. For example, if you’ve never done breadth-first tree traversal, and you’re asked: _Print the values in this tree level-by-level_, the question will be much harder.

In some interviews, at the end of certain questions, you will be asked to discuss the [Big-O complexity](https://www.interviewcake.com/big-o-notation-time-and-space-complexity) of your implementation.

#### Steps in a Coding Interview <a id="Steps-in-a-Coding-Interview"></a>

When given a coding problem in an interview, whether on a whiteboard or on a hackpad, you’ll generally want to resist the temptation to jump straight into code, and instead solve the problem collaboratively with the interviewer roughly following these steps:

* **Step 1: Ask Clarifying Questions** - Ask the interviewer questions to better understand the problem.
* **Step 2: High-level Discussion** - Explain the ideas you have in concept first without using code to avoid wasting time writing code on a solution that won’t work.
* **Step 3: Choose an Approach and Confirm Inputs and Outputs** - Pick a potential approach from above and then start documenting the method definition and several example inputs and outputs.
* **Step 4: Start Writing Code and Thinking Aloud** - Start writing the body of your solution in code iteratively and talking aloud to the interviewer as you do.
* **Step 5: Test Your Solution** - Walk through your code line by line using several examples of inputs, and verifying for each case that the outputs are what you expect.
* **Step 6: Discuss Complexity** - If there is time at the end, check to see if your interviewer wants you to discuss [space and/or time complexity](https://www.interviewcake.com/article/java/big-o-notation-time-and-space-complexity) of your solution.

Check out [this more extended step-by-step overview](https://app.gitbook.com/@coderschool/s/coderschool-student-handbook/~/drafts/-MDXvVfqEkIFrITGq7Av/anatomy-of-an-interview) or this [video by an ex-Googler for a walkthrough](https://youtu.be/uQdy914JRKQ) for more details. You can also read [this guide by an ex-Facebooker](https://hackmd.io/@nesquena/ex-fb-interviewer-tips).

#### Topic Overview <a id="Topic-Overview"></a>

The technical interviews tend to involve coding questions of the following data structure and algorithm topics:

* Complexity Analysis: [Big-O Notation](https://www.interviewcake.com/big-o-notation-time-and-space-complexity)
* Core data structures: [Hash Tables](https://www.interviewcake.com/concept/hash-map), [Arrays](https://www.interviewcake.com/concept/array), [Linked Lists](https://www.interviewcake.com/concept/linked-list), [Stacks](https://www.interviewcake.com/concept/stack)/[Queues](https://www.interviewcake.com/concept/queue)
* Searches: [Binary Search](https://www.interviewcake.com/concept/binary-search), [Breadth-First Search](https://www.interviewcake.com/concept/bfs)/[Depth-First Search](https://www.interviewcake.com/concept/dfs)
* Graph data structures: [Binary Trees](https://www.interviewcake.com/concept/binary-tree), [Graphs](https://www.interviewcake.com/concept/graph)

In particular, depth-and breadth-first search \(DFS and BFS, respectively\) can be extremely popular questions so be sure to practice them. You might also encounter harder topics such as these but you will tend to see them less frequently for internship interviews:

* Sorting: Merge Sort and Quick Sort
* Recursion and Combinatorial
* [Dynamic Programming](https://www.interviewcake.com/concept/overlapping-subproblems)
* [Greedy Algorithms](https://www.interviewcake.com/concept/greedy)
* Object-Oriented Design \(OOP\)

If you are looking for introductions to these concepts that are fun and accessible, check out [BaseCS](https://hackmd.io/s/HJ9YQDE2b) and the [related podcast](https://www.codenewbie.org/basecs). You can also read through this [algorithms tutorial series](https://adrianmejia.com/blog/2018/04/04/how-you-can-change-the-world-learning-data-structures-algorithms-free-online-course-tutorial/). For more resources, check out our [data structures and algorithms links](https://hackmd.io/s/rkg8GyDiQ) guide.

#### Checklist <a id="Checklist"></a>

Before walking in for a technical interview, **you need to study and practice for interviews**. Unless you do algorithmic challenges on a regular basis, it’s necessary to read and practice problems.

* **Use Leetcode to Practice**: To practice coding problems, check out [Leetcode](https://leetcode.com/). Focus on these topics: string manipulation, linked lists, doubly linked lists, hash tables, trees, queues, stacks, depth-first search, breadth-first-search, basic graphs, basic complexity.
* **Check Glassdoor**: Many companies have interview questions on [Glassdoor](https://www.glassdoor.com/index.htm). Your goal isn’t to study the interview questions in advance, but you can get a good idea of the general difficulty of the programming questions.
* **Practice talking while you solve problems**: When you feel a bit more prepared, you can do a mock interview to see where you’re standing. Check out [Mock Interviews](http://www.mock-interviews.com/) or [Pramp](https://www.pramp.com/). You will receive feedback afterward with details about what went well and what you need to improve, which will definitely help you with upcoming interviews.

#### Coding Interview Tips <a id="Coding-Interview-Tips"></a>

* While working through a problem, it’s natural to need some time to think. Feel free to take a breath and a few moments to think before verbalizing your thoughts to reduce the confusion of the interviewer. At the same time, try to avoid staying quiet for long periods of time, it’s important to keep the interviewer “in your loop” and talk them through your approach. This can often allow them to help you along and provide guidance as well.
* Pick a language you feel most comfortable with when interviewing and use that whenever possible. Make sure you have a solid understanding of data structures and algorithms and their respective APIs in that language. Most interviewers will have no problem letting you look up \(or telling you\) an API call, but keep in mind that time is a precious resource! Knowing that stuff beforehand gives you more time and headspace to focus on the problem at hand.
* Be sure to ask any questions you have about edge cases, assumptions, etc directly to the interviewer. You can double-check to confirm details about the problem, if you have to deal with bad or invalid input, etc. Questions are good and they show the interviewer that you consider all aspects of the problem instead of just diving in head-first.

### 2: The “what you’ve done” interview <a id="2-The-&#x201C;what-you&#x2019;ve-done&#x201D;-interview"></a>

The **“what you’ve done” interview** is a non-technical, pleasant conversation with your interviewer, where you get the opportunity to talk about your resume and projects. This type of interview was more common in small and medium-sized companies.

These interviews are an opportunity to pitch yourself as a passionate developer. To impress the interviewer, please talk about your final project in an impressive way!

During these types of interviews, keep your answers open and honest and don’t try to mislead or make up stuff that you don’t know. You aren’t expected to have a holistic working knowledge of every part of a large project.

### 3: The domain-specific interview <a id="3-The-domain-specific-interview"></a>

The domain-specific interview tests your knowledge about a specific language, framework or platform that you claim to know on your resume. This interview often shows up if you’ve been placed to interview with a specific team \(e.g., iOS Safari team at Apple, YUI team at Yahoo\).

The interviewers expect you to show knowledge through answers to quiz questions, discussion of relevant projects, and opinions on language or framework features.

#### Checklist <a id="Checklist2"></a>

If you are placed to interview with a team that uses a specific language \(or framework\), you should prepare for the following questions:

> What makes {language} different from other languages?

> If you had to change something in {language}, what would you change?

> Tell me about a technical challenge that you had when you were working on a project in {language}.

> Tell me about {feature} in {language} \(i.e Tell me about closures in JavaScript\)

### Ending the Interview <a id="Ending-the-Interview"></a>

Even when the interview runs over the allocated time, your interviewer will ask:

> Do you have any questions for me?

Treating this as an opportunity for a conversation can make things easier. This is a chance to connect on a personal level with the interviewer and show him your hunger to his team, his company.

If the interviewer hadn’t described himself or herself yet, the first thing you can ask is:

> Can you tell me more about what you do?

Let the conversation flow from there. Make sure you have some questions prepared to ask the engineer. Think about questions that demonstrate a curiosity in working for the company. Some examples:

* Can you share further about the scope of this position please?
* How about the current team structure?
* What are the technologies that you have been using?
* Asking what the Engineer enjoys most about working at the company.
* Asking about the company’s vision, where do they see the company in a year from now.

If there’s not much to follow up on, you can ask about how they test their products or what they enjoy about working there. There’s [a very good list](http://programmers.stackexchange.com/questions/16436/do-you-have-any-questions-for-us-in-an-interview) on Programmers Stack Exchange, although not all of them are suitable for potential interns to ask.

### Practical Coding Interview Tips <a id="Practical-Coding-Interview-Tips"></a>

#### Ex-Googler Interviewing Tips <a id="Ex-Googler-Interviewing-Tips"></a>

These tips are for focused around top companies like Google or Facebook, check these out to understand more about the purpose of interviews, and what to make sure you try and do during the interview:

* Your interviewers are trying to understand what it feels like to work with you on a daily basis. An interview question is a method in achieving that, it is not necessarily always there to specifically measure your skills on a topic but a tool to understand the depth of your thinking.
* Before the interview starts, ask them what they want to get out of this interview. Good interviewers should already have a plan and a set of expectations. Ask them what you should do. Don’t start coding yet. Ask them you should produce. Discussion, diagrams, pseudo code, code?
* Next, start to breakdown the question. List whatever questions you think it is important to solve this question, ask your edge cases. Get to a point where you are discussing about pros/cons of the solutions. These steps are critical. Don’t just start coding. Have a consensus first.
* Your interviewer will try to give you hints. Don’t ignore them because you are too confident about your solution. This is not a intelligence contest. Also, don’t panic if a hint doesn’t make sense. Ask what interview’s perspective is that they gave that hint.
* Talk, talk, talk as you are doing your thing. Talk about even the most obvious steps. Ask about testing, talk about testing cases if testing discussion is expected. Discuss what you’d fix to iterate your solution if you realized you are missing something.
* Don’t get freaked out if the interviewer jumps to a different question. Sometimes, they think they got enough of what they have been looking for from a question and will do something else. Don’t try to overdo a solution if interviewer think it is good enough.
* Don’t freak out just because your interviewer is taking too many notes. They need to provide evidence to the hiring committee and they want to remember as many signals as possible. Make sure you are clearly communicating your new ideas if you are iterating on the initial ones.
* At any interview regardless it is at Google or not, don’t see your interviewer as someone who has the full authority but some who you are already working with. Try to have a feel how productive it will feel in real life. Remember, interviews shouldn’t be a monologue.

These tips were sourced from [this tweet stream](https://threader.app/thread/1058433116002381824) and originally authored by [@JBD](https://rakyll.org/) from Google.

### Ex-Facebook Interviewing Tips <a id="Ex-Facebook-Interviewing-Tips"></a>

Check out [this post by an ex-Facebook interview](https://hackmd.io/@nesquena/ex-fb-interviewer-tips) on his recommendations for how to interview effectively, to briefly summarize his points:

* Make sure as the person being interviewed to properly lead the interviewer through the solution following a general set of steps.
* **Most common mistakes in an interview:** 1\) Making incorrect assumptions, 2\) Not asking questions, 3\) Not using the whiteboard to visualize or pseudocode, 4\) Not talking out loud to share your thought process, 5\) Writing no tests or poor tests
* **Important steps to an interview:** 1\) Ask clarifying questions, 2\) Analyze various solutions and tradeoffs, 3\) Plan solution with pseudocode, 4\) Implement solution, 5\) Test
* **When you get stuck:** 1\) Try to match this problem to previous similar problems 2\) Align the weakness of a solution to the strength of a data structure, 3\) Look for the twist that makes this easier to solve, 4\) Don’t be afraid to ask for a hint

### Summary of Important Points 

1. Research the employer & Analyze the JD
2. Get your projects loaded all on Github. Especially pay much attention to your final project
3. Practice your answers 
4. Practice answer to common technical questions 
5. Creating a good first impression
6. Be confident and positive!!  

