# Mendix + Docker

- [1. Create a Mendix app](#1-create-a-mendix-app)
- [2. Download the Docker build park](#2-download-the-docker-build-park)
- [3. Copy the Mendix app to the Docker build park folder](#3-copy-the-mendix-app-to-the-docker-build-park-folder)
- [4. Build docker image](#4-build-docker-image)
- [5. Docker login](#5-docker-login)
- [6. Push docker image](#6-push-docker-image)
- [Run](#run)
- [Misc](#misc)
  - [Download MxBuild](#download-mxbuild)
  - [Install dos2unix in Windows](#install-dos2unix-in-windows)

## 1. Create a Mendix app

C:\Mendix\GitHubUserSearch10-main

Run and test it

## 2. Download the Docker build park

C:\tmp\docker-mendix-buildpack

## 3. Copy the Mendix app to the Docker build park folder

C:\Mendix\GitHubUserSearch10-main

->

C:\tmp\docker-mendix-buildpack\GitHubUserSearch10-main

## 4. Build docker image

```dos
docker build --build-arg BUILD_PATH="{relative-mendix-project-location}" -t {image name} .

```

e.g.

<!-- docker build --build-arg BUILD_PATH="./GitHubUserSearch10-main" -t mendix-github . -->

```dos
docker build -t mendix-github .

docker images
```

<!-- docker build --build-arg BUILD_PATH="./GitHubUserSearch10-main" -t mendix/mendix-buildpack:v5.0.4 . -->

## 5. Docker login

```dos
docker login -u briansu2004@hotmail.com -p <password>
```

## 6. Push docker image

```dos
docker tag mendix-github:latest briansu2004/mendix-github:latest

docker push briansu2004/mendix-github:latest
```

e.g.

```text
C:\tmp\docker-mendix-buildpack>docker images            
REPOSITORY                                  TAG        IMAGE ID       CREATED          SIZE
briansu2004/mendix-github                   latest     bd33e2fbc38b   10 minutes ago   297MB
```

## Run

```dos
docker run -it \
  -e ADMIN_PASSWORD=Password1! \
  -e DATABASE_ENDPOINT=postgres://username:password@host:port/mendix \
  mendix/mendix-buildpack:v1.2  
```

```dos
docker run -it briansu2004/mendix-github
```

## Misc

### Download MxBuild

- 10.6.1

C:\Apps\Mendix\10.6.1.24365

<https://cdn.mendix.com/runtime/win-mxbuild-10.6.1.24365.tar.gz>

<https://cdn.mendix.com/runtime/mxbuild-10.6.1.24365.tar.gz>

- 6.10.3

???

### Install dos2unix in Windows

```dos
choco install dos2unix

cd C:\tmp\docker-mendix-buildpack\scripts\
dos2unix *.*
```
