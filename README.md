Source code for the Dev.to article - [Next.js, Apollo Client and Server on a single Express app](https://dev.to/givehug/next-js-apollo-client-and-server-on-a-single-express-app-55l6)

> This article describes two things:
>
> 1. How to fit `Next.js` with `Apollo Client` on front end and `Apollo Server GraphQL` api into a single `Express` app. Another important requirement was to have `SSR` support. As there is not much info about it out there, this is the main purpose of this guide.
> 2. How to organize everything nicely into `yarn workspaces` monorepo and deploy to `Heroku` as a single free plan app. You will find a lot of into about it, but I included it here as a part of the process of the project I was working on.

## Usage

Make sure you have Node.js 13+ as specified in package.json "engines" object. It is only required for Heroku deployment. If you have older versions, just remove it from package.json.

```
yarn install
```

```
yarn dev
```

open `http://localhost:3000`
