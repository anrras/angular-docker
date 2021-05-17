# angular-docker
Build Angular project using docker image with multi-stage builds


# Prerequisitos
- NodeJS +8
- Angular CLI (npm i -g @angular/cli@latest) 
- Docker +17.05

### 1. Crear un proyecto Angular
`$ ng new myapp`

### 2. Copiar los archivos al proyecto del repositorio al proyecto
`$ cp Dockerfile .dockerignore default.conf ./myapp`

### 3. Construir la imagen

`$ docker build -t myapp .`

### 4. Run the container

`$ docker run -p 8080:80 myapp --rm`


idea tomada de : https://dev.to/avatsaev/create-efficient-angular-docker-images-with-multi-stage-builds-1f3n




