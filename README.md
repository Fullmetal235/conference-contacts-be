# API Documentation

#### Backend deployed at [Heroku](https://lambda-labs-swaap.herokuapp.com/) <br>

## Getting started

To get the server running locally:

- Clone this repo
- **npm install** to install all required dependencies
- **npm run server** to start the local server
- **npm test** to start server using testing environment
- **npm run deploy** to sync the prisma datamodel with our database

### Backend Frameworks & Libraries

*GraphQL*
- Declarative data fetching
- Zero-config caching (speed)
- Seamlessly handles local & remote data
- Vibrant ecosystem and extensibility

*Prisma*
- Type-safe database access thanks to the custom and auto-generated Prisma client.
- Simple and powerful API for working with relational data and transactions.
- Visual data management with Prisma Admin.
- Prisma unifies access to multiple databases at once (coming soon) and therefore drastically reduces complexity in cross-database workflows.
- Realtime streaming & event system for your database ensuring you're getting updates for all important events happening in your database.
- Automatic database migrations (optional) based on a declarative datamodel expressed using GraphQL's schema definition language (SDL).
- Other database workflows such as data import, export & more.

## Schema

You can find the schema documentation [here](./schema.md).

## 3️⃣ Environment Variables

In order for the app to function correctly, the user must set up their own environment variables.

create a .env file that includes the following:

    *  ENGINE_API_KEY - analytics for our graphql engine
    *  NODE_ENV - set to "development" until ready for "production"
    *  TEST_TOKEN - JWT used for testing porpoises
    *  SERVICE_STAGE - the database stage for testing or production

## Contributing

When contributing to this repository, please first discuss the change you wish to make via issue, email, or any other method with the owners of this repository before making a change.

Please note we have a [code of conduct](./code_of_conduct.md). Please follow it in all your interactions with the project.

### Issue/Bug Request

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

- Ensure any install or build dependencies are removed before the end of the layer when doing a build.
- Update the README.md with details of changes to the interface, including new plist variables, exposed ports, useful file locations and container parameters.
- Ensure that your code conforms to our existing code conventions and test coverage.
- Include the relevant issue number, if applicable.
- You may merge the Pull Request in once you have the sign-off of two other developers, or if you do not have permission to do that, you may request the second reviewer to merge it for you.

### Attribution

These contribution guidelines have been adapted from [this good-Contributing.md-template](https://gist.github.com/PurpleBooth/b24679402957c63ec426).

## Documentation

See [Frontend Documentation](https://github.com/Lambda-School-Labs/conference-contacts-fe) for details on the frontend of our project.

See [iOS Documentation](https://github.com/Lambda-School-Labs/conference-contacts-ios) for details on the iOS side of our project.
