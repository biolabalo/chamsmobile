# Simple CRUD Application

This is a simple CRUD application built with Nodejs, Nestjs, Reactjs, MySQL, TypeORM, Redux, and Axios.

## Features

- A RESTful API for CRUD operations on data stored in a MySQL database using TypeORM.
- A user interface built with Reactjs that displays data in a table and allows the user to perform CRUD operations on the data.
- A table that displays the data in the database.
- A form that allows the user to add new data to the database.
- Buttons that allow the user to edit and delete data from the database.
- The application is styled using CSS.

## Requirements

- TypeScript for both the front-end and back-end code.
- TypeORM to connect to the MySQL database.
- Redux for state management on the front-end.
- Axios for API calls on the front-end.

## Folder Structure

├── client/
│ ├── src/
│ │ ├── components/
│ │ ├── pages/
│ │ ├── store/
│ │ ├── App.tsx
│ │ ├── index.tsx
│ │ ├── setupTests.ts
│ │ └── ...
│ ├── package.json
│ └── ...
├── server/
│ ├── src/
│ │ ├── controllers/
│ │ ├── entities/
│ │ ├── modules/
│ │ ├── services/
│ │ ├── app.module.ts
│ │ └── main.ts
│ ├── package.json
│ └── ...
├── package.json
└── README.md

## Installation

- Clone the repository from GitHub:
  https://github.com/biolabalo/ChamsMobile-crud
 
 - Install dependencies for the server and client:  npm run install:all


 - Start the client:  cd client && npm run dev