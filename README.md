# Office Control Panel
Simple control panel created during a 4-hour hackaton in Milan (*Campionato Universitario Makers*).

## Topic of the Hackaton
The keyword was *_environment_* ('Ambiente', in Italian).

We tried to monitor the working environment and change some parameters (temperature and lighting system in the office) according to external parameters (eg. max 7° delta).

## Brief (Technical?) Explaination
The Arduino communicates with a small node server (my computer) with the serial bus, using the **serialport** library, and launches an http server (the control panel).
The Control Panel looks for a file (data.json) and displays it in a web app, built using materialize.css for styling.

### Installation
Run `npm install ` to install the modules in package.json and  ` node server.js` to start the server.