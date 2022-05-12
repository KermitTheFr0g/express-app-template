# Express App Template
This is a template for an express server. This is an example for a very simple server which can be used to build off and create additional endpoints for.

## Getting Started
To get started with the express server the first step is to clone the repo.

### Installation
To actually 
1. Clone the GitHub Repo
``` sh
git clone https://github.com/KermitTheFr0g/express-app-template.git 
```
2. Install NPM Packages
```sh
npm install
```

## Usage
Once you have cloned the repository and all of the prerequisites installed the server can be run.
```sh
npm run start-server
```
This command begins the server running it on the default port of 3000. You can access the site at [localhost:3000](http://localhost:3000)


### Additional Information
By default the server runs on port 3000. If you would like to change the defaultl port an environmental variable must be used.
Create a new file in the root of the project name .env or alternatively use this command in the terminal:
```sh
type NUL > .env
```
This will create a new file in the root of the project and this is where we are going to add in the environment variable.
```
PORT=DESIRED_PORT
```
The server is now going to use this variable for which port to run the server on.
