# Overview

This report analyzes and models the business process of a cooking school, described as following:
<br>
*Consider the scenario of a cooking school that must manage student requests. A student
contacts the school and receives a list of available courses. The student selects a course and
is put in contact with an instructor. The instructor proposes a date and location for the first
lesson, and the student can either accept or propose different date and location options. This
iteration continues until an appointment is set. Before each lesson, the student receives a list of
ingredients and tools to familiarize themselves with before they are used in the session. During
the lesson, the student prepares a series of recipes: the instructor describes the preparation
steps, the student begins executing them, and, in case of doubts, asks the instructor for advice.
At the end of each session, all dishes are tasted, and the instructor shares her impressions with
the student. After making an electronic payment to the school, the student and the instructor
can schedule a new appointment (using the protocol described above), or the student can decide
to conclude the course. If the course is completed, the client informs the school, and the process
is concluded. Modify the processes so that, at the end of the course, the student can choose to
start a new learning path.*


## Modelling 
BPMN was chosen to model the scenario as it offers a clear and structured way to represent the
collaborative nature of the process and the interactions between different actors. The modeling
was carried out using Camunda Modeler, which was selected for its ability to effectively handle
complex workflows and visualize inter-participant communication.

## Workflow nets
The processes described in BPMN diagrams subsequently converted into workflow nets, a special
form of Petri nets. This transformation allows for a more formal and mathematically rigorous
representation of the process, enabling thorough analysis and verification of specific behavioral
properties.
