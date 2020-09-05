To perfectly deploy our web app on your local server, you need to follow the following steps:
  
  NOTE: These steps are work more effectively if user runs it on WINDOWS (10 specifically.)


1. An offline IDE to actually see and open the entire code (VS CODE or Pycharm) any one would work great.
2. You need to have latest version of python(3.8.5) installed on your system and set the PATH accordingly.
3. Since our project requires many python modules ( for eg., nltk, bs4,etc..) therefore it is advisable to download ANACONDA distribution, which comes with maximum modules installed with it.
4. Incase still some modules are 'not found' refer to our 'requirements.txt' provided in the project folder and manually do pip install 'name-here' to set up all the modules.
5. To open the database files 'notes.db' and 'login.db' download the sqlite3 database browser using this link (https://sqlitebrowser.org/) and set PATH accordingly.
6. In case of any 'DATABASE LOCKED ERROR' refer this link 'https://stackoverflow.com/questions/151026/how-do-i-unlock-a-sqlite-database'.
7. To work with the python-vlc module you need to have 'VLC - 64 Bits' downloaded on your system. ('Make sure to recheck the version since older are not compatible eith latest versions of python.')
8. Set PATH for your VLC downloaded on your system.
9. Note that the other additional files provided in the project folder('Procfle','requirements.txt','nltk.txt' etc.. are for deployment purpose and therefore need not considered for running the project locally. )
 10. Once done , open command prompt go to the project folder and run 'python back.py'.
 11. It will start on local server and give you the localhost. Copy paste on your browser and start exploring the project.
 
