# Node, MongoDB and React local setup
This is a documentation to setup Node,MongoDB and React from Conektto GitLab repositories.


# Prerequisites

- Access to Conektto/Ezapi Gitlab reposotories.


# Setting up Node environment

You must install **Node.js** and the **npm command line interface** using either a Node version manager or a Node installer.

### Useful links

[Get the latest Nodejs environment](https://nodejs.org/en/)


[Detailed documentation explaing Node Environment setup](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)

### Check your versions of node and npm

```cmd
node -v
npm -v
```

If you see a version greater than 12, you are good to go!


# Cloning the Nodejs Repository

- Go to the Nodejs repo on Gitlab that you have access to and copy the `clone with HTTPS` URL.
- Open command prompt and `cd` to the folder you want to clone and use `git clone {copied URL}`.

  You need to have Git installed, use [this](https://github.com/git-guides/install-git) to install Git.

# Installing npm packages

- `cd` to the cloned folder and use `npm install` or `npm i`.

# Setting up MongoDB

You need to setup mongoDB locally.Use below links to set it up.

### Useful links for mongodb setup

 [Detailed tutorial](https://www.mongodb.com/docs/manual/tutorial/install-mongodb-on-windows/)


 [To download compass](https://www.mongodb.com/products/compass)

You can also use Robo3T or Studio3T based on your preference.

# Starting sever 

Use `npm run start-dev` to start the server.If you see a Welcome message [here](http://127.0.0.1:7744/), you are good to go!

Also check for the console message "mongo connected", this confirms you are connected to mongoDB.

This completes the backend local setup, you can fire APIs from postman or REST client extension in VS Code.

# React setup

Now that you have all the dependencies installed on your machine, cloning and running UI should not be a problem.

# Cloning the React Repository

- Go to the React repo on Gitlab that you have access to and copy the `clone with HTTPS` URL.
- Open command prompt and `cd` to the folder you want to clone and use `git clone {copied URL}`.

  You need to have Git installed, use [this](https://github.com/git-guides/install-git) to install Git.

# Installing npm packages

- `cd` to the cloned folder and use `npm install` or `npm i`.

# Starting sever

Use `npm start` to start the server.You can see conektto UI [here](http://127.0.0.1:3000/) once you setup all this.

Happy Coding!



