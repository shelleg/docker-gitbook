# Docker Gitbook

> Boilerplate for building a Gitbook self-serving Docker container

## Build

```sh
git clone git@github.com:shelleg/docker-gitbook.git
cd docker-gitbook
docker build -t shelleg/docs .
```

## Run

```sh
docker run --rm -p 4000:80 shelleg/docs
```

Now you can browse to http://localhost:4000 to see documentation.
