Coding-Cafe

Question 1
pwd printed /Users/jaymangukiya. It showed the current working directory, This is my home folder.

Question 2
ls -a showed hidden files that plain ls did not show. These included other files like .config and much more.

Question 3
The first column of ls -l shows information about the file type and permissions. i learned d means directory and - means regular file.

Question 4
It works because I am in my home directory, where the coding-cafe folder is present. coding-cafe/week02 is a diffrent because it starts from my current directory instead of starting from /.

Question 5
The first (mv) moved README-backup.md from the coding-cafe folder into the week01 folder. The second (mv) renamed README-backup.md to old-readme.md while keeping it in the same folder.

Question 6
There are 15 folders on my PATH. They are separated by : .

Question 7
The command (which python3) printed (/opt/miniconda3/bin/python3). This is the location of the python3 that my shell is currently using.

Question 8
Our (python3) paths were different. This can happen because Python can be installed in different locations on different computers.

Question 9
The shell said (zsh: command not found: pyton3). This happened because I typed (pyton3)  instead of (python3). The shell searched the directories in my PATH for a command called (pyton3), but it could not find any.

Question 10
The (.venv) folder did not appear with plain (ls) because it starts with a dot, so it is a hidden file/folder. The (ls -a) command shows hidden files and folders.

Question 11
Before activating the virtual environment, my prompt started with ( (base) ). After running (source .venv/bin/activate), ((.venv)) appeared at the beginning, showing that the virtual environment is active.

Question 12
No, the paths are different. Before activation, Python came from Miniconda, but after activation it comes from my project's (.venv), showing that activating the virtual environment changed my PATH to use the Python inside (.venv).

Questios 13
The second list contains requests and its dependencies: certifi, charset-normalizer, idna, and urllib3. These were not present in the first list.

Question 14
After deactivating the virtual environment, python3 points back to /opt/miniconda3/bin/python3. This shows that deactivation restored the original PATH.

Question 15 
ls -h shows file sizes in a human-readable format, such as KB, MB, or GB, instead of only showing the size as a number of bytes.

Question 16 
Ctrl+C interrupted the running Python session and showed KeyboardInterrupt, but it kept me inside Python at the >>> prompt. Ctrl+D signaled the end of the input and exited Python, returning me to the normal Terminal prompt.