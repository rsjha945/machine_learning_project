# machine_learning_project
This is a machine learning project

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

Buid Docker Image
``` 
docker build -t <image_name>:<tagname> .
```
> Note: image name for docker must be in lowercase

To list Docker image
```
docker images
```

To run docker image
```
docker run -p 5000:5000 -e PORT=5000 <image_id>
```

To check running container in docker
```
docker ps
```

To stop the docker container
```
docker stop <container_id>
```

```
python setup.py install
```