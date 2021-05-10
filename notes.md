Before you start create a directory for your project
1. check your python version make sure you are running python 3
--in termal enter "python - V"
2. create virtual environment
--in terminal type "python -m venv kekambas_venv"
3. activate the virtual environment by runing the activate.bat You have to activate every time you open VScode (unless you tell VScode to run it automatically)
--in terminal enter in "kekambas_venv\Scripts\activate"
--once the ven has been activated you'll see (kekambas_env) in your terminal
Note- to deactivate your venv, type "deactivate" into the cmd
4. lets use pip to install flask
--pip install flask
Note- What is Pip? "python package manager" 
5. so now if you run pip list in the cmd it will show new items such as Flask, itsdangerous etc. and the version numbers. Pay attention to what versions you are using when you start your project because you'll need to use those version for your applications lifetime. So if there's an automatic update and if the new vversion of the package no longer supports some aspects of your code, then it will break your code. So you need to keep track of which versions you used when you created your program. 
------------in the CMD--------
(kekambas_venv) C:\Users\User1\Desktop\Jessica\Coding_Temple\Week5\Intro_to_Flask>pip list
--but what we really want is pip freeze
(kekambas_venv) C:\Users\User1\Desktop\Jessica\Coding_Temple\Week5\Intro_to_Flask>pip freeze
click==7.1.2
Flask==1.1.2
itsdangerous==1.1.0
Jinja2==2.11.3
MarkupSafe==1.1.1
Werkzeug==1.0.1
--save pip freeze to a text file
(kekambas_venv) C:\Users\User1\Desktop\Jessica\Coding_Temple\Week5\Intro_to_Flask>pip freeze > requirements.txt
---------------
Note: later you could use the requirements.txt to create a new virtual environment 
--create new venv
--active it
--install all the correct versions of the packages in your requirments.txt
--do this by entering this into cmd "pip install -r requirements.txt"
The requirements.txt is just a list of required packages and versions. So any user can grab the project's requirements.txt and use that to create their own matching venv. 



