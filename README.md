# Altoscholarship

#### About Submodules
As you can see, Frontend and Backend folders are submodules.
Thus, to clone the whole project including both submodules you should type the following :
```
$ git clone --recurse-submodules https://github.com/chloebalcer/Altoscholarship.git
```
For more information about submodules, check [git submodules](https://git-scm.com/book/fr/v2/Utilitaires-Git-Sous-modules).

#### Build project with :
```
$ docker-compose -f docker-compose.dev.yml up --build
```
### Virtual Environment
#### When  working on backend, don't forget to create a virtual environment.
```
$ virtualenv <nameofmyvirualenv>
$ source .env/scripts/activate
```
Once you've activated your virtual environment, put it inside .gitignore file from the root directory.
Now, you can install all the dependencies from the requirements.txt file.
```
$ pip install -r requirements.txt
```
In case you've installed a new library, you can add it to th requirements.txt file with :
```
$ pip freeze > requirements.txt
```
#### To deactivate virtual environment, simply run :
```
$ deactivate
```
### Save my progress

You should always remember that you are working with submodules. It is thus important to push new content firstly into the submodule you are working on and then push it into the main repository.
