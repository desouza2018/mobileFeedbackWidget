#

[Logo of the project](https://logo_link)

## Feedback_Widget

... Description

## Technologies used in this project

* react-native
* expo
* typescript
* phosphor-react-native
*...

## Services Used

* Github
* ...

## Getting started

* To install expo:

    > $ npm install -g expo-cli

## Checking expo instalation

* To checking the sucessfull expo instalation:

    > $ expo --version

* on sucessful case, the expo version will be returned:

    > $ 5.4.3

## Create the project

* To create the project (yarn package manager):

    > $ expo init project_name

### To choose a Template

* Template with a minimal app as clean as an empty canvas

    > $ blank

* Template with same as blank but with Typescript configuration

    > $ blank (Typescript)

* Template with several example screens and tabs using react-navigation and Typescript.

    > $ tabs (Typescript)

* Template with bare and minimal, just the essentials to get you started

    > $ minimal

### To create the project (npm package manager)

    > $ expo init project_name --npm

* Follow before steps on Choose a Template

### To run the app

    > $ expo start

## Commands used when building app

[Using a Google Font](https://docs.expo.dev/guides/using-custom-fonts/?msclkid=b941de44cfe711ecb58a3b727e5b1f8b)

    > $ expo install expo-font @expo-google-fonts/inter

* [AppLoading is [Deprecated!]](https://docs.expo.dev/versions/latest/sdk/app-loading/?msclkid=b35ef870d07b11ec8e83639c4e44289a) to verify if app is loading the fonts:

    > $ expo install expo-app-loading

### So dont use AppLoading but Use expo-splash-screen directly instead

SplashScreenpreventAutoHideAsync() and SplashScreen.hideAsync()

#### SplashScreen instalation

Read more about [SplashScreen](https://docs.expo.dev/versions/latest/sdk/splash-screen/)

    > $ expo install expo-splash-screen

#### Phosphor React Native

* [phosphor-react-native](https://www.npmjs.com/package/phosphor-react-native?msclkid=393686d8d07a11ecafbf8f28bef12707): a flexible icon family for interfaces, diagrams, presentations.

* With npm:

    > $ npm install --save phosphor-react-native

* Or with yarn:

    > $ yarn add phosphor-react-native

#### React Native SVG

* [react-native-svg](https://www.npmjs.com/package/react-native-svg?msclkid=bf84b29cd07a11ec8e2564aaf6645e2a)

    > $ expo install react-native-svg

#### React Native Iphone X Helper

* [react-native-iphone-x-helper](https://www.npmjs.com/package/react-native-iphone-x-helper?msclkid=5c663561d07811ec9d3dda0e7ec12216). A library to help you design your react-native app for notched iPhones:

    > $ npm i react-native-iphone-x-helper --save

#### React Native Bottom Sheet

* [React Native Bottom Sheet](https://gorhom.github.io/react-native-bottom-sheet/#features). To install:

* With yarn:

    > $ yarn add @gorhom/bottom-sheet@^4

* With expo:

    > $ expo install @gorhom/bottom-sheet@^4

* or npm:

    > $ npm install @gorhom/bottom-sheet@^4

### To install the dependencies of Reac Native Bottom Sheet

[Reanimated](https://docs.expo.dev/versions/latest/sdk/reanimated/?msclkid=7b562beccfff11ec82c0911b7f39ebc2)

    > $ expo install react-native-reanimated

[GestureHandler](https://docs.expo.dev/versions/v45.0.0/sdk/gesture-handler/)

    > $ expo install react-native-gesture-handler

* with npm:

    > $ npm install --save react-native-gesture-handler

* or yarn:

> $ yarn add react-native-gesture-handler
