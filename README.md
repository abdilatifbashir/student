### In-memory management
The task uses redux which persist data to local storage.

### Tech stack used.

- `typescrip`
- `reactjs`
- `redux`


### Install NVM for managing Node.js versions

The reason for using [nvm](https://github.com/coreybutler/nvm-windows) instead of other install types is mainly in how easy it is to have multiple versions of Node.js (if needed) without too much of extra complexity. Sometimes applications might require a certain version of Node.js to work, so having the flexibility of using specific versions can save a lot of time from you.

1. Download and install nvm-setup.zip for the stable maintenance release from [here](https://github.com/coreybutler/nvm-windows/releases)
2. To install Node.js and NPM, open CMD prompt and run
   - `nvm install latest`
3. If everything went well, check the Node.js version installed by running
   - `node -v`
   - (Another option is to open a new Terminal window/tab.)
4. Use the installed Node.js version that is outputted from the previous command e.g. v11.12.0
   - `nvm use 11.12.0`
5. Install [node-gyp](https://github.com/nodejs/node-gyp), a command-line tool written in Node.js for compiling native addon modules for Node.js
   - `npm install -g node-gyp`
6. Install the build tools for compiling native Node.js modules in windows by running
   - `npm install —global —production windows-build-tools`

## Install

Next up, installing and running the application use node v12 and above

- `git clone https://github.com/abdilatifbashir/student `
- `cd student`
- `npm install`
- `npm install`
- `npm start`

### implemented functionality

The app add and delete Student details and manages data on redux that persist to localstorage


