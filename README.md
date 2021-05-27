# bug-tracking-system
A bug tracking system that keeps track of bugs that the user encountered in any software development or in any project and various role distribution.
You need to have MySQL installed with root password set as null or no values or "".
creating a database:
run the queries in MySQL command line client to a create the database as:
Creating 5 tables:
1. employee(empCode, empName, empEmail, empPassword, gender, DOB, mobileNo, Role)
2. project(projectId, projectName, SDate, EDate, projectDesc)
3. AssignProject(projectId, empCode)
4. bugtype(bugCode, bugCategory, bugSeverity)
5. bugreport(bugNo, bugCode, projectId, empCode, status, bugDesc)

Directly keep on copying and pasting each line(for least errors) of the bds.txt file in command line.
