# Contributing 

## Setup

Clone your fork of the repository

```
$ git clone https://github.com/YOUR_USERNAME/logger.git
```

Install npm dependencies

```
npm install
```

Run build process

```
npm run tsc:compile
```

## Test

```
npm run test
```

## Write documentation

Ts.Logger uses docsify to convert markdown to HTML. Also, all documentation in your code will be used to generate the API documentation. To preview your comments on a class you can run this command:

```
npm run doc:serve
```

## Guidelines

- Ts.Logger follows the git flow to generate a release note. To write your commit message, see https://docs.google.com/document/d/1QrDFcIiPjSLDn3EL15IJygNPiHORgU1_OOAqWjiDU5Y/edit
- Please try to combine multiple commits before pushing
- Please use TDD when fixing bugs. This means that you should write a unit test that fails because it reproduces the issue, then fix the issue and finally run the test to ensure that the issue has been resolved. This helps us prevent fixed bugs from happening again in the future
- Please keep the test coverage at 100%. Write additional unit tests if necessary
- Please create an issue before sending a PR if it is going to change the public interface of Ts.ED or includes significant architecture changes,
- Feel free to ask for help from other members of the Ts.Logger team
