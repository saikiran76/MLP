# MLP
Deployable Machine Learning Project

1) Creating Conda Environment 
```
conda create -p venv python==3.7 -y
```
2) Activate your venv
```
conda activate venv 

OR

conda activate venv/
```

3) Create you requirements.txt file and install the requirements
```
pip install -r requirements.txt

```

4) HEROKU CREDENTIALS

5) BUILD DOCKER IMAGE

```
docker build -t <image_name>: <tagname> .
```
> Note: Image name for Docker must be lowercase

To list Docker Image
```
docker images
```

Run docker image
```\
docker run -p 5000:5000 -e PORT = 5000 f8c749e738
```

To check running container in docker

```
docker ps
```

To stop container
```
docker stop <container_id>
```

