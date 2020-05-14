<!-- TABLE OF CONTENTS -->
# Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started-with-back-end)
  * [Prerequisites](#prerequisites)
  * [Installation](#instructions-for-installing-and-running-the-applications-front-end-locally)
  
  <!-- ABOUT THE PROJECT -->
  # About the Project
  Oikomiskaveri mobile-app
  
Project is to create a mobile app to help with the use of dental braces via notifications and stat-tracking for a more complete treatment care. Current state of the app tracks user inputs and notifies when a set of time has been completed. Stat-tracking is currently only availible from Google firebase, however tracking is to be implimented to the app as well. This document will focus on the front-end of the project.
  
  <!-- Build With -->
## Built With
* [Google Firebase](https://firebase.google.com/)
* [React Native](https://reactnative.dev/)
* [Expo CLI](https://expo.io/)
* [Node.js](https://nodejs.org/en/)
* [Express -framework for Node.js](https://expressjs.com/)

<!-- GETTING STARTED -->
# Getting Started with Back-End

Make sure Node.js is installed to your computer. Download from: `https://nodejs.org/en/`

## Prerequisites

### To install and run the application you need Git, Node.js, Expo CLI and Expo app (instructions for installing these following)

#### Instructions for installing Git for Windows
Download the git installer from https://gitforwindows.org/ and follow it's instructions.

#### Instructions for installing node.js
Download the node.js installer from https://nodejs.org/en/download/ and follow it's instructions.

#### Instructions for installing Expo CLI
Open your terminal and run the following command on it `npm install -g expo-cli`.

#### Instructions for installing Expo app (Android/Apple)
Open Google Play Store / AppStore in your mobile, search for Expo and download the app.

## Instructions for installing and running the applications front-end locally

#### Step 1
The easiest way to get the project is to clone it. Create an empty folder and open the Git-terminal (for example GitBash) on it. Then clone the project using following command `git clone https://github.com/oikomiskaveri/oikomiskaveriapp`.

#### Step 2
Navigate to the cloned project folder and open your (PowerShell)-terminal

#### Step 3
To install the needed dependencies execute the following command in your terminal `npm install`.

#### Step 4
Now you can start up the application by writing the following command to the terminal `expo start`, it will open expo's own terminal to web browser on port localhost:19002.

Switch the connection from LAN to Tunnel from the left side of the browser just above the QR-code. You can also use LAN but then your computer and mobile should be on the same network. Wait until it reads 'Tunnel ready' in your expo terminal.

#### Step 5
Open the Expo app in your mobile, navigate to the Projects view and scan the QR-code from the expo terminal by pressing 'Scan QR Code' on the app. Now the application should start building on your mobile and should be ready for testing after few seconds (and sometimes after few seconds more).

