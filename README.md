# Reservation-Challenge
A demo application that implements a custom solution for an automotive service reservation form.

The app was created in React Native using a bare React Native CLI project.

Developed and tested on Android

<img src="/20200707-231746.gif?raw=true" width="300px">

## Libraries and features implemented:

- Formik for getting values in and out of form state and handling form submission
- ReactNativeFormik for helpers, eliminating boilerplate, and focusing next input
- Yup for its schema builder, value parsing, and validation
- KeyboardAwareScrollView for moving focused form elements above keyboard
- Material Textfield for animations and formik error handler integration
- select-multiple and simple-radio-button for their clean UI elements

- table-component used for the horizontally scrollable Date and Time Picker. Customized to populate table with days of the week and time slot buttons
- AwesomeButton for animated feedback and conditional success/error alerts

## Limitations

Custom Components were not structured to share state data, so there was no way to display an encompassing review of everything selected by the user.

This can be solved by implementing a global state management system like Redux

## Install
npm install

npx react-native run-android
