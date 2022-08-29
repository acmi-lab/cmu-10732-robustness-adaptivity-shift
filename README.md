Instructor: Zachary Lipton (Director of [ACMI lab](https://acmilab.org)) \
Time: Mondays 5pm–9pm \
Location: GHC 4303 (in person) \
TAs: [Shantanu Gupta](https://shantanu95.github.io/), [Gokul Swamy](https://gokul.dev/) \
Credits: 12

## What's the course about

Under distribution shift, the source domain (which produces labeled training data) 
and the target distribution (which produces unlabeled deployment-time data) might diverge. 
In general, if one can assume nothing about how the past relates to the future, 
then all bets are off. 
However, under a variety of reasonable settings, we might hope for robustness and/or adaptation. 
Descriptions of such settings in the literature vary in key ways: 
two-domain discrete shift setups versus continual shifts; benign shifts,
versus targeted adversarial attacks, 
shifts that preserve (factors of) causal structure and/or support 
versus shifts that respect geometric invariances. 
In this class we will take a grand tour of the literature 
on robustness and adaptation under distribution shift,
bringing together perspectives from distributional robustness, 
structural causal models, adversarial learning (in both senses),
and the wild west of heuristics and benchmarks 
that have been proposed in the deep learning literature. 

## Structure and Deliverables

The first week of class we will get to know each other, 
learn about each student's experience in this area,
discuss the course logistics, and finalize our list of topics. 
The second week will be labor day and each student 
will enjoy a spa day as required by federal and university regulations.
On the third class, Zack will give a lecture on 
label shift (including positive and unlabeled learning, 
open set label shift, and latent label shift),
using this material to give an overview of several 
of the key themes of the topic, including identification,
estimation, and bridging deep learning methods with structural assumptions.

Then, starting from the third week, each session 
will be run by a group that will be responsible for 
distilling a different major topic in this literature.
Each week, all students, except those presenting, 
will be responsible for submitting short responses 
to each week’s readings. These will require students
to register 3 thoughtful questions. 
These will be made available to the presenters 
more than 24h prior to their presentations.
There will be no inescapable lulls in conversation,
because we will always have 30+ questions to resolve.

This is a 12-credit class and thus the deliverables 
are heavier than for a typical seminar. In particular,
in addition to presenting material from the literature
during the class, students will be required to complete
a final project. The silver lining: this project 
has been oriented to align closely with your career goals. 


## Presentations 

Students will be assigned to present a major topic 
in a group of 3 or 4. 
After the first day of class, students 
will have the opporunity to register interest in topics,
which will be taken into account when constructing group assignments. 
While each group will be given several 
"seed" readings to to anchor their inquiry,
groups are encouraged to expand the set of papers covered 
(and when appropriate, to modify the assigned readings) 
to paint a more comprehensive view of the area. 
While we have the room for 4 hours, 
we should plan to have two *heavily-interrupted* 75-minute sessions,
separated by a 30-minute pizza break. 
Groups will have some discretion about 
the extent to which they wish to intersperse group discussion 
throughout the presentations, versus frontloading technical discussion
and guiding a critical discussion in the second half/

You have discretion to influence both 
the scope of material to be presented
and to make pedagogical decisions about how to present it. 
While sometimes, it may make sense for each group member
to present a paper, do not reflexively fall into the trap
of following each paper section by section.
There may be times where integrating the papers,
e.g., by covering common elements of the setup up front 
and discussing common critical concerns about the approaches
at the end might make more sense. 

All presenters should provide lecture notes. 
Whenever possible presentations should 
rely on chalk/whiteboard presentations
and avoid powerpoint except if necessary
given the nature of the material.


## Project

In self-chosen groups of 2-3 students will pursue
a project related to robustness and adaptation 
of one of the following two forms:
 * A comprehensive review of the literature
 * An original technical research project
 
As the class progresses, the extra time after Monday's presentation
can be used for unstructured disucssions of project ideas 
with the instructor, TAs, and your peers.

## Grading
 * 25% weekly feedback on readings
 * 25% presentation
 * 25% participation
 * 25% projects

## Tentative Topics
 * Adaptation under Causally Structured Shifts
 * Label and Covariate Shift
 * Strategic Classification and Performative Prediction
 * Domain Generalization
 * Shift Detection and Anomaly Detection
 * Adversarial Examples and Certified Defenses
 * Distributionally Robust Optimization
 * Sequential Testing 
 * Online/adversarial learning formulations
 * Conformal Approaches
 * Data Augmentation and Invariances
 * Benchmarks (the landscape of existing benchmarks, the role of benchmarks, etc)
 
