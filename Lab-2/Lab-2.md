# CPE 322 - Lab 2 
## Command Line 
--- 
### Introduction 
This lab focuses on utilizing some basic standard terminal commands to accomplish basic system, information, and file-related tasks. Most common systems utilize similar commands for their basic command line tasks, so I began by opening a Windows command prompt, as I currently have a Windows system. 

### Commands 
The lab began with the usage of several basic commands. 

#### Command 1: `hostname` 
This simple command returns and displays the hostname of the system, which is its identifying label, as shown below. 

![hostname Command](hostname.png)

#### Command 2: `env` 
This command displays the environment variables for the system, which control various file paths and processes within the system. 

![env Command](env.png)
![env Command Continued](env2.png)

#### Command 3: `ps` 
This command lists and displays basic information about running processes within the system. 

![ps Command](ps.png)

#### Command 4: `pwd` 
This command displays the path to the current working directory in the command terminal. 

![pwd Command](pwd.png)

#### Command 5: `git clone` 
This command invokes the Git program to copy a directory from a remote source to the current directory, which in this case is the IOT GitHub repository. Git needed to be installed manually to be utilized within the Windows command prompt, as it is not a common built-in utility on Windows. However, after being installed, the command worked properly and downloaded the IOT repository. 

![git clone Command](git_clone.png)

#### Command 6: `cd iot`
This command sets the current working directory to the directory specified, which in this case is the 'iot' directory. 

![cd iot Command](cd_iot.png)

#### Command 7: `ls`
This command lists the files and other directories within the current working directory. 

![ls Command](ls.png)

#### Command 8: `cd`
This command, which is 'cd' without any directory path following it, simply lists the current working directory, but in a Windows file path format unlike pwd. Notably, on Unix-based systems, this command will change the directory to the home directory without any arguments. 

![cd Command](cd.png) 
![cd Command On Unix-like Terminal](cd2.png)

#### Command 9: `df`
This command lists filesystems on the system with basic information, such as storage usage. 

![df Command](df.png) 

#### Command 10: `mkdir demo`
This command creates a new directory within the current working directory. In this case, the directory is named 'demo'.  

![mkdir Command](mkdir.png) 

#### Command 11: `cd demo`
The cd command is used again to set the current working directory to the demo directory. 

![cd demo Command](cd_demo.png) 

#### Command 12: `nano file`
This command opens a file in nano, which is a command-line text editor. The text 'file' was written manually into the new file with the text editor, and the file was then saved to the current working directory. 

![nano file Command](nano_file.png) 

#### Command 13: `cat file`
This command prints the contents of the file in the arguments, which in this case contained the word 'file'. 

![cat file Command](cat_file.png) 

#### Command 14: `cp file file1`
This command copies the first file argument to the second file argument under the file name in the second argument. After the copy operation, 2 files remained in the directory. 

![cp Command](cp_file_file1.png) 
![Files present after copy](cp1)

