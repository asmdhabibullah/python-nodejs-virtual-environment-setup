**If You want to be a Web Programmer by the help of Python django for backend, React-Redux for font-end then you need to setup Virtual-Environment on your Operating system.**
===================================================================================================================

If your Operating system is Ubuntu 18.4.1 LTS or Windows 10.
Lets go==> to Environment setup for Python and Nodejs.
------------------------------------------------------------
Python 3 Virtual-Environment on Ubuntu 18.04.1LTS
-------------------------------------------------

```
sudo apt update
sudo apt -y upgrade
python3 -V
Python 3.6.5
sudo apt install -y python3-pip
sudo apt install build-essential libssl-dev libffi-dev python3-dev
sudo apt install -y python3-venv
```

Finish python setup.


Nodejs, Npm, yarn and create-react-app installation for Virtual-Environment on Ubuntu 18.04.1LTS.
-------------------------------------------------------------------------------------------------
```
sudo apt update
sudo apt install nodejs npm
sudo apt install curl
curl -sL https://deb.nodesource.com/setup_10.x | sudo bash -
sudo apt install nodejs
nodejs --version
v10.15.1
npm --version
6.4.1
sudo npm install npm@latest -g
6.8.0
sudo npm install yarn -g
yarn --version
1.13.0
sudo npm install -g create-react-app
create-react-app --version
2.1.5
```

Finish Node setup.


Now we create a Project by the help of Python,django and Reactjs.
------------------------------------------------------------------
Create a Directory on Desktop or any where.
-------------------------------------------
```
mkdir DjReact
cd DjReact
asmdh@x1:~/Desktop/DjReact
asmdh@x1:~/Desktop/DjReact$ python3.6 -m venv penv

Activate Virtual Environment

source penv/bin/activate
(penv) asmdh@x1:~/Desktop/DjReact$
(penv) asmdh@x1:~/Desktop/DjReact$ pip install django
Collecting django
  Downloading https://files.pythonhosted.org/packages/c7/87/fbd666c4f87591ae25b7bb374298e8629816e87193c4099d3608ef11fab9/Django-2.1.7-py3-none-any.whl (7.3MB)
    100% |████████████████████████████████| 7.3MB 21kB/s 
Collecting pytz (from django)
  Downloading https://files.pythonhosted.org/packages/61/28/1d3920e4d1d50b19bc5d24398a7cd85cc7b9a75a490570d5a30c57622d34/pytz-2018.9-py2.py3-none-any.whl (510kB)
    100% |████████████████████████████████| 512kB 28kB/s 
Installing collected packages: pytz, django
Successfully installed django-2.1.7 pytz-2018.9
django-admin --version
2.1.7
django-admin startproject backapp
(penv) asmdh@x1:~/Desktop/DjReact$ cd backapp/

(penv) asmdh@x1:~/Desktop/DjReact/backapp$ ls
backapp  manage.py
(penv) asmdh@x1:~/Desktop/DjReact/backapp$ python manage.py runserver
Performing system checks...

System check identified no issues (0 silenced).

You have 15 unapplied migration(s). Your project may not work properly until you apply the migrations for app(s): admin, auth, contenttypes, sessions.
Run 'python manage.py migrate' to apply them.

February 17, 2019 - 12:41:41
Django version 2.1.7, using settings 'backapp.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CONTROL-C.


(penv) asmdh@x1:~/Desktop/DjReact/backapp$ deactivate
asmdh@x1:~/Desktop/DjReact/backapp$
```


Now create react application.
------------------------------
```
asmdh@x1:~/Desktop/DjReact$ create-react-app fontapp

If you finish create react app then show to screen like this=>
Creating a new React app in /home/asmdh/Desktop/DjReact/fontapp.

Installing packages. This might take a couple of minutes.
Installing react, react-dom, and react-scripts...

yarn add v1.13.0
[1/4] Resolving packages...
[2/4] Fetching packages...
info There appears to be trouble with your network connection. Retrying...
info There appears to be trouble with your network connection. Retrying...
info There appears to be trouble with your network connection. Retrying...
info There appears to be trouble with your network connection. Retrying...
info fsevents@1.2.7: The platform "linux" is incompatible with this module.
info "fsevents@1.2.7" is an optional dependency and failed compatibility check. Excluding it from installation.
info fsevents@1.2.4: The platform "linux" is incompatible with this module.
info "fsevents@1.2.4" is an optional dependency and failed compatibility check. Excluding it from installation.
[3/4] Linking dependencies...
warning "react-scripts > pnp-webpack-plugin > ts-pnp@1.0.0" has unmet peer dependency "typescript@*".
[4/4] Building fresh packages...
success Saved lockfile.
success Saved 4 new dependencies.
info Direct dependencies
├─ react-dom@16.8.2
├─ react-scripts@2.1.5
└─ react@16.8.2
info All dependencies
├─ react-dev-utils@7.0.3
├─ react-dom@16.8.2
├─ react-scripts@2.1.5
└─ react@16.8.2
Done in 79.61s.

Success! Created fontapp at /home/asmdh/Desktop/DjReact/fontapp
Inside that directory, you can run several commands:

  yarn start
    Starts the development server.

  yarn build
    Bundles the app into static files for production.

  yarn test
    Starts the test runner.

  yarn eject
    Removes this tool and copies build dependencies, configuration files
    and scripts into the app directory. If you do this, you can’t go back!

We suggest that you begin by typing:

  cd fontapp
  yarn start

Happy hacking!


cd fontapp
asmdh@x1:~/Desktop/DjReact$ cd fontapp/
asmdh@x1:~/Desktop/DjReact/fontapp$ npm start

Or
yarn start

Compiled successfully!

You can now view fontapp in the browser.

  Local:            http://localhost:3000/
  On Your Network:  http://10.100.245.175:3000/

Note that the development build is not optimized.
To create a production build, use yarn build.

```



Command For Windows.
---------------------
Start First stap for setup Pc Globally.
Download Python 32/64 bit is your matien capability from: python.org

01.Now install Python.

02.When istallation is compleate then Goto Python script file. Like this: C:\Programs\Python37\Scripts. Copy the path of instalation.

03.Now goto Windos propartis option => goto Advanced System => Environment Variable => Click New => Past the link of python path, that you already copy. Finally Click Save button.

Open windows powershell administrator mode. Wright the comment.
```
pip install virtualenv
virtualenv --version
pip Install virtualenvwrapper-win
```

First stap Complate.
Start Secont Step for project.
Create a Directory
----------------------
cd Directory

Goto any Drive Like this: C: or any folder Desktop Create New folder => Goto folder => Click the button of shift + right button of mous => Open poweshel here.

Now wright the commend again.
```
mkvirtualenv (any name, this is your own choise name)
Like this: mkvirtualenv penv

Now wright created own name like(penv) and enter for active environment.

Now Showing:
(penv) c:\User\Desktop:
`````
```
Thanks
Abu Sayem Md Habibullah
Yunnan University, Kunming, China
Computer Science & Technology
```