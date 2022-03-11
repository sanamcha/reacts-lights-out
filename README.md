# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

## Lights Out
This exercise provides a chance to work with React events where the state and events happen in different classes.


### The Game

Lights Out is a logic/puzzle game, played on a gird of individual lights, which can either be lit or unlit. The puzzle is won when when all of the lights are turned off.

You can click on a cell to toggle that light — but it also toggles the light above it, to the left of it, to the right of it, and below it. (Cells on an edge or in the corner won’t flip as many lights, since they are missing some neighbors).

### Plan

Before reading further, take a moment to think about how you would design this, component-wise.

We’ll give you a component design further down, but thinking about the requirements and what components/state/props would be needed will help you learn the skills to design applications out of components.

    = STOP = DRAW YOUR DESIGN OUT before reading further.



This game will be built from three components: (hover to view)


When the game is won, the board should not be shown, but a simple “You Won” message should show in its place.

A small amount of code is provided, but there are lots of places where you’ll need to write code to get the game functional.
