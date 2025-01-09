Bash Script for Keyword Search in System Logs
The task was completed on the TryHackMe platform as part of an educational program. All actions and tasks were performed in compliance with the platform's rules and are entirely legal.

The objective of the project was to create a Bash script that automates the search for a specific keyword within system log files. The script scans files with the .log extension in a specified directory and outputs the file(s) containing the keyword. The implementation involved developing a Bash script that utilized loops and variables to automate the task, configuring the script to define the search directory and keyword, and testing it in a Linux environment.

Key steps included preparing the script by opening the search_log_script.sh file in the nano text editor and editing it to set the directory (/var/log) and keyword (thm-flag01-script). Changes were saved using Ctrl + O to write the changes and Ctrl + X to exit the editor. The script was granted execution permissions with chmod +x search_log_script.sh and executed using ./search_log_script.sh. The script successfully displayed the name of the file and the line containing the keyword, for example: /var/log/authentication.log:thm-flag01-script.

Tools used in the project included Linux for terminal operations and file management, Bash for scripting and automation, and Nano for file editing. The project demonstrated the ability to write effective Bash scripts, edit files via the terminal, manage file permissions, and automate repetitive tasks successfully.
