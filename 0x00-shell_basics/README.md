1. Write a script that prints the absolute path name of the current working directory.
#!/bin/bash
pwd

2. Display contents of the current working directory
#!/bin/bash
ls

3.  Write a script that changes the working directory to the user’s home directory.
#!/bin/bash
cd /root

4. Display current directory contents in a long format
#!/bin/bash
ls -l

5. Display current directory contents, including hidden files (starting with .). Use the long format.
#!/bin/bash
ls -la

6.  Display current directory contents.
	a. Long format
	b. with user and group IDs displayed numerically
	c. And hidden files (starting with .) 
#!/bin/bash
ls -lna

7. Create a script that creates a directory named my_first_directory in the /tmp/ directory.
#!/bin/bash
mkdir tmp/my_first_directory

8. Move the file betty from /tmp/ to /tmp/my_first_directory
#!/bin/bash
mv tmp/betty tmp/my_first_directory

9. Delete the file betty. The file betty is in /tmp/my_first_directory
#!/bin/bash
rm tmp/my_first_directory/betty

10. Delete the directory my_first_directory that is in the /tmp directory
#!/bin/bash
rm tmp/my_first_directory

11.  Write a script that changes the working directory to the previous one
#!/bin/bash
cd ..

12. Write a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
ls -al ./../boot

13. Write a script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script
#!/bin/bash
file tmp/iamfile

14. 
