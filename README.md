# Sample C4 Diagrams with Structurizr Lite

This repo is built from instructions from [Getting started with Structurizr Lite](https://dev.to/simonbrown/getting-started-with-structurizr-lite-27d0).

## Install
Make sure you have [Docker installed](https://docs.docker.com/get-docker/) and enter the following in a console:

```
git clone git@github.com:dwhelan/c4-simple.git
cd c4-simple
docker pull structurizr/lite
```

## Run

**macOS or Linux**
```
docker run -it --rm -p 8080:8080 -v `pwd`:/usr/local/structurizr structurizr/lite
```

**Windows Powershell**
```
docker run -it --rm -p 8080:8080 -v $pwd:/usr/local/structurizr structurizr/lite
```

**Windows Command**
```
docker run -it --rm -p 8080:8080 -v %CD%:/usr/local/structurizr structurizr/lite
```

Browse to http://localhost:8080 to see the generated diagrams.

If you are running macOS or Linux you can simply use the `run` script:

```
./run
```

You can pass the port you want to use for Structurizr if port 8080 is in use:

```
./run 8888
```
