# PWA Text Editor

## Badges
![MIT License](https://img.shields.io/badge/license-MIT%20License-green)

## Description
This project is a Progressive Web Application (PWA) text editor that runs in the browser. It allows users to create and store notes or code snippets with or without an internet connection, ensuring reliable retrieval for later use. The application features data persistence using IndexedDB, which serves as a redundant storage option. It also functions offline, providing a seamless user experience.

The text editor utilizes the idb package, a lightweight wrapper around the IndexedDB API. This package offers useful methods for storing and retrieving data and is widely used by companies like Google and Mozilla.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Tests](#tests)
- [Questions](#questions)
- [Contributing](#contributing)
- [Credits](#credits)
- [License](#license)

## Installation
To install and run the PWA text editor application, follow these steps:
1. Clone the repository to your local machine.
2. Navigate to the root directory of the project.
3. Run `npm install` to install the necessary dependencies.
4. Run `npm run start` to start the backend and serve the client.
5. Open the text editor application in your browser.


## Usage
Once the PWA text editor is running in your browser, you will see a client server folder structure. The JavaScript files are bundled using webpack. The webpack plugins generate an HTML file, service worker, and a manifest file.

You can use the text editor to create and edit notes or code snippets. The content you enter is automatically saved to IndexedDB when you click off the DOM window. The saved content will be retrieved from IndexedDB when you reopen the text editor.

To download the web application as an icon on your desktop, click on the "Install" button. This enables you to access the text editor quickly and conveniently.

The application has also been deployed to Heroku and can be accessed here: [https://pwa-text-editor786.herokuapp.com/]

## Tests
No tests are provided in this project.

## Questions
Questions can be directed to this GitHub profile or this email.

GitHub: [alimomin7861](https://github.com/alimomin7861)

Email: [alimomin7861@gmail.com](mailto:alimomin7861@gmail.com)

## Contributing
N/A

## Credits
There are no additional contributors to this project.

## License
MIT License

Copyright (c) 2023 Ali Momin