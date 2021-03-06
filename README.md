# Project setup for fast prototyping with react and meteor.

![example snapshot](https://i.imgur.com/BAzmlXJ.png)

Full-Stack Web Setup

[React](https://reactjs.org/), is a Javascript library for building user interfaces.

[Meteor](https://www.meteor.com/), is a free and open-source isomorphic JavaScript web framework written using Node.js.

## Meteor basic setup

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

### Features

- Login and signup
- Reset password
- Edit user profile
- Security methods
- [Roles with alanning:roles meteor package](https://github.com/alanning/meteor-roles)
- Form validation
- Mailing

Client side

- Meteor 1.7+
- React 16.5.2
- [SemanticUi-react](http://react.semantic-ui.com/introduction/)
- SASS
- Forms with [formik](https://github.com/jaredpalmer/formik) and [yup](https://github.com/jquense/yup)

Server side

- Meteor 1.7+
- MongoDB

Testing

- [Mocha](https://mochajs.org/)
- [Chai](https://www.chaijs.com/)
- [sinon](https://sinonjs.org/)
- [Enzyme](https://github.com/airbnb/enzyme) (testing react components)

Code format

- eslint (airbnb and react/meteor styleguides)
- prettier
