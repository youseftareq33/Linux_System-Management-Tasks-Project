# Linux Command-Line Operation and System Management Tasks Project

# Question 1:

1. Question#1: Use the find command to compile a list of all directories in your system (under the root’/’directory).
The command must redirect the output so that the list of directories ends up in a file called directories.txt and the
list of error messages in a file called errors.txt.

2. Question#2: run vi forever in the terminal and write the following script: 

while true 
do echo hi Comp311 students> out 
done: wq! 

3. Question#3: Run the command forever in the background using &. 

4. Question#4: Run the command forever in the foreground, suspend it with CTRL+z, and
put it into the background using bg. Next, run the command jobs, then the command ps.
Finally, bring the job back into the foreground with fg. 

5. Question#5: Run the command forever four times in the background using &, then use 
the kill command to terminate the process by its job number. Repeat this task but kill the 
process by specifying its PID. 

6. Question#6: Run the command forever in the background using &, then use the kill 
command to suspend (stop)the process. Finally, use the bg command to resume running 
the process.

7. Question#7: Suppose there are many forever processes in the background, for example,
more than 50 processes in the jobs. We need to kill these processes at once. All processes 
must be killed unclearly, and the terminal mustn’t be killed, terminated, or hanged. 
(Justify your command line)

8. Question#8: Create a variable called myprj2var in your current bash shell with value 
project, then make sure that the variable myprj2var is passed from bash to ksh when you 
run a ksh shell under your bash shell. 

9. Question#9: Create a Prj2 directory under your home directory, add the directory to the 
end of your current PATH environment variable (temporarily) and display the value of 
the PATH variable on the screen.

10. Question#10: What is the difference between nice and renice commands? Give a usage 
example for each of them.


# Question 2:

1. Question#1: Display the login names (e.g., u1180111) of all users whose last name is 
Mohammad (all cases) and whose default shell is zsh.

2. Question#2: Display the first names of all unique users (all cases) in uppercase with 
comp322 as part of their home directory, sorted by the numerical value of their user ID numbers 
in descending order.

3. Question#3: Select all sh shell usernames (full name, separated by a space in uppercase) and 
save them to a file called sh_shellusers. 

4. Question#4: Save users from user number 15th to user number 20th into a user.txt file. The
name in this file should appear in uppercase and sorted in descending order (i.e., first name and 
last name separated by a space).

5. Question#5: Display the unique first names of all users (all cases) whose last names end with 
the letter between a-o, and save the result to the a_oSorted.txt file 

6. Question#6: List the full names (all in uppercase) sorted in descending order of all users 
whose shell is NOT zsh shell.

7. Question#7: List the last names of all users (sorted based on ID number in ascending). The
user that has a login name starts with u116. 

8. Question#8: Display all files in the (/etc.) directory that do not contain word passwd in 
these files page by page on the screen

9. Question#9: Display the number of directors in the /etc. The directory starts with any 
letters (a-k) for all cases. 

10. Question#10: List the initials (i.e., the first letter of the first name followed by the first 
letter of the last name) of all users with ksh as their default shell.
