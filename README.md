# Text Editor Starter Code

# Progressive-Web-App

![license badge](https://img.shields.io/badge/license-MIT-brightgreen)

## Description

JATE is a web app that lets developers create and store notes or code snippets offline or online. It uses a client-server folder structure and starting it up involves running 'npm run start' from the root directory. JATE is built with next-gen JavaScript and uses IndexedDB to store content, which is automatically retrieved when the editor is reopened. It also offers the option to download the app as an icon on the desktop and pre-caches static assets with a registered service worker upon loading.

![Homepage](./assets/images/homepage-image.png)

## User Story

AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use

## Acceptance Criteria

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

## Table Of Contents

* [Installation](#installation)
* [Usage](#usage)
* [License](#license)
* [Contributing](#contributing)
* [Test](#test)
* [Questions](#questions)

## Installation

To install dependencies, run the following command: 

```
npm install
```

## Usage

N/A

## Contributing

N/A

## Test

To run test, use the following command:

```
npm test
```

## Technologies Used

- JAVASCRIPT

## Credits

N/A

## License

MIT License

## Questions

To ask questions about the project, contact me directly at yhdeslouches@hotmail.com. You can find more of my work at [Yves Harry Deslouches](https://github.com/YvesHarry).