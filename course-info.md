# CS 1632
Software Quality Assurance - Summer 2022

## Course Information

**Taught by:** Wonsun Ahn (wahn at pitt dot edu)
  * GitHub username: wonsunahn

**Class Time and Location:**

  * Tue/Thu 11:30 AM - 1:15 PM @ 5502 Sennott Square
  * Fully synchronous in-person

**Instructor's Office Hours:**

  * Chat on Microsoft Teams: Mon-Fri 9:00 AM - 6:00 PM
  * Physical Office Hours: Tue/Thu 10:30 AM - 11:30 AM @ 5423 Sennott Square, or by appointment

**Class GitHub repo:** https://www.github.com/wonsunahn/CS1632_Summer2022

**Required Texts:**
* [_A Friendly Introduction to Software Testing_](software-quality-assurance-textbook.pdf)
  * This is a PDF and is freely available by clicking on the link

This course provides students with a broad understanding of modern software
testing and quality assurance. Although it will cover testing theory, the
emphasis is on providing practical skills in software testing currently used in
industry. To that end, it will cover: manual and automated tests, test-driven
development, performance testing, and model checking.

This lecture will use the **flipped classroom** learning model.  All lectures
(except the introductury lectures and guest lectures) will be pre-recorded and
posted on Canvas.  It is your responsibility to keep up with the lectures
according to the schedule on the [Syllabus](syllabus.md).  There will be eight
in-class exercises to apply what you learned during the lectures and to prepare
you for the deliverables.

The class schedule is available on the [Syllabus](syllabus.md)).  

## Grading

* Projects (70%):
  * Deliverable 1 - 10%
  * Deliverable 2 - 15%
  * Deliverable 3 - 15%
  * Deliverable 4 - 15%
  * Deliverable 5 - 15%
* Midterms (20%):
  * Midterm 1 - 10%
  * Midterm 2 - 10%
* Participation (10%)
  * TopHat attendance
  * TopHat lecture questions
  * Exercise submissions (satisfactory / unsatisfactory)
  * Teams participation

TopHat questions will be asked in class on the day that the recorded lectures
are due, usually at the beginning of each week.  You will be given typically 30
seconds to one minute to answer each question.  0.5 points are participation
points and 0.5 points are correctness points for each 1 point per question.

Exercise submissions are unscored (as in your actual score doesn't matter).
You will get full credit if you submit "satisfactory" work.  By satisfactory, I
mean you did not just submit the skeleton code and you put some kind of effort
into doing the exercise.  Since these are unscored, you are encouraged to learn
from your classmates, including by sharing each other's source code.

Exams will NOT be allowed to be made up except with a valid and verified excuse
(generally medical - others are left to the discretion of the instructor).

The following grading scale will be used.  Note that I do _not_ round grades up.

Score  | Grade
-----: | ------------------------------
100.00-93.00 | A (A+ for extraordinary work)
92.99-90.00  | A-
89.99-87.00  | B+
86.99-83.00  | B
82.99-80.00  | B-
79.99-77.00  | C+
76.99-73.00  | C
72.99-70.00  | C-
69.99-67.00  | D+
66.99-63.00  | D
62.99-60.00  | D-
59.99-0.00   | F

## Group Work Expectations

You are highly encouraged to work in groups of two for the exercises and
deliverables.  I encourage it because, not only will you be able to learn from
each other in a technical and academic sense, but also because the experience
of collaborating on a software project as a team is valuable in itself.  You
will learn to communicate better, internalize good collaboration habits, and
learn to use collaboration tools such as a shared Git repository.  Just like
anything else, learning to collaborate well requires effort.  If you are
prepared to put in this effort, yes, please go ahead and sign up for a
partnership!  If you have a reason for wanting to work alone, please talk to
me and I would be happy to discuss it.

You are responsible for finding your own partner.  The contact info for your
classmates are available in our team on Microsoft Teams (see [Participating in
Class](#participating-in-class)).  Also, you can broadcast a message on the
Partner Exchange channel on Teams to see if anyone is interested.  Once you
from a partnership, please submit the Partnership Contract on GradeScope.  Your
expectations as a group member are outlined clearly on the contract.  You may
resubmit the contract at a later time, at which time the new contract will come
into effect.

## Assignment submission

All exercises and deliverables are submitted using GradeScope.  Only one member
of the group is asked to submit to GradeScope.  After submission, please use
the "View or edit group" link at the top right of the submission page to add
your partner.  Failure to add a partner will result in the partner not getting
credit.  If your partner has submitted but the submission does not appear on
GradeScope on your list of submissions, ask your partner if your name was
added.

Assignments should be committed and pushed to GitHub to a shared private
repository and then submitted to GradeScope.  This shared private repository is
automatically created for you through GitHub Classroom when you click on the
GitHub Classroom link provided at the top of the instruction README for
relevant assignments.  Some assignments also require write-ups that needs to be
submitted to GradeScope.  The format of the write-up will be specified on each
assignment.  Students are encourged to commit early and often to the GitHub
repository as commit history will be used as the ground truth for proof of work
(especially as it relates to a group project).  Also, frequent commits help
avoid conflicts when working on the same files as your partner.  

If any disputes from groups arise, I will assume that GitHub is the "ground
truth".  For example, if Partner A insists that they did all the work, but
GitHub history shows only commits by Partner B, I will assume that Partner B
has done all the work.

Late assignments will receive a -5 percentage point penalty per day (e.g., if
you would have received a 90% on an assignment, but you turned it in 3 days
late, you would receive 90 - 15 = 75%.).  

## Excercise Details

Exercises are unscored, as in the score that you get on GradeScope will not be
factored into your grade.  As long as you didn't get a 0 score (or you didn't
submit), your exercise will be marked as complete and be counted towards your
participation score.  The purpose of the exercises are to prepare you for the
deliverables and get feedback on mistakes you made so that you don't make the
same mistakes on your deliverables.  Since exercises are unscored, you are free
to discuss them with your classmates, including sharing each other's code.

Exercises will be **released on Tuesdays** in class.  You will be given time
in-class on Tuesday to complete it and if you don't, you can keep working on it
on Thursday as well.  On Thursday, we will discuss the exercise and you will
have a chance to ask questions if you had any difficulties.  You can finish up
and **submit by the start of the next class**.

* **Exercise 0:** Java assessment exercise
* **Exercises 1-5:** Exercises that prepare you for the corresponding deliverable (see below)
* **Supplementary Exercises 1-4:** Supplementary exercises that are unrelated to a deliverable

## Deliverable Details

Deliverables are scored, and will constitute the bulk of your letter grade.  

* **Deliverable 1:** Developing a test plan and traceability matrix for a system.
* **Deliverable 2:** Developing unit tests for a console-based application.
* **Deliverable 3:** Developing a simple web application system with the help of automated systems testing.
* **Deliverable 4:** Performance testing and optimization of an application.
* **Deliverable 5:** Developing and testing an application using both static and dynamic testing.

## Programming Language Selection

For all deliverables, the class will use Java with the appropriate frameworks
(JUnit, Mockito, Selenium).  Projects written in other languages or using
alternative frameworks will not be accepted.

## Participating in Class

Questions and comments are invited and strongly encouraged.  If you have a view
point or experience that may enrich the class, please jump in!  As we will come
to learn, often there is no "correct answer" for software quality assurance.
To be successful, you need the flexibility to adapt different tools and
methodologies to different situations.  That means your question or perspective
will only enrich the thought process of others (including me).  In the process of
teaching this course, I have never had a "dumb" question.  

There are several ways you can participate:

1. In-class

    If you raise your hand, I will get to you as soon as I notice.  Or, just
say "Dr. Ahn, I have a question!" or "Dr. Ahn, may I add something?" and
interject.  Or do both at the same time.

2. Out-of-class

    Please use the Teams "Posts" tab on the "General" channel if you have a
general question or comment.  If you have a question about a specific exercise
or deliverable, there is a channel dedicated to it (e.g. "Exercise 0 (Java
Assessment)").

    You can also DM (direct message) me or another student in the class.
Again, select the class in the "Teams" menu and then click on the "..." context
menu beside the "CS 1632 Software Quality Assurance" team name.  Please select
the top-most item: "Manage Team".  There, you should be able to see the
statuses of all students in the class, and if you hover over the name of any
student, you should see options to initiate a chat, email, or video chat with
that individual.

3. Email / Canvas messages

    For the fastest response, please use Teams chat.

When you ask a source-code-specific question about an exercise or deliverable,
<b>please submit your code to GradeScope so that I can reproduce your
error.</b> Also, describe precisely the steps I should take to reproduce your
error.  Before you do this, it is very hard for me to help you.

I will typically respond to Teams messages in real time.  But please understand
that sometimes I may be away from my desk or having a meeting.  If I don't
respond immediately, I guarantee that I will respond within 24-hours at most.
Often, <b>you may have the best answer to your classmate's question</b>
(particularly if it is an issue specific to a OS, platform, or IDE).  If you
think you can help, don't wait for me --- please jump right in!  I will give a
thumbs up on verified answers or I will add a few more things if needed.  Both
asking and answering questions will be considered as participation.

## Disability Services Statement

"The Office of Disability Resources and Services (DRS) provides a broad range
of support services to assist students with disabilities. Services include, but
are not limited to, tape-recorded textbooks, sign language interpreters,
adaptive and transportation. Contact DRS at 412-648-7890 or 412-383-1355 (TTY)
in 216 William Pitt Union or see www.drs.pitt.edu for more computer technology,
Braille translation, and nonstandard exam arrangements, DRS can also assist
students with accessibility to campus housing information."

The instructor will work to the best of their ability to accommodate any issues
arising from a disability that a student has, but he must be aware of it in
order to accommodate it.  Please inform me as soon as possible if you have a
disability which you think may hinder your success in the course and we (along
with the DRS) should be able to work around it.

## Academic Integrity Statement

Cheating/plagiarism will _not_ be tolerated. Students suspected of violating
the [SCI Academic Integrity
Policy](https://www.sci.pitt.edu/student-resources/policies/academic-integrity-policy)
will receive a minimum sanction of a zero score for the exam or assignment.

Some guidelines:

_1. For unscored in-class exercises, you are allowed (and encouraged) to look
at your classmates' work and discuss it.  If you get ample help for the
exercises, you should rarely need additional help for the deliverables._

_2. For all scored deliverables and exams, viewing the work done by your
classmates (or a 3rd source) before submission is considered cheating.  Aiding
this activity is also considered cheating.  The only exception is your
designated group members for your group projects._

_3. If you have any question about the exercises, I encourage you to post it
publicly on the appropriate Teams channel.  The same goes for questions about
deliverables that do not require you to show your work.  Keeping it public acts
as a psychological guardrail; if you are hesitant about communicating publicly,
chances are that you subconsciously are aware that you are compromising your
integrity._

_4. If you have a question on the deliverables that does require showing your
work, please initiate a chat with your instructor on Teams or come to office
hours._

## Back to In-Person

The university policy is to be back to full in-person.  That means we are back
to pre-COVID rules concerning remote classes: they do not exist, as a general
rule.  There are two exceptions:

_1. If you have to quarantine due to contact with COVID.  Either you have a
positive test result or you are waiting for test results._

_2. If you have a family or medical emergency that would cause you to miss
class.  Rather than miss class, if you are able to participate over Zoom, I
encourage you to do so._

For the above exceptions, I will create Zoom sessions on demand.  These Zoom
sessions are only available to affected students and are protected by a
password which is distributed individually.  Please notify me as soon as you
are affected so I can make arrangements.
