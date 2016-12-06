# RemindMe

## About the App

RemindMe is a native Android app developed for Dr. Lehr's CS3398 Software Engineering class. 
The app is designed to be used every day to help the user keep track of and organize their daily
tasks. You can create tasks, set due dates, and keep them organized into lists.

### Technologies Used
The app is built on the Android framework, and uses an implementation of SQLite to store the user's
lists and tasks on the phone. 

## How to Build the App

RemindMe is a self contained project that is ready to build and deploy. All that's needed to
build the app is to check it out from the Github repository as a new project using the 
Android Studio VCS tools. When the project is loaded, click Tools -> Build to build the project. 
After Android Studio is finished building the project, it can be installed on a phone or run in
an Android Emulator.

## Third Party Libraries Used
We would like to give credit to the developers of the following libraries that were critical in the
development of the app.


* [Parceler](https://github.com/johncarl81/parceler), a serialization library for sending data between activities
* [Stetho](http://facebook.github.io/stetho/), a debugging bridge developed by Facebook that makes it easy to inspect your app with Google Chrome
* [DBFlow](https://github.com/Raizlabs/DBFlow), an Object Relational Management library that uses Java annotations to make creating and managing databases in Android simple
* [Advanced Recycler View](https://github.com/h6ah4i/android-advancedrecyclerview), a library for Android RecyclerView that adds features such as swiping and Drag and Drop
* [Material Dialogs](https://github.com/afollestad/material-dialogs), a library that condenses the creation of pop-up dialogs into a single function call