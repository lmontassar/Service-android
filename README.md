# Android Service Example

This repository contains a simple Android application demonstrating the usage of Android Services. It's part of an academic exercise to understand how services work in Android development.

## Project Overview

The project consists of two main components:

1. `MainActivity`: The main activity of the app, which contains buttons to start and stop a service.
2. `MyService`: A simple Android Service that logs its lifecycle methods.

## Features

- Start a service using a button click
- Stop the running service using another button click
- Demonstration of Service lifecycle methods (onCreate, onStartCommand, onDestroy)

## How to Use

1. Clone the repository to your local machine.
2. Open the project in Android Studio.
3. Run the app on an emulator or physical device.
4. Use the "Start Service" button to start the service.
5. Use the "Stop Service" button to stop the service.
6. Check the Logcat in Android Studio to see the service lifecycle method logs.

## Code Structure

- `MainActivity.java`: Contains the UI logic and buttons to control the service.
- `MyService.java`: Implements the Android Service with overridden lifecycle methods.
- `activity_main.xml`: Layout file for the main activity (not included in the provided code snippet).

## Learning Objectives

This project helps in understanding:

- How to create and implement an Android Service
- The lifecycle of an Android Service
- How to start and stop a service from an Activity
- Logging in Android for debugging purposes

## Note

This is an academic exercise and is intended for learning purposes. It demonstrates basic service functionality and may not include all best practices for production-level applications.
