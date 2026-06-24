# Express RealWorld Example App

A backend API application built using Node.js, Express.js, TypeScript, Prisma ORM, and PostgreSQL.

## Features

* User Authentication using JWT
* User Registration and Login
* Profile Management
* Article Creation, Update and Deletion
* Comment Management
* Database Integration using Prisma ORM
* RESTful API Architecture
* Environment Variable Configuration
* TypeScript Support

## Tech Stack

* Node.js
* Express.js
* TypeScript
* Prisma ORM
* PostgreSQL
* JWT Authentication

## Installation

Clone the repository:

```bash
git clone https://github.com/Anudhi1705/Express_realworld_example_app.git
```

Install dependencies:

```bash
npm install
```

## Environment Variables

Create a `.env` file in the root directory and add:

```env
DATABASE_URL=
JWT_SECRET=
NODE_ENV=production
```

## Generate Prisma Client

```bash
npx prisma generate
```

## Run Database Migrations

```bash
npx prisma migrate deploy
```

## Start the Application

```bash
npx nx serve api
```

## Project Structure

* src/ - Application source code
* prisma/ - Database schema and migrations
* e2e/ - End-to-end tests
* Dockerfile - Container configuration

## Author

Anudhi Mishra

## License

This project is for educational and learning purposes.
