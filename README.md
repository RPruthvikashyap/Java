Calculating Estimated Completion date and time of a task.

Let say we are assigning different tasks to different Employees.
Task1 to Employee1
Task2 to Employee2
..
TaskN to EmployeeN
Each task takes different amount of time to complete, like 8 hours, 16 hours, 48 hours, 72
hours.
Task1 takes H1 hours to complete.
Task2 takes H2 hours to complete
And so on.
Each employee can work in different time table.
Employee 1 working from 7 AM to 3 PM,
Employee 2 working from 3 PM to 11 PM
Employee 3 working from 11 PM to 7 AM and so ON

Employees might take leaves on certain days.
Employee 1 is on Leave on 1 st December, 5 th December and 15 th December
Employee 2 is on Leave on 3 rd December, 8 th December and 10 th December.

If we know the start time of the task, we need to calculate the end time of the task by
considering Leaves, different working hours and time required to complete the task.

We need a program in java, where we have a function java:
Where we pass:
startTime = Caledar startTime of the task
timeRequired = Integer noOfHours required to finish a task
workingHourStart = the Start time of employee
workingHourEnd = End time of employee
List&lt;Leaves&gt; = All the dates when the employee is on leave.
getEndTime(startTime, timeRequired, workingHoursStart, workingHourEnd, List&lt;Leaves&gt;)
We need to return the end time when the task will be finished.
