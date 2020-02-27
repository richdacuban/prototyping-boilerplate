# TEC Opt-In ad assignment

This is a simple and quick demo project created for Thought and Expression Company to demo a simple session based system for allowing a user to opt-in to see ads that may otherwise be objectionable. This project uses only plain html, plain javascript and css styling. The internal "ads" are in iframes and communicate with the parent window via postMessage

## Minimal Requirements

- Git
- HTTP server of choice

## Get Started

- `$ git clone https://github.com/thoughtis/prototyping-boilerplate.git your-project-name`

### HTTP Server

- If you have PHP or Python installed, you can use their built in HTTP server without installing anything else.
- Otherwise
  - `$ npm install`
  - `$ npm run start` to serve locally using `http-server`

## Scripting

This boilerplate uses ECMAScript Modules in the browser. See [this post](https://jakearchibald.com/2017/es-modules-in-browsers/) on Jake Archibald's blog for more info on how to use them this way.

> Note: My example modules use strict mode in each module. This is a personal choice and may not be required.

## Styling

No magic here, just use custom properties if you need variables, and you can get them ready for production later.
