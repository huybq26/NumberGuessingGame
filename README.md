# NumberGuessingGame

A mobile game that lets you and your friends play with numbers.
In the start of the game, you will choose a secret number for your phone to guess. This number must be bigger than 0 and smaller than 100. After that, your phone will start guessing. For each time your phone propose a number, you should tell it that this number is smaller and bigger than the secret one, and it will guess another, till it is correct. After it finds out, the screen will display the secret number and the rounds took to guess it.
It is a fun game. You can bet how many rounds it will take to find out the number with your friends, or you can use this to replace the rock, paper, scissors game :)

In order to run this app, you need to install Expo CLI and have Android Studio ready with an Emulator. Follow the guides below:

Initialize node modules:
### `npm install --save react-tinder-card --legacy-peer-deps`
### `npm install`
Installing Expo CLI:
### `npm install --global expo-cli`
Verify that the installation was successful by running expo whoami. You're not logged in yet, so you will see "Not logged in". You can create an account by running expo register if you like, or if you have one already run expo login, but you also don't need an account to get started.

To run the app in development mode:
### `expo start`

Run the Android Emulator directly in Android Studio

    Click File > Settings > Tools > Emulator (or Android Studio > Preferences > Tools > Emulator on macOS), then select Launch in a tool window and click OK.
    If the Emulator window didn't automatically appear, open it by clicking View > Tool Windows > Emulator.
Then go to the terminal, press 'a' to open in your emulator android, or you can use your phone to scan the QR code in development mode.
