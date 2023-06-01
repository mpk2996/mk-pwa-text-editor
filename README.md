# PWA Text Editor

This application is a text editor that runs in the browser. The application saves user input to IndexedDB database for offline use and utilizes Workbox to register a service worker.

## Table of Contents

- [Deployed Application](#deployed-application)
- [Demonstration](#demonstration)
- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Deployed Application
![Screen Shot 2023-06-01 at 3 18 55 AM](https://github.com/mpk2996/mk-pwa-text-editor/assets/118133981/b8568d70-04c6-47ea-8b0f-380baa1e6a23)

This application has been deployed to Heroku. You may view the application [here](https://mk-pwa-text-editor.herokuapp.com/).

## Demonstration

The following video demonstrates the application's functionality:
https://drive.google.com/file/d/1TZpmE2Am5QgSwL2BQ8LoUz-idacBmy_Y/view

## Installation

To install and run this application on your local machine, follow these steps:

1. Clone the repository.
2. Run `npm install` to install the required dependencies.
3. Run `npm run start`
4. If you wish to run the application offline, you may install it to your local machine by clicking the "Install" button on the top left corner of the application.

## Usage

To use this application, open the text editor and begin typing on the first line. The text editor will automatically save your input to IndexedDB. Your saved content will be retrieved each time you reopen the text editor.

## Credits

Node.js 
https://nodejs.org/en/

ESLint 
https://eslint.org/

Webpack 
https://webpack.js.org/

Babel  
https://babeljs.io/

## License

Please refer to the LICENSE in the repo.

