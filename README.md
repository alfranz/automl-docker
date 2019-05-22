:whale: AutoML - A Docker image for automated machine learning


Based on the scipy-jupyter Docker image with [auto-sklearn](https://automl.github.io/auto-sklearn/master/index.html) installed.

## Usage

```
docker pull alfranz/automl

docker run --rm -p 8888:8888 -e JUPYTER_ENABLE_LAB=yes -v "$PWD":/home/jovyan/work automl:v1
```


