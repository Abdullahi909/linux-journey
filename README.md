# linux-journey

Creating editing and searching file commands 

I have learnt some file creating and editing commands in Linux 

Touch – this command creates and empty file.
	Example of this, touch testfile.txt

Echo- this command allows users to print text or variables in a file.
	Example of this, Echo “Hello world” >> testfile.txt

Cat- this command lets users see the contents of the file 
	Example of this, cat testfile.txt 
				Output “Hello world”

Grep- the command lets users search for specific texts inside files.
	Example of this, grep “Hello” testfile.txt
				Output “Hello world” (Hello is highlighted)






Shell programmes and binary

Bash – Born again shell 

Echo $SHELL – This command lets users see what shell they are using 
		Output: /bin/bash, this is because I am using the bash shell 

Echo $PATH- In the command PATH is the environment variable and the $ expands its value: a list of directories that Linux searches (in order) when you run commands.
        Output: /usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/usr/games:/usr/local/games:/snap/bin

A shell is a user interface that allows user to communicate with the operating system. It is between the user and the OS. Which translates user commands to actions.

Cat/etc/shells- prints the configured shell files contents on the operating system
                                        
																					
