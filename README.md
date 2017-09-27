# Proj0-Hello

Author: Mikaela Schaefer

Contact: kaela_anne@hotmail.com

## Description
The python program hello.py outputs the message which is specified
in the credentials file that should be housed on the user's home computer.
A template for the credentials file is included in the repo as 
credentials-skel.ini.

The makefile has two rules, install and run. Install is unnecessary, but
run will change the current working directory and run hello.py. For the
rule to execute correctly, credentials.ini must be in stored in the hello
directory.
