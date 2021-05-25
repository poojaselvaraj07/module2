# module2
*Operating Systems and You: Becoming a Power User Coursera - Week 5 &amp; Week 6*


# Week 5 - Assignment 1

## Maintain Efficient Process Utilization on Windows

We can demonstrate this by killing a running process using Windows Powershell.

1. Collect Process Information

   **Get-Process** - gets all the currently running processes.
 
   __Get-Process -Name "process name"__ - this can be used to target processes with a specific process name.

2. Terminate a specific process

   __taskkill /F /PID__ - kills the process with the mentioned PID.

   Following message will be printed if the termination is a success:
   SUCCESS: Sent termination signal to terminate the process with PID [id].

3. Terminate multiple processes
  
   __taskkill /F /PID /PID__ - can be used to terminate multiple processes at once.


# Week 6 - Assignment 2

## Using Logs to Help You Track Down an Issue in Windows

1. Updating software that's out of date

2. Finding and deleting Files

3. Modifying file permissions

4. Terminating specific tasks/processes



