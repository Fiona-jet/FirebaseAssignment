# iOS App with Firebase Integration

This project is an iOS app developed using *Swift*, with Firebase integration. The app includes functionalities such as user signup and a list view to display data.


================================================================================================######## [ 2007089 ]   #######


## Prerequisites

Before running the app, ensure you have the following:

- macOS with Xcode installed (version 14.0 or higher recommended).
- A Firebase account.
- Swift programming knowledge.


## Setup Instructions

### 1
Firebase Integration
Firebase Authentication
Signup: The SignupPage enables users to create an account using their email and password.

Here's a complete README.md file for your iOS app:

markdown
Copy code
# iOS App with Firebase Integration

This project is an iOS app developed using **Swift**, with Firebase integration.
The app includes functionalities such as user signup and a list view to display data.


===============================================================================####### [ 2007085 ] ####



## Features
Google OAuth Integration:

The Sign in with Google button initiates the Google OAuth authentication process using the Authentication class.
Key Features:
User-Friendly Design: The login screen includes input fields for email and password, ensuring a smooth user onboarding process.

Sign-Up Functionality: A prominent "Sign up" button is available for new users.
Account Access: Existing users are prompted to log in easily.
Modern Aesthetics: The screen layout boasts a sleek red and black background, enhancing the overall look and feel of the app.

## Interface Details:
Top Section: Displays a "Welcome" message in white text against a red background.
Middle Section: Black background with fields for email and password.
Bottom Section: A red "Sign up" button and a prompt to log in for existing users.


==============================================================-============================####### [ 2007088 ] ####

## Description
This project features a mobile application designed to manage and list different breeds of dogs. The interface is simple, user-friendly, and visually appealing, making it easy for users to interact with the application.

## Key Features:
List Management: The application allows users to create and maintain a list of dog breeds.

## Intuitive User Interface:
The main screen displays the title "Dogs" at the top, followed by a list of dog breeds such as "Pitbull," "Beagle," and "Jack Russell Terrier."
Add New Items: A plus icon in the top right corner enables users to add new dog breeds to their list easily.
Clear Separation: Each item in the list is separated by a thin line, providing clear visual distinction between entries.
Modern Design: The app features a light gray background with black text, ensuring readability and a clean look.

## User Interface Layout:
Title: The title "Dogs" is prominently displayed at the top of the screen in bold text.
List Items: The list of dog breeds is displayed below the title, each on a separate line.
Add Button: A plus icon is located in the top right corner for adding new list items.



## .. Clone the Repository

bash
git clone <repository-url>
cd <repository-folder>

Install Dependencies:
sudo gem install cocoapods
pod install

Project Structure:
├── SignupPage.swift         // Handles user registration.
├── ListViewPage.swift       // Displays the list of items.
├── AppDelegate.swift        // Configures Firebase.
├── SceneDelegate.swift      // Handles scene management.
├── GoogleService-Info.plist // Firebase configuration file.
├── Podfile                  // Manages CocoaPods dependencies.
