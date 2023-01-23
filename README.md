# Progressive Web Applications (PWA): Text Editor

<p align="center">
  <img src="images/logo.png">
</p>

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

📌 [Link to Deployed Application](https://ass19-jate.herokuapp.com/)


## Description

This web application is a text editor that runs in the browser. It is a single-page application that meets 
the PWA criteria. Additionally, it features a number of data persistence techniques that serve as redundancy in 
case one of the options is not supported by the browser. The application is also capable of functioning offline.

Here is are snapshots of using the API calls using Insomnia:
    <br />
![Social Media API](Assignment18.gif)


## User Story

```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

## Acceptance Criteria

```md
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
```

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Tech-Stack](#Tech-Stack)

- [License](#license)
- [Tests](#tests)

## Installation

To run your own version of the app do the following:
1. Clone this git repo to your computer
2. In your terminal type `npm install` 
3. Once all dependencies are installed type `npm run start` which will create the `dist` folder and launch the server 
4. Use the text editor either online or offline

## Tech-Stack
- JavaScript
- [Webpack](https://webpack.js.org/)
  - Service Workers
  - Create Manifest
- [IndexedDB](https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API)
- [Node.js](https://nodejs.org/en/)
- [Express](https://expressjs.com/)


## Credits

* Samdemarco

## License

MIT License

## Tests

N/A
