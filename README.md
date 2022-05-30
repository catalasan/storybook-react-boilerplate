# Getting Started with Storybook React Boilerplate

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

Since we are only developing react components, we don't need react-scripts package used for building react apps

### `npm uninstall --save react-scripts` or `yarn remove react-scripts`

Removed unnecessary files that are related to building an app.

### `rm -rf public` and other test files

Installed propTypes package used in storybook

### `npm install --save prop-types` or `yarn add prop-types`

Installed css modules package used in storybook

### `npm install --save-dev storybook-css-modules-preset` or `yarn -D add storybook-css-modules-preset`

Installed storybook addon postcss package (to remove deprecation warning from previous preset)

### `npm install --save @storybook/addon-postcss` or `yarn add @storybook/addon-postcss`

Finally, installed storybook itself

### `npx sb init`

## Available Scripts

In the project directory, you can run:

### `npm start` or `yarn start`

Runs the component in the storybook mode.\
Open [http://localhost:6006](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm build` or `yarn build`

Builds the component for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your component is ready to be deployed!
