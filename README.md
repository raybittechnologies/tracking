# App Activity Tracker

This Node.js application tracks the activity of apps opened on your computer and logs it into a file called `processes.json`.

## Installation

const va = require("visible-app");

const getApp = async () => {
console.log(await va());

<!-- {
  activeWindow: 'test.js - visible-app - Visual Studio Code',
  processName: 'Visual Studio Code',
  timeStart: '3/27/2024, 1:39:03 PM'
} -->

};

setInterval(getApp, 2000);

## Contributing

Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or create a pull request.

## Development

For now URL of active tabs are fetched only on debuging mode, when electron app is developed, it wont be necessary.

1. cd-><Firefox Installation directory> firefox --remote-debugging-port=9223
2. cd-><Chrome Installation directory> chrome --remote-debugging-port=9222
