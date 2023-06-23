# Multi Window Communication

This example shows four different ways of pushing out messages from a single source to multiple windows.

- Broadcast Channel using a Shared WebWorker
- Broadcast Channel from the Publisher Page
- OpenFin IAB Message Bus from the Publisher Page (only within OpenFin)
- OpenFin Channel API from the Publisher Page (only within OpenFin)

You may want to have one window/worker acting as the connection to a websocket and then have that push out data across multiple windows.

This hasn't been built as an example of best practice. The goal is to give you a way of defining what type of message you want to share, how you want to share that message and if there is a threshold in milliseconds you do not want a message to exceed.

## Running the example

You can clone this repo, run npm install and then run npm start. The web server should show localhost:3000. If you open this url in the desktop browser you can (run the test in the browser) and if you have OpenFin installed you will be able to launch a platform through a fins link by click on the link displayed within your desktop browser.

More information about OpenFin:

- https://openfin.co/ -> main site
- https://developers.openfin.co/docs/getting-started => getting started guide
- https://github.com/openfin -> OpenFin Github repo
