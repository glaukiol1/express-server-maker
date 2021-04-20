# express-server-maker
Tired of making all those folders and files every time you want a new expressJS server? This is the solution. Shell Script for Linux.

## About

This tool is made for people who write a lot of ExpressJS servers, because they need to setup the whole project directory and files all over again. The starting files stay the same! This tool will take care of creating every thing, the public and views folders, also setup an example server with the NPM packages already installed. Once you run it, and it sets up everything, you can go to localhost:3000 and the server is already running!

## What it does
The tool will create the following directory(s) and file(s);
```
server.js
package.json
package_lock.json
node_modules
public
  js
    index.js
  css
    index.css
  img
views
  index.pug
```
## How to run it
First make *SURE* you put the *main.sh* file in the directory where you want the project to be init-ed! After that, in the linux terminal run the following;
```sh
$ sudo ./main.sh
# Now it should've
# started to make the project files
# in the current directory
# after it has downloaded the npm modules,
# it will write something like the following;
 Server Started on 127.0.0.1:3000!
#
# When you are done checking that everything works on 127.0.0.1:3000,
# Stop the script and delete it using,
$ sudo rm -f -r ./main.sh
```

## And You're Done!
If there are any issues, make sure to submit it in the "issues" tab! I will make sure to get back to you!

