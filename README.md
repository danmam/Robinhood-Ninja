
# Robinhood Ninja

A front-end web app built using [Polymer 2.0](https://www.polymer-project.org) components. It's hosted on Firebase Hosting and uses a NodeJS reverse proxy [CORS Anywhere](https://github.com/Rob--W/cors-anywhere) hosted on Amazon AWS EC2 instance to redirect calls to api.robinhood.com. 

Unofficial Robinhood API documentation: https://github.com/sanko/Robinhood 

![screenshot](https://firebasestorage.googleapis.com/v0/b/robinhood-web.appspot.com/o/RH_V2.svg?alt=media&token=95493c1e-730c-4f13-96fa-6a41c704b715)

### Live App;
https://robinhoodninja.com

### If you feel like setting this up locally;
### Clone

    git clone  https://github.com/eugv86/Robinhood-Ninja

### Setup

##### Prerequisites

First, install [Polymer CLI](https://github.com/Polymer/polymer-cli) using
[npm](https://www.npmjs.com) (assuming you have pre-installed [node.js](https://nodejs.org)).

    npm install -g polymer-cli

Second, install [Bower](https://bower.io/) using [npm](https://www.npmjs.com)

    npm install -g bower

Third, install dependencies

    bower install bower.json
**** If you get a message "Unable to find a suitable version..." select the options that are required by Robinhood Ninja  ****

### Start the development server

This command serves the app at `http://127.0.0.1:8081`

    polymer serve

### Build

The `polymer build` command builds your Polymer application for production, using build configuration options provided by the command line or in your project's `polymer.json` file.  
