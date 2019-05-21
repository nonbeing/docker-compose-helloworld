# docker-compose-helloworld
Repo corresponding to the official [Docker Compose Tutorial](https://docs.docker.com/compose/gettingstarted/)

This version doesn't build an image from a `Dockerfile` - it simply downloads a pre-built image from docker hub and uses it.

A `Dockerfile` can however be used to build an image if so desired- it's present in the `ignore-temp` directory.

# Running

- Clone this repo.
- `docker-compose up`


# docker hub

Docker images needed (`redis` and `web`) are here (just FYI):
https://cloud.docker.com/u/nonbeing/repository/docker/nonbeing/docker-compose-helloworld
