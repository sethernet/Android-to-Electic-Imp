# Android-to-Electic-Imp
Android app to communicate with Electric Imp via HTTP Requests

##Overview
A simple Android application that can be used to send HTTP POST and GET requests to an Electic Imp Internet of Things Device 
(https://electricimp.com/)

This app includes a POST button and a GET button that sends the specified request to the Imp Agent.

##Setup
The easiest way is to use Android Studio to import the repository from GitHub

##Usage
Navigate to the MainActivity file, which is located at SendRequests/app/src/main/java/com/androidtoimp/sendrequests/MainActivity.java

and within the doInBackground method, find the line
```js
URL url = new URL("Your Agent URL Here");
```
Enter the specific URL for your Agent. 
From here you can change your URL parameters as needed for your specific project.

And that's it!

##Special Thanks

Thanks to Numetric Technologies for providinig an excellent tutorial on how to use the HttpURLConnection class in an Android app.
This project is largely based on that tutorial, see the details here:
https://www.numetriclabz.com/android-post-and-get-request-using-httpurlconnection/



