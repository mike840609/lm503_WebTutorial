 ## Demo
 Deploying django project on heroku

video : https://www.youtube.com/watch?v=fDF14AMZixA&t

 Demo : https://django402401606.herokuapp.com/

## Requirements
- python 3.5

## Installation
- Create a virtual environment for a project: 
```bash
  
  $ cd desktop/lm503_WebTutorial/
  
  $ python -m venv myvenv
```

 ##### Virtualenv will isolate your Python/Django setup on a per-project basis.
- Start your virtual environment by running: 
```bash
    win :
    $ myvenv\Scripts\activate
    osx : 
    $ source\myvenv\bin\activate
```
- Generate pip requirements.txt:
```bash

    (optional)
    $ pip install --upgrade pip 
    $ pip install django~=1.10.0
    $ pip install django-toolbelt
    $ pip install dj-database-url gunicorn whitenoise
    $ pip freeze > requirements.txt
    

```

- Installing requirements.txt:
```bash

    $ pip install -r requirements.txt

```

- Heroku Deployment :
```bash
  
   $ heroku create 'heroku_name'


   $ heroku git:remote -a 'your heroku project_name'
   
   $ rm -rf .git (osx)    
   $ rmdir /s/q .git(ms-dos)

   $ git init 
   $ git add .
   $ git commit -m "initialize"
   $ git push heroku master
```

- git revise(optional):
```bash
    - remote list:  
        $ git remote -v
    - delete remote git : 
        $ git remote rm  'git_name'
```
## Usage
You just need to revise the index.html file and deployed it on the heroku,
then you can use any device to access the website which you deployed.