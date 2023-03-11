# Introduction to Kamva
Interactive E-Learning Platform

**Author:** M. Sadegh Salimi

[Kamva platform](https://kamva.academy/) is developed by members of Rasta Educational NGO. So first of all we have an introduction on this NGO.

## Rasta educational NGO
The Rasta Educational NGO was founded in the summer of 2017 by a group of students from Sharif University of Technology, Isfahan University of Technology, and the University of Tehran with support from the Isfahan Mathematics House and Sharif University of Technology.

The mission of Rasta is to promote science and growth through education and research. To this end, Rasta has harnessed the scientific expertise of its members to encourage a questioning spirit among students and the country's youth, conducting both on-site and online educational events for students.

Rasta has also introduced numerous educational products, including events, online content, student podcasts, the NimKhat magazine, and a competition platform.

Another one of these products is the Kamva platform, which will be highlighted in this report.

## What is Kamva?
The Kamva Academy is an online platform for designing and conducting online courses/events, created and maintained by the members of Rasta promotional NGO. The platform's most prominent feature is the addition of the "interactive" elements to the learning process. Kamva platform has the ability to hold both online and offline courses.

As stated, the "interactivity" aspect is the most important feature of this platform. Other features of the platform include the "gamification" aspect and the ability to personalize learning.

The platform also uses the “FSM-based learning method” in its workshops. The FSM method allows the teacher to guide students along separate learning paths and provide unique learning procedures for each student.

## FSM-Based Learning approach
In traditional learning methodologies, the content is taught linearly and all learners follow the same learning path that leads to the end of the training. However, in the FSM-Based Learning approach used by the Kamva platform, we view each course and its educational content as a graph of a Finite State Machine. Each node in the graph represents a state in the learning process.

In this learning process, students/teams are dynamically transitioned between different states. If a student has a good grasp of a topic, they may need more challenging exercises, in which case they will be moved to a state where they can hone their skills with tougher practice. Or, if a student is struggling with a concept or has not adequately remembered prerequisites, we can return them to a state that reinforces the prerequisites or provides simpler examples for better understanding.

![image](https://user-images.githubusercontent.com/45296858/224487432-ad3700b7-001a-4df1-938c-82c2325c1d24.png)


## Usage of Kamva
To date, nearly 15 courses or events have been held on the Kamva platform, attracting participation from over 7,000 students. These workshops can be conducted either with the presence of a teacher or independently, either as an individual or in a group setting.

Some of the courses or events can be seen in the following image.

![image](https://user-images.githubusercontent.com/45296858/224487476-1d4ba789-81a9-4bc5-a4cf-7c8cd010ea73.png)

## Platform Terminology
We categorize the platform-related terms and definitions into three categories: Roles, Features, and Components.

### Roles
Each account can have various roles, each with different permissions and access levels.

 + **Administrator**s can create events and assign the "Event Organizer" role to other accounts.
 + **Event Organizer**s have the ability to create workshops and courses within the event and can assign mentor/head roles to other accounts. They also manage student registration.
 + **Workshop Head**s can add mentors and grant them editing access to workshop content.
 + **Mentor**s can assess students' progress and make adjustments to their team's status. Some mentors have editing privileges for the workshop/course content.
 + **Student**s can form teams with other students and view course content.
 + **Team Leader**s, selected from the students, can change the status of their entire team.

### Features
Here are some of the key features of the platform:
 + **Interactive whiteboard**: Teams have access to a shared whiteboard where team members can see each other's drawings.
![image](https://user-images.githubusercontent.com/45296858/224487528-abba4671-8036-4ba3-8a67-d2294f938f32.png)
 + **Mentor request**: When students encounter challenges or problems, they can buzz mentors by pressing the "Request for a mentor" button.
 + **Answer submission**: Students can submit answers to questions posed in courses/workshops, and mentors can grade their solutions.
 + **Team invitations**: Students can create teams and invite others to join. Invited students can accept or reject the invitation.
 + **Mini-Game Embedding**: Workshop heads/mentors can embed interactive mini-games into learning states, which can be simple javascript games.
 + **Group Jitsi room**: Teams have a Jitsi room for communication and consultation with mentors.
![image](https://user-images.githubusercontent.com/45296858/224487551-956ca101-3ff8-4659-a8f5-1f685c8dc63e.png)
 + **Event Organizer Panel**: Event organizers have a panel for managing the event, where they can manage students, mentors, workshops, etc.
![image](https://user-images.githubusercontent.com/45296858/224487565-d444e9f2-1ba7-4968-9772-20a7f7fb1a72.png)

### Components
As we stated before, “Interactivity” is a key aspect of the platform, allowing mentors to incorporate various interactive elements into course states, including:
 + **Text**
 + **Multimedia (photo and video)**
 + **Short answer question**
 + **Long answer question**
 + **Mini-game**: This is the most powerful component, and can be used for mini-games, graphs, charts, and other interactive web elements. It is a javascript component.

You can check out [this link](https://minigames.kamva.academy/) for a list of mini-games we have developed and used in workshops.

![image](https://user-images.githubusercontent.com/45296858/224487594-642d515e-6db1-45b6-b9b4-2c51d2b3ddde.png)

## Development and Technology Stack
 + The Kamva project utilized a wide range of frameworks and libraries, including:
 + ReactJS
 + Django
 + TypeScript
 + React Redux
 + React Router DOM
 + Material UI
 + Django REST
 + Jitsi React SDK
 + Sentry
 + React Konva

## Open source development
Kamva is an open source project that allows anyone to contribute and suggest enhancements. There are two GitHub repositories associated with the project:
 + [Backend of Kamva](https://github.com/Rastaiha/Kamva-Backend)
 + [FrontEnd of Kamva](https://github.com/Rastaiha/Kamva-Frontend)

## Future possible plans
We are currently designing the Finite State Machine (FSM) of the course on our own, and mentors are responsible for transitioning students between states. However, in the future we could automate both course design and state changes by using Machine Learning algorithms, thus creating personalized FSMs for each student.

## Conclusion
In conclusion, Kamva is an interactive e-learning platform that can be used to conduct online and offline courses/events. It has a powerful feature set, including the ability to personalize learning and add interactivity to the learning process. The platform uses the FSM-based learning method, which allows the teacher to guide students along separate learning paths and provide unique learning procedures for each student. Kamva is an open source project and has been used to date by over 7,000 students. In the future, we can use Machine Learning algorithms to automate course design and state changes and create personalized FSMs for each student.
