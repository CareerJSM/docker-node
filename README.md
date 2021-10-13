# Docker Image for Ember Testing

This Docker image, will setup a system so your ember tests can be executed inside the container itself.

Based on repository here: https://github.com/BookerSoftwareInc/emberjs-docker-testing.

## Supported tags and respective `Dockerfile` links

- latest
- 12.8.1
- 14.18.0

## Run the Image

```
docker run --rm -ti -v $PWD:/app -p 7357:7357 careerjsm/docker-emberjs-testing:latest bash
```

### Run Your Tests

Now that you are in the container, you can run the following command `ember test --server`.
