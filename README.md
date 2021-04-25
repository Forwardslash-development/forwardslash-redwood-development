# Forwardslash Redwood Development
A full-stack, serverless web application framework that will allow you to build and deploy JAMstack applications with ease.

- React
- GraphQL (Apollo)
- Prisma
- Jest
- Storybook
- Babel
- Webpack

# Features
Opinionated defaults for formatting, file organization, webpack, Babel, and more.
Simple but powerful routing (all routes defined in one file) with dynamic (typed) parameters, constraints, and named route functions (to generate correct URLs).
Automatic page-based code-splitting.
Boilerplate-less GraphQL API construction.
Cells: a declarative way to fetch data from the backend API.
Generators for pages, layouts, cells, SDL, services, etc.
Scaffold generator for CRUD operations around a specific DB table.
Forms with easy client- and/or server-side validation and error handling.
Hot module replacement (HMR) for faster development.
Database migrations (via Prisma 2).
First class JAMstack-style deployment to Netlify.

## Getting Started

- [Docs](https://redwoodjs.com/docs/introduction): using the Redwood Router, handling assets and files, list of command-line tools, and more.
- [Redwood Community](https://community.redwoodjs.com): get help, share tips and tricks, and collaborate on everything about RedwoodJS.

### Setup

We use Yarn as our package manager. To get the dependencies installed, just do this in the root directory:

```terminal
yarn install
```

### Fire it up

```terminal
yarn redwood dev
```

Your browser should open automatically to `http://localhost:8910` to see the web app. Lambda functions run on `http://localhost:8911` and are also proxied to `http://localhost:8910/.redwood/functions/*`. 

> **WARNING:** RedwoodJS software has not reached a stable version 1.0 and should not be considered suitable for production use. In the "make it work; make it right; make it fast" paradigm, Redwood is in the later stages of the "make it work" phase.