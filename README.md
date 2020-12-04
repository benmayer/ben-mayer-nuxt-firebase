# ben-mayer-web

[Demo](https://ben-mayer-web.web.app/)

This is my personal website, a Nuxt.js application with Serverside Rendering, deployed to firebase functions, and using Firestore and Firebase Storage.

## Build Setup

``` bash
# install dependencies in /src 
$ cd src 
$ yarn install

# install dependencies in /functions for firebase functions 
$ cd functions 
$ yarn install


# serve nuxt on dev server at localhost:3000
$ yarn dev 

# generate static project
$ yarn predeploy

# build for production and serve firebase functions locally at localhost:5000
$ yarn serve

# build firebase for productions
$ yarn deploy


```

## Firebase installation

install firebase cli and login using your firebase account

``` bash 
$ curl -sL https://firebase.tools | bash

```
then create a .env file in the `src` directory your firebase config

