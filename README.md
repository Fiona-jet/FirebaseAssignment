# iOS App with Firebase Integration

This project is an iOS app developed using *Swift*, with Firebase integration. The app includes functionalities such as user signup and a list view to display data.


====================================================######## [ 2007089 ]   #######

![Firebase_Connection]([https://github.com/Fiona-jet/FirebaseAssignment/blob/main/ss1.webp]
![Firebase_Connection]([image_url](https://github.com/Fiona-jet/FirebaseAssignment/blob/main/ss2.webp))
![Firebase_Connection]([image_url](https://github.com/Fiona-jet/FirebaseAssignment/blob/main/ss3.webp))
![Firebase_Connection]([image_url](https://github.com/Fiona-jet/FirebaseAssignment/blob/main/ss4.webp))


## Prerequisites

Before running the app, ensure you have the following:

- macOS with Xcode installed (version 14.0 or higher recommended).
- A Firebase account.
- Swift programming knowledge.

Firebase Integration
Firebase Authentication
Signup: The SignupPage enables users to create an account using their email and password.



===============================================================####### [ 2007085 ] 

![LoginView]([image_url](https://github.com/Fiona-jet/FirebaseAssignment/blob/main/Screenshot%202024-12-07%20111819.png
))

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




=============================================-============================####### [ 2007088 ] ####

![ListView]([image_url](https://github.com/Fiona-jet/FirebaseAssignment/blob/main/Screenshot%202024-12-07%20111627.png))


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

