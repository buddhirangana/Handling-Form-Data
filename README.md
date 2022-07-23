# Handling Form Data

- Before starting to implement the `Handling Form Data`, we need to set up the required environment for the project. Below sections will guide you to set up the environment. If you have already installed them, you can skip the relevant sections.

## Installing Node.js

Check whether `Node.js` and `npm package manager` is already installed by typing the following commands in the command line.
```bash
# Check the Node.js version
node -v

# Check the npm version
npm -v
```
> **Important**: This project requires a Node.js version of 14 or higher.

If the above is not installed, download suitable `Node.js` package for your OS using the following [link](https://nodejs.org/en/download/) and install it.

## Installing Angular

Check whether `Angular CLI` is already installed by typing the following command in the command line.
```bash
# Check whether Angular CLI is available 
ng
```

If the `Angular CLI` is not installed, install it using the `npm package manager` by typing the following command in the command line.
```bash
# Install Angular CLI globally
npm install -g @angular/cli
```

## Installing Dependencies

After completing the above installations, we must install the dependencies specified in the `package.json` files for the `backend` and the `frontend`.

- To install the dependencies of the backend, type the following command from the root of the project.
```bash
# Install the dependencies
npm install
```

- To install the dependencies of the frontend, first navigate to the frontend folder and then install the dependencies using the following command.
```bash
# Navigate to frontend directory
cd frontend

# Install the dependencies
npm install
```
