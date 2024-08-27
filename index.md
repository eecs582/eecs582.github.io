---
layout: home
---

## Course Overview

Operating systems are a critical and complex piece of software that does the
heavy lifting of managing computing devices for other software. It is also one
of the few types of software that has been extensively engineered, studied,
refined, debated, and even overhauled for decades. While one might
consider operating systems as mature software, its evolution is far from
complete.

This course exposes students to the operating systems as a research field and
study operating systems, and more broadly computer systems in general, from a design 
point of view. We will examine different systems in both important historical 
contexts and recent research developments. In addition to teaching various system 
techniques, the objectives of the course also include helping students learn:

* How to read a research paper in an objective manner.
* How to write a critical analysis of the research described in a paper.
* How to articulate ideas and insights into a research paper.
* How to compare and contrast different approaches to understand their trade-offs.
* How to synthesize research themes and topics across multiple papers.

This course involves readings on classic and new papers. Topics include OS
structure and extension techniques, virtualization, synchronization,
communication, file systems, reliability, formal verification,
data centers, and history and experience of systems.

<span class="badge bg-info md-badge">Prerequisite</span>: EECS 482 (Introduction 
to Operating Systems) or equivalent.

<hr>

## Staff

<dl class="staff">
	<dt><h4>Instructor</h4></dt>
	<dd><strong><a href="https://web.eecs.umich.edu/~ryanph">Ryan Huang</a></strong></dd>
	<dd><b>Email: </b><a href="mailto:ryanph@umich.edu">ryanph@umich.edu</a></dd>
	<dd><b>Address: </b>BBB 4611</dd>
	<dd><b>Office Hours: </b>By appointment</dd>
	<dt><h5>GSI</h5></dt>
	<dd><strong><a href="https://chenyi.world/">Yi Chen</a></strong></dd>
	<dd><b>Email: </b><a href="mailto:yichencs@umich.edu">yichencs@umich.edu</a></dd>
	<dd><b>Address: </b>BBB 4945</dd>
	<dd><b>Office Hours: </b>Tuesdays/Thursdays 2pm-3pm</dd>
</dl>

## Meetings

<p>
<div class="border-table">
<table class="table table-hover">
  <tbody>
    <tr scope="row">
      <td><strong>Lecture</strong></td>
      <td>Tuesday/Thursday 3:00pm-4:30pm 1200 EECS</td>
    </tr>
  </tbody>
</table>
</div>
</p>

## Readings
This course does not have a required textbook. However, we recommend you to
use an undergraduate operating systems textbook as a reference, e.g.,
[Operating Systems: Three Easy Pieces](http://www.ostep.org). 

We also recommend you to read materials about the internals of mainstream OS.
These resources will both help you understand technical details in many papers 
and serve as handy references in your project development and systems research
in general. We particularly recommend the following books:

* *Understanding the Linux Kernel*, 3rd Edition, Daniel P. Bovet, and Marco Cesati, 2005.
* *Linux Kernel Development*, 3rd Edition, Robert Love, 2010.
* *The Design and Implementation of the FreeBSD Operating System*, 2nd Edition, Marshall Kirk McKusick, George Neville-Neil, and Robert N.M. Watson, 2014.

The major material of the course comes from seminal, noteworthy, or representative 
papers from the literature. Each class will have one or two **required** papers 
to read. You **MUST**{: .text-danger} read the required papers **before**{: .text-danger} 
the class, and be prepared to discuss them. In-class questions or quizzes will 
confirm you do the reading.

For some topics, we will list additional recommended papers. You are encouraged, 
but not required, to read those. Students often find it useful to form a reading 
group to discuss papers together before the class period, and we encourage 
the practice. The reading load will be heavy. So be sure to allocate enough
time for it.

* [Reading List and Schedule](schedule.html)

<span class="badge bg-info md-badge">Note</span>: this course assumes that you
have taken the undergraduate operating systems course. Thus, it will *not*
cover background knowledge such as how virtual memory works. Most papers we will 
read also make such an assumption. If you did not take an undergraduate OS 
course, it will be quite challenging to complete this course. If your undergraduate 
OS knowledge is rusty, review past lectures ([example](https://web.eecs.umich.edu/~ryanph/jhu/cs318/fall22/schedule.html)) to
help better comprehend the papers.

## Grading

<div class="container">
  <div class="row">
  <div class="col-8" style="padding-left:0px">
    <ul class="list-group border-table grading-table">
      <li class="list-group-item d-flex justify-content-between align-items-center">
        <b>Reviews</b>
        <span class="badge bg-primary rounded-pill">10%</span>
      </li>
      <li class="list-group-item d-flex justify-content-between align-items-center">
        <b>Labs</b>
        <span class="badge bg-primary rounded-pill">10%</span>
      </li>
      <li class="list-group-item d-flex justify-content-between align-items-center">
        <b>Presentation</b>
        <span class="badge bg-primary rounded-pill">15%</span>
      </li>
      <li class="list-group-item d-flex justify-content-between align-items-center">
        <b>Class Participation</b>
        <span class="badge bg-primary rounded-pill">15%</span>
      </li>
      <li class="list-group-item d-flex justify-content-between align-items-center">
        <b>Project</b>
        <span class="badge bg-primary rounded-pill">50%</span>
      </li>
    </ul>
  </div>
  </div>
</div>

<p></p>

## Structure and Policies

<span class="badge bg-info fs-6"><b>Paper Review</b></span>: You are required to 
submit a brief review for the required reading in each class. For Thursdays' 
classes, the reviews only need to answer the listed paper questions. Reviews 
must be turned in by <span class="text-danger">by 12 pm</span> on the day of
the class. Please refer to the detailed requirements on [this page](review.html).

<span class="badge bg-info fs-6"><b>Participation</b></span>: The structure of
this course is unusual in that there are NO traditional lectures. Instead, 
we will discuss research papers that everyone is expected to **read before** 
class. Because of this format, class participation is vital to the success of
the course. If you remain silent in the class, you will gain little out of this
course.

In each class, I will ask direct questions about the paper and expect you to
be able to answer. Note that your answers to these questions will be part of
your overall grade.

<span class="badge bg-info fs-6"><b>Presentation</b></span>: A subset of the
papers will be presented by students in groups of 2--3 members. Each group
will present *at least once* in the semester. The presentation should not
simply summarize the paper. Detailed requirements for the presentation are
described on [this page](presentation.thml).

<span class="badge bg-info fs-6"><b>Attendance</b></span>: *Three* absences of
classes are allowed for good reasons (e.g., conference presentation,
interview). However, reviews of the papers must still be turned in.

<span class="badge bg-info fs-6"><b>Discussion</b></span>: You are strongly
encouraged to discuss the papers with other students in the class -- you may
have insights that others do not, and vice versa. Often students form reading
groups, which I heartily encourage. Note that group discussion, however, is not
an effective substitute for actually reading the paper.

<span class="badge bg-info fs-6"><b>Labs</b></span>: There will be one or more
assignments to give your hands-on kernel programming experience and prepare you 
for the course project. They are to be done individually.

<span class="badge bg-info fs-6"><b>Project</b></span>: A major component of
this course is a semester-long, research-oriented course project. You will 
work in a team of 2-3 students on the project. Detailed requirements for the project 
are described on [this page](project.thml).

<span class="badge bg-info fs-6"><b>Missing and Late Submission</b></span>: 
You may miss up to *three paper reviews* without penalty. For each additional missed 
review beyond three, a 30% deduction will be applied. Therefore, missing a total
of seven paper reviews results in a zero for the review grade. 

Missing the submission of any other assignment (e.g., proposal) will result in
a zero for that assignment. Late submissions of any assignment (including paper
reviews, proposals, etc.) will incur the following penalties:
<ul>
<li>within 12 hour, 10%</li>
<li>1 day, 20%</li>
<li>2 days, 40%</li>
<li>3 days, 80%</li>
<li>4 days, no credit</li>
</ul>

<span class="badge bg-info fs-6"><b>Academic Integrity</b></span>: All students are required to 
  know and adhere to the College of Engineering [Honor Code](https://ecas.engin.umich.edu/wp-content/uploads/sites/19/2023/02/College-of-Engineering-Honor-Code-UPDATED.pdf) and 
  university policies. They apply to all course requirements, including the
  paper reviews, proposals, course project code and documentation. <span
  class="text-danger">Violations of the policies will result
  in serious consequences</span>. You may use tools such as ChatGPT to help you 
  understand the concepts and paper contents. However, you may NOT use them to
  do the required work for you, such as generating reviews, answering assigned 
  questions, or completing the programming assignments. 

## Acknowledgment

The course syllabus and materials are influenced by the advanced OS course at
UCSD (CSE 221). We are particularly indebted to Geoff Voelker for sharing his
lecture notes.
