# ng-tuto


To Get new project front
===================


You need  **node** to install him run command.
```
// Install node
sudo apt-get install nodejs-legacy
```

> **Node.js®** is a platform built on Chrome's JavaScript runtime for easily building fast, scalable network applications


Init new project
-------------------
```
// Init project && create package.json
sudo npm init
```
> **package.json** This **file** is used to give information to npm that allows it to identify the project as well as handle the project's dependencies

```
// Install bower to manage your proj dependencies || librarys
npm install bower --save // local
||
npm install -g bower // global
```

now you can add your library like (angular / jquery / bootstrap / ...)

```
sudo bower install angular
sudo bower install bootstrap
```

// package.json
"scripts": {
    "postinstall": "bower install",
    "prestart": "npm install",
    "test": "echo \"Error: no test specified\" && exit 1",
    "start": "http-server -a localhost -p 8888 -c-1"
  }
