# To-Do List Command Line Coding Challenge

You are tasked with developing a command-line interface (CLI) program for a basic To-Do List application.
The program should allow users to add, view, and remove tasks from their to-do list. Each task has a title and a description. The program should also provide the ability to mark tasks as completed.


## Requirements:

The CLI program should have the following commands:

/add: Allows the user to add a new task to the to-do list. The user should enter content for the task.

/ls: Displays the list of all tasks (both completed and pending) with their content.

/check:  Marks a task as completed. The user should provide the <task_id> of the task to mark as completed.


## Exmaple:


    > /ls
    == Pending ==
    == Completed ==
    
    > /add Leetcode training
    > /ls
    == Pending ==
    <task_id1> Leetcode training
    == Completed ==
    
    > /add Eat
    > /ls
    == Pending ==
    <task_id1> Leetcode training
    <task_id2> Eat
    == Completed ==
    
    > /check <task_id1>
    == Pending ==
    <task_id2> Eat
    == Completed ==
    <task_id1> Leetcode training
  
  




The program should handle invalid inputs gracefully and provide appropriate error messages when necessary.

The to-do list data should not be stored permanently. The program should keep the tasks in memory while it's running.

The program should have a clean and user-friendly interface.

The code should be modular and well-organized.

