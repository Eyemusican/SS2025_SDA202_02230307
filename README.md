# SS2025_SWE201_02230307

# Automated Grading System Analysis

## System Background
The university needs to automate grading for programming assignments in its expanding Software Engineering course. Currently, professors manually grade by cloning student GitHub repositories and running code in their terminals. With 300+ students annually, plus staff and admin users, an efficient automated solution is essential.

## Diagram Analysis

### Image 1: Interaction Overview Diagram

![Alt text](practical_images\image3.png)



#### Reflection
This diagram successfully captures the core interactions between system components and users. The interaction overview approach works well to show:

1. **Role-Based Workflow**: The diagram clearly separates Professor and Student paths, showing how different users interact with the system.

2. **Decision Points**: Critical decision points like "Before deadline" and "Working" code checks are well-positioned to show how the system responds to different conditions.

3. **Process Flow**: The diagram shows how submissions move from student upload through plagiarism checking, code testing, and ultimately to grading.

4. **Feedback Loops**: The resubmission path is represented, allowing students to improve their grades through multiple attempts.


### Image 2: Activity Diagram 

![Activity Diagram](practical_images\image1.png)

#### Reflection

This diagram shows the students are handing in the assignments directly to their github repository and the professors are grading it manually by cloning down their repository to his/her local machine and running the student’s code in terminal and inspecting it manually in VSCode.


1. **Clear Roles**: It separates tasks between students, the terminal, and the professor.

2. **Step-by-Step Flow** : The vertical layout shows the order of activities.
3. **System Grouping** : Related activities are grouped, showing how different parts of the system work together.

4. **Decision Paths**: The outcomes of decisions (like "Working" or "Before Deadline") are clearly connected to what happens next.



### Image 3: Use Case Overview

![Use Case Overview](practical_images\image2.png)

#### Reflection
This diagram gives a clear view of the system by showing:

1. **System Boundary** : What is inside and outside the Code Submission System.
2. **Main Functions** : How the system’s features are organized.
3. **External Connections** : Links to GitHub, LMS University, and the Plagiarism Detector.
4. **User Interactions** : How students and professors use different system features.



## Comparative Strengths

When comparing these diagrams against the requirements:

1. **Image 3 (Interaction Overview)** best captures the process flow and decision logic, particularly for plagiarism detection and the resubmission path.

2. **Image 1 (Activity Diagram)** excels at showing responsibility boundaries and the sequential nature of the grading process.

3. **Image 2 (Use Case Overview)** provides the most comprehensive coverage of all system functions and external integrations.

## Objectives

1. The main goals of this analysis are to:

2. Check if the UML diagrams capture the system requirements well

3. See if the interactions are clear and easy to follow

4. Find strengths and weaknesses in the diagrams

5. Show how the system transitions from manual to automated grading


 
## Methodology

We studied three UML diagrams to understand the system better:

3.1 **Interaction Overview Diagram**

1. Shows the order of activities and decisions

2. Maps user roles to system actions

3. Highlights key decision points and different paths


3.2 **Use Case Diagram**

1. Identifies main users and system functions

2. Defines system boundaries and external connections

3. Focuses on system requirements


3.3 **Activity Diagram**

1. Organizes actions by user and system component

2. Shows step-by-step and parallel processes

3. Clarifies who is responsible for each task


## System Analysis

 **Interaction Overview Diagram Reflection**

This diagram shows how the system works step by step:

1. Separates Professor and Student actions

2. Marks key decision points (like deadlines and plagiarism checks)

3. Includes feedback loops for resubmissions



**Shows connections to the Learning Management System (LMS)**

It helps visualize the shift to automation by showing:

1. Students submitting code directly

2. Automated checks replacing manual reviews

3. Professors spending less time on repetitive tasks

4. Students receiving systematic feedback




5. Comparative Analysis

Each diagram adds a unique perspective:

1. The Interaction Overview Diagram shows the process flow and decisions

2. The Use Case Diagram explains system functions and boundaries

3. The Activity Diagram shows responsibilities and step-by-step workflows

Together, these diagrams give a complete picture of the system, balancing technical needs with practical considerations.


## Conclusion

The UML diagrams provide a solid foundation for building the automated grading system. They show:

1. How to integrate smoothly with the current LMS

2.  A cost-effective, flexible design

3.   Support for high academic standards

While small adjustments could improve clarity, the diagrams successfully capture the key elements needed to guide system development.