# react-native-express-upload-image

This is an example of how to upload an image from react-native on android to an express server.

# installation

## instal dependencies

    cd ./uploadApp
    npm install
    cd ../uploadServer
    npm install

## change IP to upload

go to ./uploadApp/App.js

Change SERVER_URL variable to the IP of your server.

## run server

    cd ./uploadServer
    npm start

## run application

### android

    cd ./uploadApp
    npx react-native start
    npx react-native run-android

### ios

    cd ./uploadApp
    npx react-native start
    npx react-native run-ios

# warning

The code has only been tested for an android app and on unbuntu 20.
