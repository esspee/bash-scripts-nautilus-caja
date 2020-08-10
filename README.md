# bash-scripts-nautilus-caja

# Requirements
Any linux distribution with nautilus file manager or caja file manager. No specific requirements are needed.

# Conventions 	
requires to be executed with root privileges.

# Creating the scripts directory
The first thing we want to do is to create the directory that will host our scripts. 

For nautilus file manager: mkdir -p ~/.config/nautilus/scripts
For caja file manager: mkdir -p ~/.config/caja/scripts

Copy the scripts into this directory and make them executable (chmod +x script_name).
Once placed in this directory, the scripts will automatically appear in the Nautilus context menu displayed when we select one or more files.

Notice that they will be correctly included in the Nautilus context menu only if they are made executable. Before writing code we should learn to know some variables we can use inside the scripts, they are the main way we can interact with the status of the file manager, accessing very useful information.
