## Project Proposal

### Project Title or Name of the Application	: Group Manager
### Section			   	      : 9-Cesium
### Group Members			    : BITOR, Joaquin; DEJADINA, Liam; RESUELLO, Casey
### Date (Proposal Date)  : Nov 13, 2026
### Project Description:

- Group Manager is a project that allows students to manage their group members, assign roles, delegate activities for the group, track completion of activities and give ratings for overperforming or underperforming groupmates. This can help students perform better and track members easier in group projects.

- The system will consist of objects under separate Student and Group classes.
  - Each student will have private attributes detailing their name and section, while they will also have three public lists for their ratings from groupmates, the groups they are in, and the tasks they have been assigned. Each student will be able to create their own group, complete an assigned task, and rate a groupmate using the methods under the Student class. Each student can also display the groups they are in, their assigned tasks, and their average rating.
  - Each group will have a name, a short description, a group leader, a list containing the objects of the other members, and a list of all the created tasks. Each group can create, assign, and display its tasks, add and show its members, and change its leader.
  -  The group leader will createGroup() then addMember() to complete the group. Tasks will be created and assigned (createTask() and assignTask()) to group members, who will then completeTask(). After projects are completed, groupmates can rateGroupmate() to evaluate a groupmate's performance. A student's average rating can be seen using rating(), which may help a student know if there is anything they need to improve on.

- The target demographic are students/student leaders who are managing their groupmates in group projects/group activities.

![UML Diagram]([https://github.com/lmydejadina/CS3SY26_ProjectProposal/blob/main/CS3SY26_ProjectProposal_Diagram.drawio.png?raw=true])

### Goals:

The goal for this coding project is to provide an application that group leaders can use in order to assign tasks to their groupmates and track the performance and completion of these groupmates in their assigned tasks and roles. This project aims to assist groups in being able to track the delegation of roles, tasks, and necessary requirements, allowing for easier monitoring among a group.

- Objective 1: Make tracking group members easier for group leaders
- Objective 2: Increase productivity and collaboration among group projects
- Objective 3: Encourage active participation among the group by being able to track under or over performing group members
- Objective 4: Allow for the easier delegation of tasks and roles among the group
