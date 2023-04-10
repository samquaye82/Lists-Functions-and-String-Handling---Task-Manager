# Lists-Functions-and-String-Handling---Task-Manager
In this project I was tasked with modifying a program to build a task manager.

There was so much functionality needed to complete this. Using the principle of abstraction I was tasked to refactor the code to create and use the following functionality:

register user — that is called when the user selects ‘r’ to register a user.
add task — that is called when a user selects ‘a’ to add a new task.
view all — that is called when users type ‘va’ to view all the tasks listed in a separate external text file.
view mine — that is called when users type ‘vm’ to view all the tasks that have been assigned to them.

The function called reg_user has to make sure that you don’t duplicate usernames when you add a new user to the external text file user.txt. If a user tries to add a username that already exists in user.txt, provide a relevant error message and allow them to try to add a user with a different username.

When the user selects ‘vm’ to view all the tasks assigned to them, the following functionality had to be present: 

   Display all tasks in a manner that is easy to read. Make sure that each task is displayed with a corresponding number which can be used to identify the    task.
   
   Allow the user to select either a specific task (by entering a number) or input ‘-1’ to return to the main menu.
   
   If the user selects a specific task, they should be able to choose to either mark the task as complete or edit the task. If the user chooses to mark a      task as complete, the ‘Yes’/’No’ value that describes whether the task has been completed or not should be changed to ‘Yes’. When the user chooses to      edit a task, the username of the person to whom the task is assigned or the due date of the task can be edited. The task can only be edited if it has
   not yet been completed.
