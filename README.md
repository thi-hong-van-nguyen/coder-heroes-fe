# Basic SPA

For the steps on how to work with this repository [please see here](https://docs.labs.lambdaschool.com/labs-spa-starter/)


# CoderHeroes

You can find the deployed project at [CoderHeroes](https://a.coderheroes.dev/login).

## Contributors

|[<img src="https://avatars.githubusercontent.com/u/78114013?v=4" width = "200" />](https://github.com/chelseaceballos)|[<img src="https://avatars.githubusercontent.com/u/84593843?v=4" width = "200" />](https://github.com/Jie-chelchel)|[<img src="https://avatars.githubusercontent.com/u/42555076?v=4" width = "200" />](https://github.com/WillisLi)|[<img src="https://avatars.githubusercontent.com/u/83714912?v=4" width = "200" />](https://github.com/bradlylewis)|
|---|---|---|---|
|[Chelsea Ceballos](https://github.com/chelseaceballos) [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/chelseaceballos)|[Jie Zhang](https://github.com/Jie-chelchel) [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/Jie-chelchel)|[Willis Li](https://github.com/WillisLi) [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/WillisLi)|[Bradly Lewis](https://github.com/bradlylewis) [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/bradlylewis)|
|[<img src="https://avatars.githubusercontent.com/u/80992248?v=4" width = "200" />](https://github.com/fernando817mm)|[<img src="https://avatars.githubusercontent.com/u/47357270?v=4" width = "200" />](https://github.com/muhannadbm)|[<img src="https://avatars.githubusercontent.com/u/82040208?v=4" width = "200" />](https://github.com/vasqueza91)|[<img src="https://avatars.githubusercontent.com/u/32268444?v=4" width = "200" />](https://github.com/MikeLikesCode)|
|[Fernando Martinez](https://github.com/fernando817mm) [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/fernando817mm)|[Muhannad Bani Almarje](https://github.com/muhannadbm) [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/muhannadbm)|[Alejandro Vasquez](https://github.com/vasqueza91) [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/vasqueza91)|[Michael Guerrero](https://github.com/MikeLikesCode) [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/MikeLikesCode)|
|[<img src="https://avatars.githubusercontent.com/u/81542563?v=4" width = "200" />](https://github.com/andrewskr90)|[<img src="https://avatars.githubusercontent.com/u/39386788?v=4" width = "200" />](https://github.com/Rodgers31)|[<img src="https://avatars.githubusercontent.com/u/85185709?v=4" width = "200" />](https://github.com/cn8817)|[<img src="https://avatars.githubusercontent.com/u/65091914?v=4" width = "200" />](https://github.com/CptHappyHands)|
|[Kyle Andrews](https://github.com/andrewskr90) [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/andrewskr90)|[Rodgers Otieno](https://github.com/Rodgers31) [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/Rodgers31)|[Christine Nguyen](https://github.com/cn8817) [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/cn8817)|[Andrew Cummings](https://github.com/CptHappyHands) [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/CptHappyHands)|
|[<img src="https://avatars.githubusercontent.com/u/14983694?v=4" width = "200" />](https://github.com/JoeyMBrown)||||
|[Joseph Brown](https://github.com/JoeyMBrown) [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/JoeyMBrown)||||

<br>
<br>

## Tech stack

![MIT](https://img.shields.io/packagist/l/doctrine/orm.svg)
![React](https://img.shields.io/badge/react-v16.13.1--alpha.2-blue.svg)
![react-router-dom](https://img.shields.io/badge/react--router--dom-v^5.2.0-blue.svg)
![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)
![Less](https://img.shields.io/badge/Less-v^1.17.0-ff69b4.svg)
![antd](https://img.shields.io/badge/antd-v^4.4.3-green.svg)
![redux](https://img.shields.io/badge/redux-v^4.1.2-yellow.svg)
![redux-thunk](https://img.shields.io/badge/redux--thunk-v^2.4.0-yellow.svg)
![Axios](https://img.shields.io/badge/Axios-v^0.21.1-yellow.svg)
![Okta](https://img.shields.io/badge/Okta-v^3.0.2-red.svg)

- Fork and clone the repo to install it as your own remote.
  - **note** please [be sure to set your remote](https://help.github.jp/enterprise/2.11/user/articles/changing-a-remote-s-url/) for this repo to point to your Labs Team Front End Repository.
- run: `npm install` to download all dependencies.
- run: `npm start` to start your local development server.

> When using Okta for authentication, the app will need to run locally on port 3000.

### Key Features

- Antdesign for component base
- File scaffolding to organize pages and components
- File scaffolding to organize styles
- React router to handle project routing
- Okta to handle user authentication
- Less for global and component base styles
- Redux for global state management

#### Front end deployed to `heroku` at [coderheroes](a.coderheroes.dev).

#### [Back end](https://github.com/BloomTech-Labs/coder-heroes-be) built using:


- Docker
- Node.js
- Express
- Okta interaction

# APIs

## Authentication API here

For authentication we're hitting Okta.  The Okta flow can be found here: [OktaFlow](https://developer.okta.com/docs/guides/implement-grant-type/authcode/main/#grant-type-flow).  We're very early stages in using Okta.  Right now users cannot self-register accounts need to be created on Okta by an administrator (from Lambda).  Logging in does work with pre-defined accounts.

## Payment API here

We we're planning on implementing Stripe for payments - however this is a future feature that we have not started implementing yet.

## Misc API here
No misc API's currently being used.

# Installation Instructions

- git clone
- npm install
- npm start

## Other Scripts

    * start - starts the production server after a build is created
    * test - runs tests in **tests** directory \* eject - copy the configuration files and dependencies into the project so you have full control over them

# Contributing

When contributing to this repository, please first discuss the change you wish to make via issue, email, or any other method with the owners of this repository before making a change.

Please note we have a [code of conduct](./CODE_OF_CONDUCT.md). Please follow it in all your interactions with the project.

## Issue/Bug Request

**If you are having an issue with the existing project code, please submit a bug report under the following guidelines:**

- Check first to see if your issue has already been reported.
- Check to see if the issue has recently been fixed by attempting to reproduce the issue using the latest master branch in the repository.
- Create a live example of the problem.
- Submit a detailed bug report including your environment & browser, steps to reproduce the issue, actual and expected outcomes, where you believe the issue is originating from, and any potential solutions you have considered.

### Feature Requests

We would love to hear from you about new features which would improve this app and further the aims of our project. Please provide as much detail and information as possible to show us why you think your new feature should be implemented.

### Pull Requests

If you have developed a patch, bug fix, or new feature that would improve this app, please submit a pull request. It is best to communicate your ideas with the developers first before investing a great deal of time into a pull request to ensure that it will mesh smoothly with the project.

Remember that this project is licensed under the MIT license, and by submitting a pull request, you agree that your work will be, too.

#### Pull Request Guidelines

- Update the README.md with details of changes to the interface, including new plist variables, exposed ports, useful file locations and container parameters.
- Ensure that your code conforms to our existing code conventions and test coverage.
- Include the relevant issue number, if applicable.
- You may merge the Pull Request in once you have the sign-off of two other developers, or if you do not have permission to do that, you may request the second reviewer to merge it for you.

## Documentation

See [Backend Documentation](https://github.com/BloomTech-Labs/coder-heroes-be#readme) for details on the backend of our project.

## Testing your Components

- You will be using [jest]() along side with [React Testing Library]() to test your application.
- Please put all of your tests for your code in `__tests__` folder.
- You should get into the habit of ensuring that you have coverage for your code _before submitting a pull-request_.

### Running your tests

- When writing tests run the command:
  - `cd into` the root of this directory
  - `npm test` to run your test suite
    - _if you're prompted_ select `a` to run tests in watch mode. This will re-run your test suite when you save any file in your application.
  - In your terminal you will see a test runner that looks something like this:
    ![Test screenshot](https://tk-assets.lambdaschool.com/bc9ca7b9-4fce-45de-9a16-705cbec062d8_ScreenShot2020-06-25at7.52.52AM.png)
  - When you're not actively writing tests its best to close that terminal window so that you don't keep running tests when your files are saved.

### Coverage

> 💡 Code coverage should be a good goal to have and a good starting place. But every application will be different.

- [Kent Dodds put it nicely](https://kentcdodds.com/blog/common-testing-mistakes#mistake-number-2-100-code-coverage). Strive for solid coverage as we strive to hand you over well-tested code in which we have extreme confidence.

- To run a coverage report for your application simply run `npm run coverage`.
- You should see a print out in your console that looks like this:
  ![code coverage](https://tk-assets.lambdaschool.com/5abec98b-2b61-483f-bd85-71002a9f755a_ScreenShot2020-06-25at7.59.14AM.png)

## Data Visualization

Components in folder `src/pages/ExampleDataViz` represent a pattern that you can use when working as a part of a `Hybrid Team`. When working with Data Scientists you'll need to ensure that you communicate as often as you possibly can with that team. They will be doing hard work using [`Plotly`](https://plotly.com/) to ensure that the data they're working with is charted out in a visually appealing way, however you'll need to work with them to integrate their work into the app.

The `RenderDataViz.js` file demonstrates how you can pull in data from an external API, set that data on state, and then pass that data down to a `<Plot />` component. In this case, the URL for the plot component is the only prop that will be needed to send off the API call and subsequently mount the Plot components w/ the appropriate data. **Be sure to handle your errors nicely.**

## Login and Authentication w/ Okta.

- The `LoginContainer.js` file in `src/pages/Login` includes a widget that is provided to us by Okta.
- This widget is the key to `user authentication and management` within your application.
- You don't have to manage ANY users because we're letting Okta do this for us :)
- This component is heavily documented with comments but it'd be REALLY good to read through [the docs here](https://github.com/okta/okta-signin-widget) to get a good understanding of the configuration we're doing with the widget itself.
- You'll also want to learn a bit about how to style this widget to meet your app's concerns.

## Utils

- `Utils` directory is for any of the business logic that your application may need to use.
- Simple one-off _helper_ functions that you may need can be defined in this directory.
- Any reusable logic or handlers or config files can also be used here.
- **REMINDER do not** check any sensitive information into git

## Common Directory Explanation
Loom[https://www.loom.com/share/e304d66df57a42b4871ed82a2aa98dd1]

## ExampleList Directory Explanation
[Loom] https://www.loom.com/share/686ebc35d65b45d9b2e3c63ef7848736

## ExampleDataViz Directory Explanation
[Loom] https://www.loom.com/share/1fd02cd49ea4481ebb4e3e6829af323b

## [Loom Videos]
##  Home/Landing/Login/NotFound/ProfileList Directories Explanations
Loom [https://www.loom.com/share/b096caec05d64723973075cb4d6bbd00]
## InstructorBooking/ InstructorHome directories explanation

### InstructorBooking
Loom[https://www.loom.com/share/abb423fc7e5444a3b7f01baca244b3dd]

### InstructorHome
Loom[https://www.loom.com/share/4c5f90178f17417aa206f2319bb16a39]

### Parent Dashboard
Loom[https://www.loom.com/share/5250dabcfb8f40d6bae9b363118fc910]

### Parent Bookings
Loom[https://www.loom.com/share/20a4917f86de4cbd9499f41d34061706] (part 1)
Loom[https://www.loom.com/share/b6648c95d4b74b3aa2e3b153f3a410fe] (part 2)

### Parent Calendar
Loom[https://www.loom.com/share/ad3fcdce651c4e8381781df08e40d7b1] (part 1)
Loom[https://www.loom.com/share/8b94d91bcacc47f7ad082d26eab1f94a] (part 2)
Loom[https://www.loom.com/share/689ff99c6838454483724f7f281f8241] (part 3)
Loom[https://www.loom.com/share/42e6893185c44a5cbd64b3ba3a90faff] (part 4)
Loom[https://www.loom.com/share/d0f2ee9de7e6439280c826560c36393b] (part 5)
Loom[https://www.loom.com/share/a47320e57c9f46f88e6ee14d5a8563bb] (part 6)
Loom[https://www.loom.com/share/70db70523b7e45a0852c6f39eb29261e] (part 7)
Loom[https://www.loom.com/share/ba15e1a16e174d25a39db4ee01a013fc] (part 8)
Loom[https://www.loom.com/share/a6eb1260c8ce45adad1d38a4c9b42686] (part 9)



