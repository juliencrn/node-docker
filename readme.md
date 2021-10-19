# Node Docker

Project built following this [tutorial](https://docs.docker.com/language/nodejs/)

## Notes

### Build the docker image
The unit tests must pass to be able to build the image.

```
docker build -t node-docker --target test .
```

### Run
You can access the debugger using chrome at `chrome:inspect` (`0.0.0.0:9229`)

```
docker-compose -f docker-compose.dev.yml up --build
```