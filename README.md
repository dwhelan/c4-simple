# Sample C4 Diagrams with Structurizr Lite

This repo is built from instructions from [Getting started with Structurizr Lite](https://dev.to/simonbrown/getting-started-with-structurizr-lite-27d0).

To run this demo, clone or download it.

Make sure you have [Docker installed](https://docs.docker.com/get-docker/) and enter the following in a console:

```
docker pull structurizr/lite
docker run -it --rm -p 8080:8080 -v PATH:/usr/local/structurizr structurizr/lite
```

Be sure to replace `PATH` with the full path of this directory on your local file system.

Open your browser to http://localhost:8080 to see the generated diagrams.

If you are running OS with `sh` you can simply start the `run` script:

```
./run
```

You can pass the port you want to use for Structurizr if port 8080 is in use:

```
./run 8888
```
