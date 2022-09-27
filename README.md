Q.1 What is node.js ? Node.js is an open source, cross-platform runtime environment and library that is used for running web applications outside the client’s browser. Node.js is designed to build scalable network applications. In the following "hello world" example, many connections can be handled concurrently. Upon each connection, the callback is fired, but if there is no work to be done, Node.js will sleep.

Q.2 What is NPM? Npm stands for Node Package Manager. It is a package manager for the Node JavaScript platform. Npm is known as the world’s largest software registry. Open-source developers all over the world use npm to publish and share their source code. 1.The website allows you to find third-party packages, set up profiles, and manage your packages. 2.The command-line interface or npm CLI that runs from a terminal to allow you to interact with npm.

Q.3 What are the different modules in Node.js? Modules are of three types: 1.Core Modules(http,path,process,url,os) 2.local Modules(local modules are created locally in your Node.js application.) 3.Third-party Modules(npm install express,npm install mongoose,npm install -g @angular/cli)

Q.4 What is the purpose of the module.exports? The module. exports is a special object which is included in every JavaScript file in the Node. js application by default. The module is a variable that represents the current module, and exports is an object that will be exposed as a module. So, whatever you assign to module.

Q.5 Difference between default export and named export --A default export can only export a single object, function, or variable and curly braces are omitted when importing in various files. --Named exports are imported with curly braces in various files and must be imported using the name of the object, function or variable that was exported.

Q.6 How do you import any module in Node.js require() function In order to use Node. js core or NPM modules, you first need to import it using require() function as shown below. var module = require('module_name'); As per above syntax, specify the module name in the require() function.
