# Python Web Development

## Publish Docker Image

Build Docker Image

```shell
docker build -t python-web-dev .
```

Login to Docker Hub Registry

```shell
docker login
```

Tag Docker Image

```shell
docker tag python-web-dev:latest timelimelim/python-web-dev:latest
```

Upload Docker Image

```shell
docker push timelimelim/python-web-dev:latest
```

## References

 * Complie matplotlib in docker
   * https://earthly.dev/blog/python-matplotlib-docker/