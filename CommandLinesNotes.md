#_Linux The Commmand Line Notes_

CommandLine-
A command line, or terminal, is a text based interface to the system. You are able to enter commands by typing them on the keyboard and feedback will be given to you similarly as text.
*Line 1*- 
presents us with a prompt ( user@bash ). After that we entered a command ( ls ). Typically a command is always the first thing you type. After that we have what are referred to as command line arguments ( -l /home/ryan ). Important to note, these are separated by spaces (there must be a space between the command and the first command line argument also). 
*Lines 2-5*-
 are output from running the command. Most commands produce output and it will be listed straight under the issuing of the command, Other commands just perform their task and don't display any information unless there was an error.
*Line 6*- 
presents a prompt again. After the command has run and the terminal is ready for you to enter another command the prompt will be displayed. If no prompt is displayed then the command may still be running (you will learn later how to deal with this).

*Opening a MAC's Terminal*
find the program Terminal under Applications -> Utilities. An easy way to get to it is the key combination 'command + space' which will bring up Spotlight, then start typing Terminal and it will soon show up.
Opening a Windows/ Linux's Terminal- 
find it in Applications -> System or Applications -> Utilities. Alternatively you may be able to 'right-click' on the desktop and there may be an option 'Open in terminal'.
If you are on Windows and intend to remotely log into another machine then you will need an SSH client.
*The Shell*-
 part of the operating system that defines how the terminal will behave and looks after running (or executing) commands for you. There are various shells available but the most common one is called bash which stands for Bourne again shell. 
 *Echo*-
  use a command called echo to display a system variable stating your current shell. echo is a command which is used to display messages.
#Basic Navigation-
 PWD stands for Print Working Directory. -tells what your current or present working directory is. 
 *Paths*-
 There are 2 types of paths we can use, absolute and relative. Whenever we refer to a file or directory we are using one of these paths. Whenever we refer to a file or directory, we can, in fact, use either type of path (either way, the system will still be directed to the same location).
 *Absolute*- paths specify a location (file or directory) in relation to the root directory. You can identify them easily as they always begin with a forward slash ( / )
Relative- paths specify a location (file or directory) in relation to where we currently are in the system. They will not begin with a slash.
*LS*-
List the contents of a directory
*CD*-
Change Directories - ie. move to another directory.
*File*-
obtain information about what type of file a file or directory is.
*ls -a*-
List the contents of a directory, including hidden files.
