# PWA Text Editor

## Description

C19 PWA Text Editor is a Progressive Web Application (PWA) that runs in the browser. It's a single-page application that meets PWA criteria and features multiple data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application also functions offline.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Examples](#examples)
- [Technologies Used](#technologies-used)
- [Source Code](#source-code)
- [License](#license)

## Installation

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Run `npm install` to install all dependencies.
4. Run `npm run build` to build the application.
5. Run `npm start` to start the backend and serve the client.

## Usage

- Open the application in your browser.
- Start typing or pasting your content.
- The content will be automatically saved when you click off the DOM window.
- To install the application on your desktop, click the "Install!" button in the header.

## Features

- Create and edit text content with JavaScript syntax highlighting.
- Offline functionality.
- Automatic content saving using IndexedDB.
- Installable as a Progressive Web Application.
- Responsive design for use on various devices.

## Examples

You can view the live application here: [PWA Text Editor on Render](https://c19-pwa-text-editor-9pva.onrender.com)

Here are some examples of the PWA Text Editor in action:

### Application Interface

![JATE Interface](./images/desktop%20JATE.png)
*The main interface of the JATE text editor.*

### IndexedDB Storage

![IndexedDB Storage](./images/jate%20indexedDB.png)
*Demonstration of content stored in IndexedDB for offline use.*

### PWA Installation

![PWA Installation](./images/PWA%20JATE%20Install.png)
*Installing JATE as a Progressive Web App.*

### Service Worker

![Service Worker](./images/jate%20service%20worker.png)
*Active service worker for offline functionality.*

### Web App Manifest

![Web App Manifest](./images/jate%20manifest.png)
*The web app manifest for JATE.*

### Text Editor in Action

![Text Editor Usage](./images/Open%20with%20Jate%20text.png)
*Using JATE to edit text with syntax highlighting.*

## Technologies Used

- HTML/CSS/JavaScript
- IndexedDB
- Webpack
- Workbox
- Babel
- Express.js
- Node.js

## Source Code

This project is based on the starter code from the following repository:

- Original Source: [https://github.com/coding-boot-camp/cautious-meme](https://github.com/coding-boot-camp/cautious-meme)

The current version has been edited and modified by:

- Editor: [Mountainmancodes](https://github.com/Mountainmancodes)
- Edited Version: [https://github.com/Mountainmancodes/C19-PWA-Text-Editor](https://github.com/Mountainmancodes/C19-PWA-Text-Editor)

## License

This project is licensed under the ISC License.
