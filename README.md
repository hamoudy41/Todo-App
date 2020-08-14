HOW TO RUN THIS APP USING DOCKER

1. Download or clone the repo
2. Unzip the folders if necessary
3. Navigate to app directory
4. Build the app image by running the command

```docker build -t todo-app .```

You can specify your own name instead of todo-app

5. Run the app by running the command

```docker run -dp 3000:3000 todo-app```

Again todo-app should be the name you specified in build command if you used a different name.
You may also use different ports instead of 3000

6. Navigate to the port 3000 of your localhost or a port you specified yourself

