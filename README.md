# React Native - Expo Folders Structure
~~~ssh
code-base/
├── .expo/
├── .expo-shared/
├── assets/
│   ├── fonts/
│   ├── images/
├── node_modules/
├── src/
│   ├── components/
│   │   └── MyComponent.tsx
│   ├── screens/
│   │   └── HomeScreen.tsx
│   ├── navigation/
│   │   └── AppNavigator.tsx
│   ├── services/
│   │   └── ApiService.ts
│   ├── styles/
│   │   └── GlobalStyles.ts
│   └── utils/
│       └── helpers.ts
├── .gitignore
├── App.tsx
├── app.json
├── babel.config.js
├── package.json
├── tsconfig.json
└── README.md
~~~

# Explain

## There files are auto create and update [Can change]:
    .expo/
    .expo-shared/
    .node-modules/
    .gitignore

## Some folder:
    assets:
        - images:
        - fonts:
    => Include: logo, font, splash_icon,...

    src:
        - components => include some components in your app (button, input, ...)
        - constants  => include some "CONST" (about: color, path, sth else,...)
        - navigation => include navigation for your app (like: screen)
        - screens    => include screens in your app (design by Figma - code on RN)
        - styles     => contain file TS about CSS style in your app
        - utlis      => contain utility functions
        - api        => fetch APIs and collect data

## Some files:
    app.json => config for your app (like: name, version, icon,...)
    App.tsx  => Like main# MyNewRepo
