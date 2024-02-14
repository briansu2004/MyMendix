# Mendix + Docker

- [1. Create a Mendix app](#1-create-a-mendix-app)
- [2. Download the Docker build park](#2-download-the-docker-build-park)
- [3. Copy the Mendix app to the Docker build park folder](#3-copy-the-mendix-app-to-the-docker-build-park-folder)
- [4. Build docker image](#4-build-docker-image)
- [5. Docker login](#5-docker-login)
- [6. Push docker image](#6-push-docker-image)
- [Misc](#misc)
  - [Download MxBuild](#download-mxbuild)

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

```dos
docker build --build-arg BUILD_PATH="./GitHubUserSearch10-main" -t mendix-github .

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

## Misc

### Download MxBuild

<https://cdn.mendix.com/runtime/mxbuild-10.0.0.5003.tar.gz>

->

C:\Apps\Mendix\10.6.1.24365

<https://cdn.mendix.com/runtime/mxbuild-10.6.1.24365.tar.gz>
