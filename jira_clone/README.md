<h1 align="center">Jira Board</h1>

<div align="center">Auto formatted with Prettier, tested with Cypress 🎗</div>



![App screenshot](https://i.ibb.co/W3qVvCn/jira-optimized.jpg)


## Features

- Proven, scalable, and easy to understand project structure
- Written in modern React, only functional components with hooks
- A variety of custom light-weight UI components such as datepicker, modal, various form elements etc
- Simple local React state management, without redux, mobx, or similar
- Custom webpack setup, without create-react-app or similar
- Client written in Babel powered JavaScript
- API written in TypeScript and using TypeORM

## Setting up development environment 🛠


- `npm run install-dependencies`
- `cd api && npm start`
- `cd client && npm start` in another terminal tab
- App should now be running on `http://localhost:8080/`

## Running cypress end-to-end tests 🚥

- Set up development environment
- Create a database named `jira_test` and start the api with `cd api && npm run start:test`
- `cd client && npm run test:cypress`


### Migrations 🗄
### Proper authentication system 🔐
### Accessibility ♿
### Unit/Integration tests 🧪

