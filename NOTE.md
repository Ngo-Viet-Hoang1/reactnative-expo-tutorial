# File structure

1. app
- Contains the app's navigation, which is file-based. The file structure of the app directory determines the app's navigation.

- The app has two routes defined by two files: app/(tabs)/index.tsx and app/(tabs)/explore.tsx. The layout file in app/(tabs)/\_layout.tsx sets up the tab navigator.

2. assets
- The assets directory contains adaptive-icon.png used for Android and an icon.png used for iOS as app icons. It also contains splash.png which is an image for the project's splash screen and a favicon.png if the app runs in a browser.

3. components
- Contains React Native components, like ThemedText.tsx, which creates text elements that use the app's color scheme in light and dark modes.

4. constants
- Contains Colors.ts, which contains a list of color values throughout the app.

5. hooks
- Contains React Hooks, which allows sharing common behavior between components. For example, useThemeColor() is a hook that returns a color based on the current theme.

6. scripts
- Contains reset-project.js, which can be run with npm run reset-project. This script will move the app directory to app-example, and create a new app directory with an index.tsx file.

7. app.json
- Contains configuration options for the project and is called the app config. These options change the behavior of your project while developing, building, submitting, and updating your app.

8. package.json
- The package.json file contains the project's dependencies, scripts, and metadata. Anytime a new dependency is added to your project, it will be added to this file.

9. tsconfig.json
- Contains the rules that TypeScript will use to enforce type safety throughout the project.
