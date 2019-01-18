# Contentful-Simple-UI-Extension
Simple UI Extension for Contentful CMS

Small Vue app which saves a simple text string.
Boilerplate for more complex UI Extensions for Contentful CMS.

## :rocket: Dependencies & Installation
Node & NPM

Run to clone this boilerplate:
`git clone https://github.com/TinkeringAround/Contentful-Simple-UI-Extension.git`

## :star: Configuration
Edit config attribute in package.json to insert your Contentful Space ID and the name and field type of the UI extension.

## :cloud: Available Scripts
In the project directory, you can run:

### `npm login`
Fetches a Contenful management token after login via browser UI. This token will be stored and used for further requests.

### `npm create`
Initial setup of a UI extension.

### `npm run deploy`
Updating the existing UI extension.
Throws an error if the extension has not been created by `npm create` or via Contentful Web UI.

### `npm run delete`
Deleta a existing UI extension.
Throws an error if the extension has not been created by `npm create` or via Contentful Web UI.
