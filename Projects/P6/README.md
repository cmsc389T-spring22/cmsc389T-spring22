# Project 6 Base Image

The files included in this directory allow you to create a docker image with python and twilio preinstalled. You can create a container by running

```
docker build -t project6 .
```

When you want to connect to this container, just run

```
docker run -it project6 bash
```
