# useParams Hook Error in React Router v6

This repository demonstrates a common error encountered when using the `useParams` hook in React Router v6: attempting to access URL parameters outside of a component rendered within a route.  The provided code showcases the problematic scenario and its solution.

## Problem

The `useParams` hook relies on the routing context, which is only available within components rendered by a route. Accessing it outside this context leads to an error. 

## Solution

The solution involves moving the usage of `useParams` inside a component that is part of the routing hierarchy.  This ensures that the hook has access to the necessary context.

## Usage

1. Clone the repository.
2. Navigate to the project directory in your terminal.
3. Run `npm install` to install dependencies.
4. Run `npm start` to start the development server.