# basics-of-node.js-and-npm
- In this repo we will learn basics of node and npm by setting up packaga.json file in our project folder and after that we will set up lite-server and host our project file and see the changes made to it live.
- first create a local repo and initialise it as a git repo by using git init command.
   `git init`
 ### git-init
 - make an index.html file in the repo and add some html in it.
 - now make an online repo on github and push the changes to it using the following command.
 - ```gitcommand
    git remote add origin <repo link>
    ``` (this command is for linking your local repo with the remote repo)
 - push the changes to the online repo and then run the command in the terminal.
 now we will initiallise our repo with npm
 ### npm init 
 Follow along the prompts and answer the questions as follows: accept the default values for most of     the        entries, except set the entry point to index.html and set your name as author.
  This should create a package.json file in your git-test folder.
Installing an NPM Module

Install an NPM module, lite-server, that allows you to run a Node.js based development web server and serve up your project files. To do this, type the following command in the terminal:
- `npm install lite-server --save-dev`
You can check out more documentation on lite-server [here](https://github.com/johnpapa/lite-server).
Next, open package.json in your editor and modify script section 
- add "start":"npm run lite",
  and -"lite": "lite-server"
- next start deployment server by typing the following command in the terminal
 ### npm start
 - This should open your index.html page in your default browser.
   If you now open the index.html page in an editor and make changes and save, the browser should immediately        refresh to reflect the changes.
#Setting up .gitignore
Next, create a file in your project directory named .gitignore (Note: the name starts with a period)Then, add the following to the .gitignore file

#node_modules

Then do a git commit and push the changes to the online repository. You will note that the node_modules folder will not be added to the commit, and will not be uploaded to the repository.
