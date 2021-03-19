# Introduction to Machine Learning 2

University of Amsterdam / Programming Lab / 50822ITM6Y

## Syllabus<br><small>Spring 2021</small>

This course is the continuation of Introduction to Machine Learning 1. In ML1
you've learned about some of the basic algorithms in machine learning and to
what types of problems they can be applied. For ML2 we'll be focussing more on
combining smaller models as component into bigger and more complex models, most
notably neural networks.

## Staff

Tim Doolan (coordinator)

Wouter Vrielink (teacher)

You can reach us at <minorai@mprog.nl> for any practical matters or other
questions.

## Deadlines and schedules

The deadlines for each module can be found on the overview page of that module.

We've found that it can be difficult for students to plan when to work on what
part of the material, especially with two complete new courses, that together
require a full-time time investment. Being unfamiliar with a subject makes it a
lot harder to estimate how long something might take, and working from home
might also make structuring your work more difficult. To help with all of this,
we've made a day-to-day schedule for each module, which indicates what elements
should be completed each day.

### Extension policy

If there are circumstances that require you to have a deadline extension, you
must request this at least 1 hour *before* the deadline expires. The staff will
then determine if extension is permissible and make an alternative schedule
with you. Submissions after the deadline without prior permission will not be
accepted. To avoid late extension requests, it is strongly suggested that you
consult the module's schedule regularly to see if you are on track for the
module, and if not, to contact the staff early. For discussing your module
progress or requesting an extension, you can reach us at <minorai@mprog.nl>.

*Note:* While it is of course possible for circumstances to arise that require
you to need an extension, consecutive extension requests are usually not
granted. If you are given an extension, we will also discuss an alternative
schedule, which is intended to get you back on track for the regular schedule.
If the situation is such that this is not feasible, then an alternative
schedule will be constructed in which you follow fewer courses over a longer
period of time. Due to the content of each module being heavily dependent on
the content of the previous modules, skipping or only partially completing
modules is *not* possible in this curriculum.

## Morning meetings

An essential part of working completely online will be to get to know your
fellow students. For this purpose we'll host morning meetings every day at
**09:00** for all of you. Here you'll divide into smaller groups of 4 or 5
students, and have a cup of coffee and start the day together. The meeting can
be joined at [Wonder.me](https://www.wonder.me/r?id=c6cdcb4d-7901-44dc-9b9f-fe90898c22a5).

These meetings will also be useful to discuss your progress and what you're
planning to do for the day. If, for example, you find you're stuck on the same
part of an assignment as other students, you can then decide to take a look at
your approach for a problem together. We encourage you to discuss approaches to
problems together, as this is an effective way to learn, but this can only
occur if you know each other and what you are working on. Facilitating this is
primary purpose of these meetings.

*Note:* This means working together on analysis and approach of a problem, not
directly sharing code with each other! For a complete description of what it
means to do your own work and forms of collaboration are reasonable and
unreasonable, see the end of this document.

## Asking questions

If you have any question about the material, there are several ways to get
assistance. An import part of following this course, is to understand all the
different ways you can get help and when to use which one.

### Ed Q&A Forum

The first place you should try and ask your question is on the 
[Ed forum](https://edstem.org/us/courses/4208/discussion/). There the course
staff or your fellow students will answer any specific questions you might 
have.

If you have general question about the material or the assignment, please make
it a public question, so other students can also read the answer. Private
questions are intended for questions that share specific portions of a
solution, which you obviously shouldn't do publicly. Further details on using
*Ed* can be found in the pinned "Welcome" post on the forum.

### Seminars

There will be several planned seminars for each module, which will be listed as
part of the weekly schedules, usually starting at **11:00** those days. The
seminars serve as a central place to discuss material with all students, though
the exact form will differ from topic to topic. The topic for each seminar will
be listed together with the Zoom link for that seminar.

While these seminars might cover some additional material, they also serve as a
Q&A about assignments or topics from the theory. Attendance is not mandatory,
but is definitely recommended, even if you've already completed that part of an
assignment, as completing does not always mean full understanding too.

*Note:* Attendance for each seminar is still kept track of and will impact your
place in the *QuestionQueue* (see next section). If you did not attend the
seminars, then you might have to wait longer to have your individual question
answered. Answering questions centrally in a seminar is much more efficient
than answering individual videocalls, so this measure serves specifically to
discourage students who choose to not attend seminars, but still ask individual
questions, which might have already been answered during those same seminars.

### Videocall on Discord: QuestionQueue

Sometimes it is hard to phrase your specific question precisely in writing on
the forum, especially when you are just starting out with programming. For some
problems it is also easier if the staff can see your screen and ask you
questions. For these cases we also offer the option of videocalls on Discord.
Requests for videocalls are managed using the the *QuestionQueue* bot.

The question queue will open every weekday starting at **9:30**. Most days
the queue will be open until *12:30*, but if there is a seminar that day, the
queue closes before the seminar starts at *11:00*.

To use the *QuestionQueue*, send a direct message to the bot on Discord, a
starting with `!ask`, followed by your question, e.g.

    !ask My water.py gives an error I don't understand.

The staff will take videocalls from the queue in the order they are asked, and
you will be notified by the *QuestionQueue* bot when it is your turn.

### Email the staff

If you have personal matters to discuss or other questions that do not fit any
of the formats above, you can email the course staff at <minorai@mprog.nl>

## Passing the course

Your final grade for this course will a weighted average of all submitted
assignments and your final exam grade. For the assignments there will be
programming and writing portions, each graded as described below.

### Programming Grades

All programming notebooks should run from top to bottom without errors, using
`Cell > Run All`. Your grade for the programming notebooks depends on 3
factors: Correctness of the produced output, answers to the open questions, and
the style and design of the code.

The main goal of the programming notebooks in ML1 is **not** to learn
programming, but to better understand the algorithms you are implementing. Your
answers to the open question and checking that the produced output for each
step makes sense, are the main ways to show this understanding. Writing clear
code with good comments is also only possible when you understand what you're
implementing well enough. However, for the first 2 modules style and design
will not be included in your grade, as you'll still be learning what those
concepts entail in the *Python for Data Processing* course.

If all coding cells are completed, all open questions are answered and your
notebook runs top to bottom without errors, your grade starts at a 6. The
remainder of your grade is then determined as follows:

* 0 - Some code cells produce incorrect or incomplete results. Answers to some open questions are incorrect or lack motivations.

* 1 - All code cells produce mostly correct results, but may still contain small mistakes. Same goes for the answers to open questions. Style and design have had some attention, but can be improved.

* 2 - All code cells produce correct results. Answers to all open questions are correct and are motivated. Style and design are good.

* 3 - All code cells produce correct and nicely formatted results. Answers to all open questions are correct and consistently well motivated based on the theory of the algorithm. Style and design are very good.

* 4 - Above, and in addition: Output, answers and code cells are beyond what is expected for the course.

### Writing Grades

The writing assignments for this course might be different from writing
assignments you've done in your own studies. We'll start by outlining the
basic concept, in order to avoid confusion of what you are exactly graded on.

The most important aspect of your writing assignments is to show you've read
the week's material and have thought carefully about the accompanying
questions. Some questions might even just ask your opinion, which means all
that is required is that you've thought about the topic enough to clearly argue
*why* you think it is one way or the other. Specifically, this also means that
not every statement you make necessarily requires a reference or citation.
However, if you do look up other sources as part of formulating your answers,
you can of course use and cite them. 

If your writing contains a sufficient number of words answering each of the
questions from the assignment, while referencing the concepts from the reading
material, your grade starts at a 6. The remainder of your grade is then
determined as follows:

* 0 - A concept from the reading material may be misrepresented or missing. Arguments are not structured clearly or fail to motivate some part of the answer.

* 1 - The writing shows understanding of the concepts of the reading material, but there might be small inaccuracies. Answers are motivated, but some motivations could have gone more in depth. 

* 2 - The writing shows clear understanding of the reading material and how the concepts therein relate to the questions asked. All answers are well motivated using these same concepts. 

* 3 - Above, and in addition: The writing may use other sources or examples from the author's own field of study to provide relevant novel perspectives. All arguments are well structured and combine into a single cohesive answer to the questions asked.

* 4 - Above, and in addition: The writing as a whole is beyond what is expected for the course.

### Exam

The exam at the end of the course will be an oral exam consisting mainly of 
open questions on the theory and algorithms covered. More details on the exam
will follow later.

## Academic honesty

This course's philosophy on academic honesty is best stated as "be reasonable." The course recognizes that interactions with classmates and others can facilitate mastery of the course's material. However, there remains a line between enlisting the help of another and submitting the work of another. This policy characterizes both sides of that line.

The essence of all work that you submit to this course must be your own. Collaboration on problem sets is not permitted except to the extent that you may ask classmates and others for help so long as that help does not reduce to another doing your work for you. Generally speaking, when asking for help, you may show your code to others, but you may not view theirs, so long as you and they respect this policy's other constraints. Collaboration on the course's test and quiz is not permitted at all.

Below are rules of thumb that (inexhaustively) characterize acts that the course considers reasonable and not reasonable. If in doubt as to whether some act is reasonable, do not commit it until you solicit and receive approval in writing from the course's heads. Acts considered not reasonable by the course are handled harshly.

### Reasonable

- Communicating with classmates about problem sets' problems in English (or some other spoken language).

- Discussing the course's material with others in order to understand it better.

- Helping a classmate identify a bug in his or her code at office hours, elsewhere, or even online, as by viewing, compiling, or running his or her code, even on your own computer.

- Incorporating a few lines of code that you find online or elsewhere into your own code, provided that those lines are not themselves solutions to assigned problems and that you cite the lines' origins.

- Reviewing past semesters' quizzes and solutions thereto.

- Sending or showing code that you've written to someone, possibly a classmate, so that he or she might help you identify and fix a bug.

- Sharing a few lines of your own code online so that others might help you identify and fix a bug.

- Turning to the course's heads for help or receiving help from the course's heads during the quiz or test.

- Turning to the web or elsewhere for instruction beyond the course's own, for references, and for solutions to technical difficulties, but not for outright solutions to problem set's problems or your own final project.

- Whiteboarding solutions to problem sets with others using diagrams or pseudocode but not actual code.

- Working with (and even paying) a tutor to help you with the course, provided the tutor does not do your work for you.

### Not Reasonable

- Accessing a solution to some problem prior to (re-)submitting your own.

- Asking a classmate to see his or her solution to a problem set's problem before (re-)submitting your own.

- Decompiling, deobfuscating, or disassembling the staff's solutions to problem sets.

- Failing to cite (as with comments) the origins of code or techniques that you discover outside of the course's own lessons and integrate into your own work, even while respecting this policy's other constraints.

- Giving or showing to a classmate a solution to a problem set's problem when it is he or she, and not you, who is struggling to solve it.

- Looking at another individual's work during the test or quiz.

- Paying or offering to pay an individual for work that you may submit as (part of) your own.

- Providing or making available solutions to problem sets to individuals who might take this course in the future.

- Searching for or soliciting outright solutions to problem sets online or elsewhere.

- Splitting a problem set's workload with another individual and combining your work.

- Submitting (after possibly modifying) the work of another individual beyond the few lines allowed herein.

- Submitting the same or similar work to this course that you have submitted or will submit to another.

- Submitting work to this course that you intend to use outside of the course (e.g., for a job) without prior approval from the course's heads.

- Turning to humans (besides the course's heads) for help or receiving help from humans (besides the course's heads) during the quiz or test.

- Viewing another's solution to a problem set's problem and basing your own solution on it.

In all cases we follow the directives regarding fraud and plagiarism of the
University of Amsterdam and of the Computer Science
BSc programme. Find them here in [English] and [Dutch].

[Dutch]: http://uva.nl/plagiaat
[English]: https://student.uva.nl/en/content/az/plagiarism-and-fraud/plagiarism-and-fraud.html
