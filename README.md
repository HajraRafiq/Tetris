# ng-tetris

Tetris game in Angular. [Play it now!](https://focused-mestorf-930f82.netlify.com/)

Read the [blog about making the game](https://medium.com/angular-in-depth/game-development-tetris-in-angular-64ef96ce56f7?sk=66ab4b5774919de28eecd3a2662557a4) 

![tetris picture](src/assets/share-image-large.png)

#Milestone
https://github.com/HajraRafiq/Tetris

#Dockerhub image
https://hub.docker.com/r/hajrarafiq/ng-tetris

## Development server

Run `npm start` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.


## For making container
```bash
nerdctl build -t chess:v1 .
```

#For running the container in localhost

```bash
 nerdctl run -p 8000:80 ng-tetris:v1
```

#To pull my container image

```bash 
nerdctl pull hajrarafiq/ng-tetris:v1
```
#To run my chess image

```bash
nerdctl run hajrarafiq/ng-tetris:v1
```

# To check files inside the container

```bash
nerdctl run -it hajrarafiq/ng-tetris:v1
```
