WePUTS
======

Web Page Users Tracking System

Introduction:
Based on Qt and Play Framework 2, this system tracks the activity on a web site and generate/store the visitors data into a database.
It is composed of three parts:
- The Interceptor: placed at the level of PlayFramework's controller request interceptor, it filters the requests and send the desired data to the tracker
- The Tracker: a QT service that gets the requests from the Interceptor and store it into a database
