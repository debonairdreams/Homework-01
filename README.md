Homework 01
Due date: Jan. 30, 2018
Points: 15 pt.
Final contents of repository (no other files/folders should be included):
README.md
answers.txt
.gitignore
The purpose of your first homework assignment is to get familiar with the tools/environments that we use in this class.

You should create a new file named answers.txt and record your responses for Tasks 1 and 2.

Task 1: Connecting to remote machines (5 pt.)
Let's see if you can successfully connect to a remote machine. We will use SSH to securely connect to a remote machine, in this case the University's machine itsunix.albany.edu. You can use your NetID/password to connect. Refer to our instructions for establishing SSH connection using command line for more information on how to connect.

Once connected, we ask you to compute hash values of certain files and report back. In particular, we ask you to calculate MD5 checksum.

Connect to the University machine itsunix.albany.edu using SSH protocol and your NetID/password.

Calculate MD5 hash value of file /etc/passwd as follows. This file contains user accounts in a Unix.

$ md5 /etc/passwd

Record the above hash value on 1st line of answers.txt

Let's calculate hash value of your home folder. We use command pwd to retrieve your current working directory, and feed the output to md5.

$ pwd | md5

Record the above hash value on 2nd line of answers.txt

So far, assuming you received hash values "25ba6" and "ab109" for above (MD5 values will be much longer than those), answers.txt should contain the following two lines:

25ba6

ab109

Task 2: Setting up your own Linux environment (4 pt.)
You can connect to the University machines remotely and use it for the purpose of this course. But let's make sure that you also have a local machine too. If you already have a Linux/Mac OS you can skip to the second step below.

If you're not running a Linux (or Mac), install one. You can refer to our instructions for installing Ubuntu. Installing as a virtual machine is probably the safest/cleanest option.

Run the following command to return all your system information.

$ uname -a

Record the output of the above command on 3rd line of answers.txt

Task 3: Git (6 pt.)
As you are setting up your system, make sure you also install Git for your Linux distro. Refer to Git reference manual and Pro Git book to review commands you need to perform for the following steps.

Read the gitignore reference. Create a .gitignore file that ensures your repository will ignore files with .bin extension anywhere in the repository (e.g., such as files/1.bin that is currently included in the repository).
You should add your .gitignore to the repository.

Remove everything except README.md, answers.txt, and .gitignore from the repository and make sure this is reflected on GitHub as well.
Ensure only the requested files exist in the repository (no other files/folders).
