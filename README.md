# podping-hivewatcher-js

A watcher script for the hive backed podping network. (Javascript)

Uses [@hiveio/dhive](https://yarnpkg.com/package/@hiveio/dhive) to communicate with the Hive blockchain.

# Use

1. Add `hive-watcher.js` and `index.html` to a web server
    1. Ex using node:
        1. Run `npm install http-server -g`
        2. Run `http-server`
            1. Will start a server at `http://localhost:8080/` by default
    2. Ex using Python:
        1. Run `python -m http.server`
        2. Will start a server at `http://localhost:8000` by default
2. Open `index.html` in a web browser. Podpings will be added to list as they are received.
