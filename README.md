# React Router Dom v6 Catch-All Route Issue

This repository demonstrates a bug in React Router Dom v6 where the catch-all route (`/*`) is always triggered, regardless of whether other routes match.  This issue can prevent other routes from working correctly.

The solution shows how to use the `useLocation` hook to resolve this issue, creating a more robust routing mechanism.

## Setup

1. Clone the repository.
2. Navigate to the project directory.
3. Run `npm install` to install dependencies.
4. Run `npm start` to start the development server.

## Bug

The `App.js` file contains a React Router v6 setup with a catch-all route that is incorrectly triggered even when other routes are matched.

## Solution

The `AppSolution.js` file presents a solution demonstrating a more reliable approach using the `useLocation` hook.