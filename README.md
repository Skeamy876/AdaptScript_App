
# AdaptScript Application Documentation
## Overview
The AdaptScript Application represents a meticulously crafted mobile platform developed with React Native. This application provides an intuitive interface to engage users with the AdaptScript programming language. Powered by a Flask compiler server in the backend, the primary goal is to facilitate a seamless learning experience for programmers. This documentation delves into the intricacies of the application's design, implementation, and notable features. Special attention is given to its integration with a Large Language Model (LLM) - Palm 2, achieved through the adept use of PLY (Lex and Yacc). The primary objective of the application is to serve as an educational tool, guiding and empowering programmers in their journey to grasp the intricacies of the AdaptScript language.

## Application Overview
## Features
User Authentication: Users can log in, access the code editor, and log out, providing a personalized experience.

Code Editor: The application includes a robust code editor that provides a user-friendly environment for writing and executing AdaptScript code.

Categories: Programming constructs are organized into categories such as Variables and keywords, Operators, Decision Making, Loops, and Functions. This categorization aids users in learning and understanding different aspects of the language.

Integration with LLM: The application utilizes PLY (Lex and Yacc) to analyze and tokenize code. It then sends appropriate messages to the Large Language Model (LLM) - Palm 2, facilitating a seamless connection between the code editor and the LLM. Visual and audio feedback is provided to enhance the user experience.

## Application System Architecture Diagram

![image](https://github.com/Skeamy876/AdaptScript_App/assets/74942224/47fc37c6-17c3-4e58-8536-4ffad37df70c)


## Getting Started
To get started with the AdaptScript Application, follow these steps:

1. Clone the Repository:

```
git clone https://github.com/your-username/Adaptscript_app.git
cd Adaptscript_app
```

2. Install Dependencies:
Ensure you have Node.js and Expo CLI installed. If not, you can install Expo CLI globally using:

npm install -g expo-cli


3. Install Project Dependencies:
Install the project dependencies using:

```
npm install

```



4. Run the Application:
Start the Expo development server:

```
expo start
```

This will open a new tab in your web browser with the Expo DevTools. You can run the application on an emulator or scan the QR code with the Expo Go app on your mobile device to see the app in action.

For Android:

```
expo start --android
```


For iOS:
```
expo start --ios
```
If you encounter any issues, follow the instructions in the Expo DevTools to troubleshoot.

Explore the Features:
Open the application on your emulator or device, log in, and explore the code editor and various categories to understand and use the features.
