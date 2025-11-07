# Exercise Tracker

<div align="center">

![Node.js](https://img.shields.io/badge/Node.js-12.x-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-4.x-black?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Mongoose](https://img.shields.io/badge/Mongoose-5.x-880000?style=for-the-badge)
![dotenv](https://img.shields.io/badge/dotenv-Used-000000?style=for-the-badge)

</div>

## Overview

A simple REST API to track users and their exercise sessions, built as part of freeCodeCamp's curriculum. Create users, log exercises, and retrieve filtered logs. Powered by Node.js/Express with MongoDB via Mongoose.

## Key Features

- Create users and list all users
- Add exercise entries (description, duration, optional date)
- Retrieve exercise logs with optional date range and limit filters

## Tech Stack

Node.js 12, Express 4, MongoDB, Mongoose 5, Moment

## Architecture

Express REST API with endpoints under `/api/exercise/*`. Data persisted in MongoDB using a Mongoose `User` schema containing an embedded `log` array. Serves static assets from `build/` for the root route.

## Prerequisites

- Node.js: `12.0.0`
- MongoDB instance (local or hosted)

## Installation

```bash
git clone https://github.com/maxgalchenko/Exercise-Tracker.git
cd Exercise-Tracker
npm install
```

## Environment Variables

```env
MONGO_URL=mongodb://localhost:27017/exercisetracker
PORT=8080
```

## Quick Start

```bash
npm start
```

Open http://localhost:8080

## Available Scripts

- `npm start` – Start the Express server

---

<div align="center">

Built with ❤️ by [Maksym Galchenko](https://github.com/maxgalchenko)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/galchenko-max/)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-green?style=for-the-badge&logo=web)](https://portfolio-green-six-29.vercel.app/)
[![Email](https://img.shields.io/badge/Email-Contact-red?style=for-the-badge&logo=gmail)](mailto:galchenko.maksym@gmail.com)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

</div>
