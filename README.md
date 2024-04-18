If you cannot connect using CLI, follow these steps:
1- Put the json file received from firebase into the app folder
2- Copy the firebaseoptions.dart file and create this file in your own project. And enter your own data where it says 'your id' at the bottom. This data is available in the json file and firebase console.
3- Copy the build gradle file at the project level and replace its own file completely
4- Take the app level gradle file and copy it to your own project. Replace com.example.firebase with the name of your own project. Like 'com.example.yourappname'
Now your application has established firebase connection.
