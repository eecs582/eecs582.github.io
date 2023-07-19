---
layout: default
---

## Project

### Requirement

A main component of the course is a **research-oriented** course project. You
will work as a team of **2-3 students** on a topic related to operating systems
or systems in general. The project should identify a clear problem, motivate
why that problem is important and why existing solutions are insufficient,
propose an idea to address the problem, implement a prototype, and demonstrate
the idea's efficacy through experiments and comparisons with existing
solutions. In the end, you will write up a project report about your work, just
like the research paper you read in the class.

Please use the [USENIX conference paper
template](https://www.usenix.org/conferences/author-resources/paper-templates)
to format your project proposal and report.

### Expectations

The best outcome for a project well done is that it will be suitable for
publication at a major systems conference (*OSDI, SOSP, EuroSys, NSDI, ASPLOS,
USENIX ATC*). Indeed, some papers in top systems conference are a result of 
a course project (e.g., [Infiniswap](https://www.usenix.org/conference/nsdi17/technical-sessions/presentation/gu) was 
a work started in EECS 582 in the past). In those cases, additional work after
the course is often needed to push the project to be more complete for
publication, but the course project should lay the groundwork.

The minimum expectations for the project are: (1) it should be interesting! (2)
it should produce a software artifact. In other words, even if the project does
not yield a real publication, it should have intellectual depth and something
that the readers can learn from. For (2), the resulting software artifact
should be usable. 

A survey of existing literature will *not* be suitable for the course project.
Measurement studies of systems or system techniques are only allowed as a
course project topic *with instructor's approval*. In that case, you must still
build a measurement tool as part of the project.

### Topics and Tips

I will provide a list of suggested topics, but you are encouraged to come up
with your own! 

<div class="card border-success">
  <div class="card-header bg-success text-white">
    <span class="bi bi-bell-fill"></span>&nbsp;&nbsp;<strong>Tips</strong>
  </div>
  <div class="card-body">
  <ul>
    <li>When reading the papers in this course, try to identify the (sub-)problems are
    related but unsolved, limitations of the proposed solution, a possible better 
    way to address the problem, whether the paper's insights or techniques 
    are applicable in a different problem domain. Thinking along those lines can give you inspirations about potential project topics.</li>
    <li>Besides reading papers, your own experiences can also be a source to
    brainstorm about the project topics. For example, you encountered annoying
    performance issues in system software and were frustrated that the existing
    profilers could not pinpoint the root causes; so a potential project is to
    identify the limitations in existing profilers and propose a solution to
    address them.</li>
    <li>Form the project team as soon as possible and start the project early. Systems 
    projects take time, even for a course project. If you start late, it is likely
    that you will not be able to finish the project in time.</li>
    <li>While we encourage you to be ambitious, make sure the project 
    is manageable, such that you have something to present at the end of the semester. 
    It is useful to define multiple sub-goals, distinguish the basis and stretch goals, 
    identify potential risks, and create back-up plans.
    </li>
  </ul>
</div>
</div>

I will meet with each team to help refine the project scope. I will always be
available for project discussions.

### Deliverable #1: Proposal
In the proposal, briefly describe the following elements:

* the problem you plan to tackle, and why the problem is important
* the state of the art for solving this problem, and why the current solution is insufficient
* the approach/idea you propose
* the objectives/expected outcomes
* the potential challenges
* the timeline and milestones
* division of work among the team members
* a list of related work that you plan to read

The proposal should be around 2 pages and include your group member's name and email. 
The proposal only needs to be submitted by one of the group members.

### Deliverable #2: Checkpoint 1 Report

Submit a checkpoint report (around 3 pages) to describe the status of your
project, the solution you have build so far, some initial results, new
challenges that arise, any adjustments to your approach.

### Deliverable #3: Checkpoint 2 Report

The second checkpoint report is closer to the final report. It should include all 
the progress you have made so far (including content from the first checkpoint
report), and highlight the new results since the previous checkpoint, and the 
remaining tasks and timeline for completing the project.

### Deliverable #4: Final Report

The final report should look like a research paper. It motivates the importance
of the problem with concrete evidence or data points.  It explains why existing
solutions do not solve the problem well. Then it describes the insights and
ideas of your work, the challenges you need to address, how did you address
them, why your idea is better, what are your system design and implementation.
Then shows the experiment results, interpret the results, describe the
observations and implications, conclude whether or how the results demonstrate
your solutions' superiority over state-of-the-art solution. Lastly, include a
related work section to compare and contrast with your solution.

There are no hard restrictions on the page limit on the final report, **because papers 
do not need to be long to be good**. But your final report must comprehensively 
cover all the points mentioned above. The rule of thumbs is that when it does so, 
the report is around 6 to 10 pages.

### Deliverable #5: Presentation/Poster

Each project team will be given a slot to do a presentation in class to
showcase your ideas and results to others. A live demo of the system you
developed would be a nice element of the presentation. We might host a poster
session in Tishman Hall if conditions allow.

### Deliverable #6: Source Code
You will be required to turn in your source code along with instructions (documentation) and
scripts for grading. The software artifact should be runnable by the TA and instructor.
