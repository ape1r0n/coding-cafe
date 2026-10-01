pwd showed the full path of the folder I was currently in
ls -a showed hidden files and folders that plain ls did not show
The first column in ls -l shows the file type and its permissions
It works because coding-cafe is in my current location and coding-cafe/week02 is a relative path
mv was used to move the file to week01 and then rename it as old-readme.md
There are a lot of folders in my PATH separated by colons
My python3 is located at /opt/anaconda3/bin/python3
They might be different because Python can be installed in different places on different computers
The shell said pyton3 was not found because I typed the command wrong and it could not find it in my PATH
.venv did not show up with ls because it is a hidden folder
My prompt changed to show (.venv) which means the virtual environment was active
The path changed to the Python inside .venv which shows that activation changed my PATH
The second list had requests and its dependencies because I had just installed them
After deactivate python3 pointed back to the original Python location outside the virtual environment
ls -h shows file sizes in a more readable way using units like KB and MB
Ctrl + C stopped the running program while Ctrl + D told Python there was no more input