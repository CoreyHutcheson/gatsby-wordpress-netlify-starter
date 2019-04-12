<p align="center">
  <a href="https://www.gatsbyjs.org">
    <img alt="Gatsby" src="https://www.gatsbyjs.org/monogram.svg" width="60" />
  </a>
  <a href="https://wordpress.org/">
    <img alt="Wordpress" src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/98/WordPress_blue_logo.svg/1200px-WordPress_blue_logo.svg.png" width="60" />
  </a>
  <a href="https://www.netlify.com/">
    <img alt="Netlify" src="https://miro.medium.com/fit/c/240/240/0*BRl-uL7N9LF-1hiD.png" width="60" />
  </a>
</p>

<h1 align="center">
  Gatsby-Wordpress-Netlify Starter
</h1>

Kick off your next headless CMS experience with this starter. This starter ships with the necessities to get up and going pulling data from a Wordpress backend, converting your code into a static site with Gatsby, and hosting your site on Netlify.

## Requirements

1.  **Gatsby Command Line Tool** and **Netlify Command Line Tool**

    ```sh
    # install the gatsby cli
    $ npm install -g gatsby-cli netlify-cli
    ```

2.  **Netlify Account**

    You will need to setup a free Netlify account. Do so by visiting https://app.netlify.com/signup and linking your GitHub/GitLab/Bitbucket account.

## Quick start

1.  **Create a Gatsby site.**

    Use the Gatsby CLI to create a new site, specifying the default starter.

    ```sh
    # create a new Gatsby site using the default starter
    gatsby new my-new-project https://github.com/CoreyHutcheson/gatsby-wordpress-netlify-starter
    ```

2.  **Run The Setup Process**

    Navigate into your new site’s directory and set it up. This process creates the required .nvmrc file with your respective Node version and initalizes the Netlify site.

    ```sh
    cd my-new-project/
    npm run setup
    ```

3.  **Open the source code and start editing!**
    <<<<<<< HEAD

        Launch your development server by running:

=======

    Launch your development server by running:

> > > > > > > 06549b55c8f9eb4147808e054621091924dde57a

    ```sh
    $ npm start
    ```

## 🧐 What's inside?

A quick look at the top-level files and directories you'll see in a Gatsby project.

    .
    ├── .cache
    ├── node_modules
    ├── public
    ├── src
    ├   ├── assets
    ├   ├── components
    ├   ├── pages
    ├   └── util
    ├── .gitignore
    ├── .prettierrc
    ├── gatsby-browser.js
    ├── gatsby-config.js
    ├── gatsby-node.js
    ├── LICENSE
    ├── package-lock.json
    ├── package.json
    └── README.md

1.  **`.cache`**: _Don't touch_ - This folder will appear after first running npm start and contains the static site files generated by Gatsby

2.  **`/node_modules`**: This directory contains all of the modules of code that your project depends on (npm packages) are automatically installed.

3.  **`public`**: This folder will appear after first running npm start. You can place any static assets you don't want processed in this folder.

4.  **`/src`**: This directory will contain all of the code related to what you will see on the front-end of your site (what you see in the browser) such as your site header or a page template. `src` is a convention for “source code”.

    1.  **`assets`**: This folder is setup to hold any images used throughout the site

    2.  **`components`**: This folder is setup to hold all of the React components created for use throughout the site. If you notice the already created components are each placed inside their own respective folders, each with an index.js file whose sole purpose is to export the top-level component inside that directory.

    3.  **`pages`**: Each \*.js/\*.jsx file placed here will create a corresponding page on the front-end.

    4.  **`utils`**: Utility javascript functions, page-styles, and other non-component specific styles can be placed here.

5.  **`.gitignore`**: This file tells git which files it should not track / not maintain a version history for.

6.  **`.prettierrc`**: This is a configuration file for [Prettier](https://prettier.io/). Prettier is a tool to help keep the formatting of your code consistent.

7.  **`gatsby-browser.js`**: This file is where Gatsby expects to find any usage of the [Gatsby browser APIs](https://www.gatsbyjs.org/docs/browser-apis/) (if any). These allow customization/extension of default Gatsby settings affecting the browser.

8.  **`gatsby-config.js`**: This is the main configuration file for a Gatsby site. This is where you can specify information about your site (metadata) like the site title and description, which Gatsby plugins you’d like to include, etc. (Check out the [config docs](https://www.gatsbyjs.org/docs/gatsby-config/) for more detail).

9.  **`gatsby-node.js`**: This file is where Gatsby expects to find any usage of the [Gatsby Node APIs](https://www.gatsbyjs.org/docs/node-apis/) (if any). These allow customization/extension of default Gatsby settings affecting pieces of the site build process.

10. **`LICENSE`**: Gatsby is licensed under the MIT license.

11. **`package-lock.json`** (See `package.json` below, first). This is an automatically generated file based on the exact versions of your npm dependencies that were installed for your project. **(You won’t change this file directly).**

12. **`package.json`**: A manifest file for Node.js projects, which includes things like metadata (the project’s name, author, etc). This manifest is how npm knows which packages to install for your project.

13. **`README.md`**: A text file containing useful reference information about your project.
