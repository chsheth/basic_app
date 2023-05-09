# basic_app
Trying github actions through a basic flask app

# Create environment
```
conda create -p venv python -y
```
# Activate env
```
conda activate venv/
```
# Create requirements.txt

```
pip install -r requirements.txt
```

# Git commands
```
git status
git add .
git commit -m <>
git push -u origin main
git remote -v
git log
git branch
```
# Operating through branches



# CI/CD pipeline through render

# BUILD DOCKER IMAGE




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
To stop docker conatiner
```
docker stop <container_id>
```

python setup.py install
Install ipykernel

pip install ipykernel