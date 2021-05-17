# angular-docker
Build Angular project using docker image with multi-stage builds


# Prerequisitos
- NodeJS +8
- Angular CLI (npm i -g @angular/cli@latest) 
- Docker +17.05

### 1. Create a new angular project
`ng new myapp`

### 2. Copy the files in the root of the project
`cp Dockerfile .dockerignore default.conf ./myapp`

### 3. Build the image

`docker build -t myapp .`

### 4. Run the container

In the terminal run: `docker run --rm -p 8080:80 myapp`

### 5. Watch the page in the browser

In the browser open a new tab with:  [http://localhost:8080/](http://localhost:8080/)


idea tomada de : https://dev.to/avatsaev/create-efficient-angular-docker-images-with-multi-stage-builds-1f3n




