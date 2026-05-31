# learning-python
A small python script using pandas 

This code uses "pandas" after its installed using the "pip" command .
Instead of directly installing the libraries into the OS space which can cause dependency issues , its safer and preferred to create a virtual environment first.
So using built in tool like "venv" is preferred for light weight environments.
In linux and mac OS  and also windows(though the commands are different from linux and macos) , you can create a virtual , isolated environemt using the command "python version -m venv ."a name of your wish".
For example since my python version is 3.13 and I would like to name my virtual environment directory just "file"(dot files are hidden) and  the command would be ,"python3.13 -m venv .file".
And to activate the environment , the command is "source .file/bin/activate".
Now you are in an isolated , safe , virtual environment .
Next install the library you need for this program to run , which is "pandas".
To install it , type "pip install pandas".
Now open a text editor , such as vs-code or even your built in text editor.I am using nano directly in the terminal.
To create a file using nano ,type "nano pythonfile.py'.
Refer the code in "code" file , then save it using "ctrl+o" and "ctrl+x" to exit the nano editor .
Now execute using the command , "python pythonfile.py".
Refer the output , in the "output" file .
You will see the output in a table like form , consisting of all parameters .
This is due to the line "df = DataFrame(data)", this takes the values inside the variable "data" , and "DataFrame" is a blueprint for two dimensional tabular structure .
