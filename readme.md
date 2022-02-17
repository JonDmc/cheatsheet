* How to make a node project

- mkdir a new directory/folder for the project
- initiate node, on that folder you made, by typing 'npm init -y'
- create your main file (i.e. touch index.js)
- if using personal modules, apply 'module.exports' on the elements/functions you want to use to index.js
- To test your code, type 'node index.js' on the terminal to run index.js
- If using 3rd party modules, install the module/s on the same dir of your project
    - use said module's documentation to learn and understand how to use it
    - type 'touch .gitignore' in your terminal and include in the .gitignore file the node_modules that you are using
    - .gitignore will ignore everything on it when pushing into github

* How to install 3rd-party modules
- find the module you want to use
- locate in the documentation the process to install (if they have specific instructions)
- otherwise, on your terminal 
    - type ```npm i -g <moduleName>``` to install the module globally
    - type ```npm i <moduleName>``` to install the module locally
- install the module on the same dir of your project
