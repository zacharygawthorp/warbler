# Warbler Social App

## Description

The goal of this site is to allow users to search for their favorite Marvel Comics Characters. The site will provide information such as, character name, a brief description of the character, and comic appearances. Users will also be able to keep track of their favorite characters by adding them to a favorites list.

The site is deployed on Heroku and can be found [here](https:)

![Homepage Image](static/images/warbler-cover.png)

## Data Source / API

The Warbler Social App utilizes a news [API](https://newsapi.org/) in order to pull current headlines under the What's Happening section.

The tech stack is a Python back end using Flask, with server rendered jinja pages. The app uses Bcrypt for authentication and SQLAlchemy for database management.

## Functionality

- Create user profile
- Search Warbler for other users.
- Create messages and interact with other users.

## User Flow

1. Landing Page - Signup/Login to user account.
2. User Sign-Up Page - Allows user to create personal profile/account.
3. User Login Page - Allows user to login to existing profile/account.
4. Home Page - Allows user to search for other users and create messages.
5. Users Profile Page - User can see their information as well as followers, following, messages, and likes.
