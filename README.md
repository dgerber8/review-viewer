# Reviews Project

A full-stack application using NestJS with Prisma and React with Material UI.

## How To Run

1. Clone this repository
2. Run `npm install`
3. Run `npm run setup`
4. Run `npm start`
5. Go to http://localhost:4200

## Introduction

This project is a simple web app for viewing movie reviews (pulled from IMDb). It includes pagination, search functionality.

### Project Structure

The project is a simple Nx workspace with two applications, located in the `apps` directory.
There is also a `db` directory which contains a sample SQLite database seeded with some data,
and a `prisma` directory which contains the Prisma schema file.

```
swell-devtest
├── apps (backend and front end applications)
│   ├── reviews-api
│   │   └── src
│   ├── reviews-client
│   │   └── src
├── db (database files)
│   └── swell-sample.db
├── libs (Nx libraries [currently empty])
└── prisma (Prisma schema file)
    └── schema.prisma
```
