## Conda Cheatsheet:
https://conda.io/docs/user-guide/cheatsheet.html

## Multiple Python environments:

Open Anaconda Prompt to command execution  

*conda create -n py37 python=3.7 anaconda*: create a new environment. Its name is py37.  
*conda info --envs*: show all environments  
*activate py37*: activate the environment py37 to use python 3  
*deactivate*: deactivate py37  

## Manage packages:

*conda list*: show all packages installed in the env  
*conda search beautifulsoup4*: search available packages named as beautifulsoup4  
*conda install beautifulsoup4*: install package beautifulsoup4 in the env  
