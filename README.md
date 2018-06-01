# Cross-platform ReactXP e-shop

This app works on React Native (iOS, Android) and WEB.

The commands in the instructions below assume you are in the root of this repo.

### Initial Setup

- Run `yarn`. This fetches the dependencies.

### Building for Web

- Run `yarn run web-watch`. This compiles the TypeScript code and recompiles it whenever any files are changed.
- Open `index.html` in your browser to view the result.

### Building for React Native

- Run `yarn run rn-watch`. This compiles the TypeScript code and recompiles it whenever any files are changed.
- In another command prompt run `yarn start`. This starts the React Native Packager.
- Use Xcode or Android Studio to build and deploy the native app code just like you would with any other React Native project.
