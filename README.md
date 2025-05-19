# Google Photos Picker Sample App

<a href="https://studio.firebase.google.com/import?url=https%3A%2F%2Fgithub.com%2Flamek%2Fphotos-picker-open-fbs">
  <img
    height="32"
    alt="Open in Firebase Studio"
    src="https://cdn.firebasestudio.dev/btn/open_bright_32.svg">
</a>

## Cloud Project Configuration

Ensure that your Google Cloud project is set up following the "Configure your app" guide: [https://developers.google.com/photos/overview/configure-your-app](https://developers.google.com/photos/overview/configure-your-app)


## App Setup

With node js and npm installed, run:

> npm install

Then edit config.js with your client id and secret.


## Run in development mode (auto-reload on save)

This will run the app in a development mode that will reload the server whenever you make changes to the application.

> npm run dev

CAUTION: don't check in any changes to config.js (client id or secret). Use a config-test file (or gitignore config.js) instead.


## Running the app

To just run the app (if you're not doing any development), run:

> npm run server


