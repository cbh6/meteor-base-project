# meteor-base-project

Meteor basic scaffolding

- Meteor version 1.7.0.5
- Node version 8.11.4
- npm version 6.3.0

## Running the app

`npm start` : Runs meteor using production settings

`npm run dev` : Runs meteor using develop settings

`npm run test`: Runs meteor tests with mocha

Run configs are placed in `run.sh` file

### First time running

- When starting the app for the first time, an admin user is created. You can configure its data in `server/startup/fixtures.js` file
- `run.sh` file contains env variables and run commands configurations
