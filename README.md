# ECI

ShellCode
------------

###  Steps to execute a shell script

Create a new file using a text editor such as nano or vi in Linux: 


    $  nano filename.sh
    
Set the script executable permission by running chmod command in Linux:

    $  chmod +x filename.sh
    
Execute a shell script in Linux

    $  ./filename.sh
    or
    $ bash filename.sh


This  Repository contains Code worked during Devops training

PythonCode
------------

### Requirements

You need Python 3.5 or later to run mypy.  You can have multiple Python
versions (2.x and 3.x) installed on the same system without problems.

In Ubuntu, Mint and Debian you can install Python 3 like this:

    $ sudo apt-get install python3 python3-pip

Another way to download Python using following command from python official site.
    
    wget https://www.python.org/ftp/python/2.7.18/Python-2.7.18.tgz
    
After that we have to extract downloaded archive using tar command.
     
    tar xzf Python-2.7.18.tgz
    
To check version of installed python using following command.
    
    /usr/local/bin/python2.7 -V
    
PIP is a useful utility to install and manage Python modules. Using following link for installing the PIP for the installed Python version.

    curl "https://bootstrap.pypa.io/get-pip.py" -o "get-pip.py"
    
### To Run Python Program
    
For creating python file we are using .py extension 
For executing python code following command is used
    
    python3 filename.py
