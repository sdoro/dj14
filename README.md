
# workspace for [45]SX classes

## Requirements (only for 5Sx classes)

1. You've completed (at least most of) Learn Python the Hard Way: http://learnpythonthehardway.org/

2. You've completed the official Django tutorial, also known as the Polls tutorial: https://docs.djangoproject.com/en/1.4/intro/tutorial01/

3. You're here: (http://c9.io/)

## Setup github and c9.io workspace (the easy way)

1. Create a github repository (e.g. dj14)
2. Enter in demo-project c9.io workspace and copy your ~/ssh/id_rsa.pub key into https://github.com/settings/ssh
3. Create a new workspace in c9.io filling with the previous generated github repository (e.g. dj14) into field named "Clone from Git or Mercurial URL".

Now the github *origin* IS in github.com:

    $ git remote -v
    origin  git@github.com:sdoro/dj14.git (fetch)
    origin  git@github.com:sdoro/dj14.git (push)


## Using git

From now on we can use git commands as usual:

    make 'some' changes      # localy       # where: c9.io
    git add                  # localy       # where: c9.io
    git commit               # localy       # where: c9.io
    git push                 # remotely     # where: github.com


## Using github repository

From c9.io dashboard select repository; then c9.io opens automaticaly a workspace connected with the selected repository.


## Using requirements.txt file

You can generate requirements.txt file from inside your particular virtual environment with:

    pip freeze > requirements.txt
    
You can gerate you particular environment using requirements.txt file typing from your environment:

    pip install -r requirements.txt
    
    