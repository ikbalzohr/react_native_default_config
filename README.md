# Welcome to My Project 👋

//

## Get started

1. Install dependencies

   ```bash
   npx expo install -- --save-dev eslint prettier eslint-config-expo eslint-config-prettier eslint-plugin-prettier

   npx expo install react-native-svg

   npx expo install --save-dev react-native-svg-transformer

   ```

2. Copy all file folder config to root project directory

3. Run command
   If you don't install husky pre commit skip this step

   ```bash
   npm run prepare
   ```

4. Build app before start
   If you haven't used svg yet skip this step

   ```bash
   npx expo prebuild --clean
   npx expo run:android
   ```

5. Start the app

   `Ctrl + F5` for Visual Studio Code
   or use command

   ```bash
    npx expo start
   ```
