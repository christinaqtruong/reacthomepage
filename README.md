
  

# React Homepage

  

A website designed from scratch using react and react-bootstrap to showcase the first projects I created as a developer back in 2019 as part of the University of Texas at Austin's Coding Boot Camp summer cohort. The deployed version can be found [here]([https://christinaqtruong.github.io/reacthomepage](https://christinaqtruong.github.io/reacthomepage)).

  

## Getting Started

  

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

  

### Prerequisites

This application requires that you have Node and yarn/npm installed on your machine.

-  [Node.js]([https://nodejs.org/en/](https://nodejs.org/en/))

  

### Setting Up

  

You can create a react-app using [Create a New React App](https://reactjs.org/docs/create-a-new-react-app.html)

  

Once you set up the application, you can install the [yarn]([https://yarnpkg.com/](https://yarnpkg.com/)) package manager and the following command to install the required dependencies

```
npm install -g yarn

yarn install
```

or you can also use run the following [npm](https://www.npmjs.com/) command:

  

```
npm install
```

To push the application to github, use:
````
git init

git remote add origin repository_URL
````
  

The *repository_URL* is the link you would use to clone down your github repository.

  

## Deployment

  

To run the application on your local server, use:
````
yarn start
````

To deploy the application to github pages, follow the instructions [here](https://blog.usejournal.com/how-to-deploy-your-react-app-into-github-pages-b2c96292b18e) or use:

````
npm install gh-pages --save-dev
````

In the package.json file, add the following code to the first object:

  

"homepage": "http://github_username.github.io/repo_name"

Be sure to replace *github_username* with your github username and *repo_name* with the name of your repository.

  

Then inside the package.json file, add the following two scripts to the "scripts" object:

  
````
"predeploy": "npm run build",

"deploy" : "gh-pages -d build",
````
  

After those lines are saved and pushed to master, run:
````
npm run deploy
````

Once the application is deployed, navigate to your github repository Settings > Github Pages and change the **Source** to *gh-pages*.

  

## Built With

  

*  [React]([https://reactjs.org/docs/create-a-new-react-app.html](https://reactjs.org/docs/create-a-new-react-app.html)) - JavaScript library

*  [React Bootstrap]([https://react-bootstrap.github.io/](https://react-bootstrap.github.io/)) - Front-end framework

*  [Inkscape]([[https://inkscape.org/](https://inkscape.org/)]([https://inkscape.org/](https://inkscape.org/))) - Vector graphics software

  

## Authors

  

*  **Christina Truong**

*  -  [*Github* ](github.com/christinaqtruong)

*  -  [*LinkedIn* ](linkedin.com/in/christinaqtruong)