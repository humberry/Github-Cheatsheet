Github-Cheatsheet
=================

StaSh v0.6.1  

[~/Documents]$ **mkdir Github**  

[~/Documents]$ **cd Github**  

[Github]$ **mkdir ui-tutorial**  

[Github]$ **cd ui-tutorial**  

[ui-tutorial]$ **git clone https://github.com/humberry/ui-tutorial.git**  

[ui-tutorial]$ **ll**  

.git (374.0B) 2016-02-16 21:27:36  
...  
MiniPhotoView.py (3.4K) 2016-02-16 21:28:55  
...  

[ui-tutorial]$ **edit MiniPhotoView.py**  

[ui-tutorial]$ **git status**  

STAGED
UNSTAGED LOCAL MODS
['MiniPhotoView.py']

[ui-tutorial]$ **git add MiniPhotoView.py**

Adding MiniPhotoView.py

[ui-tutorial]$ **git commit**

Commit Message: remove touch and layout method

Author Name: humberry

Save this setting? [y/n]y

Author Email: 

Save this setting? [y/n]y

shivrztvhf...

[ui-tutorial]$ **git push**

Attempting to push to: https://github.com/humberry/ui-tutorial.git, branch: refs/heads/master

Enter username: humberry

Enter password: mysecretpassword

Push to https://humberry:mysecretpassword@github.com/humberry/ui-tutorial.git successful.

success!
