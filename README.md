# ML_Proj

Machine Learning Project

1. [Github Account](https://github.com)
2. [Heroku Account](https://dashboard.heroku.com/login)
3. [VS Code IDE](https://code.visualstudio.com/download)
4. [GIT cli](https://git-scm.com/downloads)
5. [GIT Documentation](https://git-scm.com/docs/gittutorial)

creating conda environment run in command prompt

```
conda create -p venv python==3.7 -y
```

```
conda activate venv/
```

or

```
conda activate venv
```

```
pip install -r requirement.txt
```

to add a file to git

```
git add . to add all file
```

or

```
git add <file_name>
```

Note: to ignore file or folder we can write the file/folder name in .gitignore file

to check git status

```
git status
```

to check all version maintained by git

```
git log
```

to create version/commite all changes by git

```
git commit -m "message"
```

to send version/changes to git

```
git push origin main
```

to check remote url

```
git remote -v
```

To setup CI/CD pipeline in heroku we need 3 information

1. HEROKU_EMAIL = darshand56@gmail.com
2. HEROKU_API_KEY = 51abe883-96e9-49c0-b436-e5d68561e170
3. HEROKU_APP_NAME = ml-regre-app

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
