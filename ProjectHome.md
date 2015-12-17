IChatbot: MSN chatbot written in Python

### Python libraries used: ###
  1. Alberto Bertogli's msnlib
  1. Cort Stratton's PyAIML
> These libs are **already included** in the package, no separate download is needed.

### Prerequisite: ###
  1. Python version >= 2.2.2
  1. fortunes and fortune-zh, both are optional by removing the line
> > clist=[fortune, fortunezh]
  1. Windows Live ID (for robot)

### Install and run ###
  1. Check out latest repository

> svn checkout http://ichatbot.googlecode.com/svn/trunk/ ichatbot-read-only
  1. Open chatbot.py, change chatbot MSN email, password, botname and admin\_email
  1. Change your bot profile in chatbot.ini such as chatbot's name, master, birthplace etc
  1. run ./chatbot.py and your robot is ready for chat on MSN
  1. say 'help' to your bot on MSN to list available commands
> Notice: It may take **minutes** to load aiml databases for the first time run, be patient

### Sample robot: ###
> add albert@huichen.org to your friend list

### Note: ###
> MSN protocal may change a lot in future, please keep an eye on msnlib's webpage if newer version is released. For updating msnlib, you only need to replace msnlib.py and msncb.py files.