## Machine_Learning_project-1
This is my First Machine learning Project`

### Software & Account Requirements:- 

1. [Github Acount](https://github.com/)
2. [Heroku Acount](https://www.heroku.com/)
3. [VS code IDE](https://code.visualstudio.com/)
4. [GIT cli](https://git-scm.com/downloads)
5.[git documentatiuon](https://git-scm.com/doc)

Creating a conda vertual inviroment

Creating conda environment
```
conda create -p venv python==3.7 -y
```
```
conda activate venv/
```
OR 
```
conda activate venv
```

```
pip install -r requirements.txt
```

To Add files to git
```
git add .
```

OR
```
git add <file_name>
```

> Note: To ignore file or folder from git we can write name of file/folder in .gitignore file

To check the git status 
```
git status
```
To check all version maintained by git
```
git log
```

To create version/commit all changes by git
```
git commit -m "message"
```

To send version/changes to github
```
git push origin main
```

To check remote url 
```
git remote -v
```git add .

To setup CI/CD pipeline in heroku we need 3 information
1. RENDER_EMAIL = ramdasprajpati460@gmail.com
2. RENDER_API_KEY = rnd_QEpLjHJOT8FUUxn0Za4ORuzjeHzq
3. RENDER_APP_NAME = ml-regression-app 

BUILD DOCKER IMAGE
```
docker build -t <image_name>:<tagname> .
```
> Note: Image name for docker must be lowercase


To list docker image
```
docker images
```

Run docker image
```
docker run -p 5000:5000 -e PORT=5000 f8c749e73678
```

To check running container in docker
```
docker ps
```

Tos stop docker conatiner
```
docker stop <container_id>
```