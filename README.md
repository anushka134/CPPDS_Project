# CPPDS_Project
To-do list

Group members:
Akshara Vinjamuri - 011

Anshuman Nerkar - 022

Anushka Sinha - 024

CPPDS project _ to-do list

To-Do List Program Algorithm:

1.Initialize: -> Create a structure Task with name (string) and status (boolean). ->Declare constant MAX (maximum tasks) and an array of Task called tasks. -> Initialize count to 0.

2.Menu Loop: ->Enter a loop displaying a menu of options: Help, Add Task, Show Tasks, Mark Task as Done, Delete Task, Quit. ->Read user choice into choice.

Option 1 (Help and About):-

Display information about the program and creators.
Option 2 (Add Task):- ->If count is less than MAX: -> Create a new Task. -> Input task name, set status to false, add to tasks. -> Increment count. -> If count equals MAX, display "Task list is full."

Option 3 (Show Tasks):- ->If count is 0, display "No tasks." ->Else, loop through tasks, display task number, name, and status.

6.Option 4 (Mark Task as Done):- -> Display tasks. -> Input task number. -> If valid, mark task as done (set status to true). -> If invalid, display "Invalid task number."

7.Option 5 (Delete Task):- -> Display tasks. -> Input task number. -> If valid, shift tasks to remove the task. -> Decrement count. -> If invalid, display "Invalid task number."

Option 6 (Quit):- -> Display "Goodbye!" and exit the loop.
9.Invalid Choice:- -> If users choice is not 1-6, display "Invalid choice. Try again."

10.Repeat:- -> Continue loop until user chooses to quit (option 6).

Exit:- -> End the program.
