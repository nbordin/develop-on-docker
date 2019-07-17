# Develop on docker

## Build and Run

Build:
```bash
docker build -t develop-on-docker .
```

```bash
docker run -ti --rm \
    -e DISPLAY=$DISPLAY \
    -v /tmp/.X11-unix:/tmp/.X11-unix \
    develop-on-docker
```

## Run programs on X Window System

Type `code` to run Visual Code Studio or `firefox` to run Firefox ESR.
