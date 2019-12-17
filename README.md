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
#### When  working on backend, don't forget to activate the virtual environment with :
```
$ source .env/scripts/activate
```
#### To deactivate virtual environment, simply run :
```
$ deactivate
```
