# Dockerize-GoLang

The app counts number of bytes from a web page.
Here, we are going to use https://www.google.com as web page


## Link:
https://blog.codeship.com/building-minimal-docker-containers-for-go-applications/

## Procedure

Build Docker image:
```
docker build . -t <your username>/go
```

Run the Docker image:
```
docker run <your username>/go
```
