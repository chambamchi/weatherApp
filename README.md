# Weather App - DataOps

## Description

Sit as close as possible to warm fire without sitting on cold floor it's 3am, time to create some chaos one of these days i'm going to get that red dot, just you wait and see purr as loud as possible, be the most annoying cat that you can, and, knock everything off the table love me! why must they do that find a way to fit in tiny box. Lick the plastic bag find box a little too small and curl up with fur hanging out for sleep everywhere, but not in my bed yet my slave human didn't give me any food so i pooped on the floor.

## Installation

- Clone this repo
- On your terminal, 'cd' to root folder
  - 'npm i' to install dependencies
  - delete data folder to start your own
  - setup 'env' with
    - 'PORT' of your choosing
    - 'CITY' of your choosing
    - 'API_KEY' from openweather
  - `npm i` to install dependencies
  - `node fetchWeather.js` to create/ update data folder
  - `node app.js` to start server

  ## Using Docker
  - Open your Docker desktop
  - Make sure you're on the same path as Dockerfile
  - On your terminal run:
    - `docker build -t <app-name:tag> .` or `docker build -t weatherapp:1.0 .` - to build image based on Dockerfile
    - `docker run -p <local-port>:<container-port> <image-name>` or `docker run -p 3000:5000 weatherapp` - to run a container based on an image

## Tests

We have tests to check if files inside the data folder is correct

## GitHub
