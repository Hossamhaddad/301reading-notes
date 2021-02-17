# Heroku
## Heroku is a platform as a service (PaaS) that enables developers to build, run, and operate applications entirely in the cloud.

## you need to create an account on developer's site and install Heroku. This is not so hard. There is also instruction on Heroku's site that can explain you how to run your first simple web server


## To turn your local server into a world wide server. Weuse Heroku cloud 


# Node.js
## Node.js is an open source, cross-platform runtime environment, which allows you to build server-side and networking applications. It's written in JavaScript and can be run within the Node.js runtime on any platform.


### Create your project directory:

#### First of all, let's declare some variables:

#### var http = require("http");
#### var fs = require("fs");
#### var path = require("path");
#### var mime = require("mime");

#### The first one will give you the key to Node's HTTP functionality. The second one is for possibility to interact with the file system. The third one allows you to handle file paths. The last one allows you to determine a file's MIME-type. And it's not a part of Node.js, so we need to install third-party dependencies before using it. We need to create the package.json file for that purpose . 

#### {
  #### "name" : "blog",
 ####  "version" : "0.0.1",
 ####  "description" : "My minimalistic blog",
####   "dependencies" : {
  ####  "mime" : "~1.2.7"
 #### }
#### }


#### npm install


## To use heroku 
### Open your terminal within your project folder. For my Linux it's:

### cd /path/to/my/project
### Then run:

### git init
### Empty Git repository will be initialized in .git/ folder.

### Then run:

### git add .
### This command allows Git to track your files changes.

### Now commit your files to the initialized Git repo:

### git commit -m "Simple server functionality added"
### We'll create our first Heroku application now:

### heroku create
### Heroku will generate a random name for your application. In my case it's enigmatic-citadel-9298. Don't worry. You can change it later.

### Now we can deploy our project. Every Heroku app starts with no branches and no code. So, the first time we deploy our project, we need to specify a remote branch to push to:

### git push heroku master 
### The application is now deployed. Ensure that at least one instance of the app is running:

### heroku ps:scale web=1
### And now, before we open it, it's time to choose a proper name for our first creation. I called it myfirstserver:

### heroku apps:rename myfirstserver
### Everything is done. You can try it now:

### heroku open