# Social-network-API

## Introduction
MongoDB is a popular choice for many social networks due to its speed with large amounts of data and flexibility with unstructured data. Over the last part of this course, you’ll use several of the technologies that social networking platforms use in their full-stack applications. Because the foundation of these applications is data, it’s important that you understand how to build and structure the API first.

Your Challenge is to build an API for a social network web application where users can share their thoughts, react to friends’ thoughts, and create a friend list. You’ll use Express.js for routing, a MongoDB database, and the Mongoose ODM. In addition to using the [Express.js](https://www.npmjs.com/package/express) and [Mongoose](https://www.npmjs.com/package/mongoose) packages, you may also optionally use a JavaScript date library of your choice or the native JavaScript `Date` object to format timestamps.

Ensure that the `mongoose` package is using version 6+. The latest version of `mongoose` (version 7+) introduces potential breaking changes to activities. All activities have version `6.9.2` in their respective `package.json` files, but should you install `mongoose`, please use `npm i mongoose@6.9.2`.

No seed data is provided, so you’ll need to create your own data using Insomnia after you’ve created your API.

## Installation

To install this project, clone the repo into your local machine. Once cloned, run npm install in your terminal to install all of the dependencies necessary for the project to run. Finally, run node server.js in your terminal to run your server. Navigate to an application, such as Insomnia, that allows you to view API routes in order to see the routes in action!

## Credits

This project uses Insomnia to test API routes and Screencastify to create the walkthrough video.

## Demonstration

![Walkthrough video](./walthrough-video/social-network-api.gif)
