## Introduction
This is an application for product owners to automatically organize their user feeback, connecting the back end, based in Node.js, to the front end through React.js.  Product owners and startups often need to track users for a service, survey those users, and review the data in order to improve the application.  The application will allow product managers to more easily go through this process.

Users sign up for an account via Google OAuth to identify users individually, rather than creating an account, then pay for e-mail credits with Stripe.  Site owners can then create a "campaign" or survey to send to their users for feedback collection.  Inside this e-mail is a simple link to collect feedback.  The seervice will tabulate that feedback into a report for Site owenrs to analyze data.

## Technologies
- Express.js
- Google OAuth - Express, MongoDB, and PassportJS (for user OAuth)
- Stripe API (to handle billing) with MongoDB (to store payment records in a database)
- React.js + Redux + Redux Form (for survey data storage)
- 3rd party e-mail provider to send surveys
- E-mail provider + Express + Mongo (to store data provided by the surveys)
- MongoDB (to tabulate feedback)
- MongoDB + React + Redux (to present report of the responses)

## Table of Contents

## Relationship between Node and Express

## Generating Express Apps

## Express Route Handlers

