# Live Mission Recording - Drone State Requirement 3

## What is This?

This repository contians a base implementation of the UX SDK [by DJI](https://github.com/dji-sdk/Mobile-UXSDK-Android), and an implementation of retreiving the relevant information that defines the state of the DJI Mini 2 drone:
- Latitude;
- Longitude;
- Altitude;
- Gimbal pitch angle;
- Drone yaw angle;
- Recording duration in milliseconds (if a recording was attempted).

## How to use the application?
Make sure to create an API Key via the official [DJI Developer platform](https://developer.dji.com/), and paste the key in the AndroidManifest.xml file.


If you want to retrieve the state of the drone, you must:
- Install the application on your Android phone;
- Connect the phone to the drone remote controller;
- Turn on the drone and the remote cotnroller;
- Launch the applicaiton;
- Click on "Complete Demo of Default UI Widgets" button;
- Launch the drone up in the air;

Then, you have two options:
- Click on "PHOTO" - this will mimic that a person is trying to make a photo. The current state of the drone will be displayed on the screen.

    ***OR***
- Click on "VIDEO" - this will mimic that a person is trying to make a video. Upon pressing the "VIDEO" button the second time, the system will save for how long the user has "recorded" a video. The current state of the drone will be displayed on the screen with the duration of the video recording.