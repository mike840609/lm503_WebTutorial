 ## Demo
 Deploying django project on heroku
  
 Demo : https://django402401606.herokuapp.com/

## Requirements
- python 3.5

## Installation
- Create a virtual environment for a project: 

```bash
$ cd /personal_website_path/
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
- Installing Django:
```bash
    $ pip install --upgrade pip
    $ pip install django~=1.10.0
```
- Database Migrate :
```bash
    $ python manage.py migrate
```


- Heroku Deployment :
```bash
   $ pip install django-toolbelt
   $ pip install dj-database-url gunicorn whitenoise
   $ heroku create 'heroku_name'
   
   $ pip freeze > requirements.txt
   
   $ rm -rf .git (osx)    
   $ rmdir /s/q .git(ms-dos)

   $ git init 
   $ git add .
   $ git commit -m origin master
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