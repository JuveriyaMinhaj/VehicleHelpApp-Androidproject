
## Vehicle Breakdown Assistance Android App

**Overview**
This Android application is designed to help users during vehicle breakdown emergencies by connecting them with nearby certified mechanics or service providers. The app allows users to submit a help request, track mechanic assignments, and manage service history, all through a user-friendly mobile interface.

**Objective**
To provide a reliable, accessible, and fast breakdown assistance platform that enhances road safety and minimizes wait times for vehicle users.

**Key Features**

* User registration and login via Firebase Authentication
* Breakdown assistance request with location and vehicle information
* Real-time assignment of available mechanics
* Live location tracking using Google Maps
* Service history and request management
* Admin module to manage mechanics and service providers
* Secure user-mechanic communication

**Technologies Used**

* Frontend: Android Studio (Java, XML)
* Backend: Firebase Realtime Database, Firebase Authentication
* APIs and Libraries: Google Maps SDK, Firebase Cloud Messaging, Retrofit
* Local Storage: Room Database

**Architecture**
The project follows a layered MVVM (Model-View-ViewModel) architecture to separate logic and maintain scalability.

* UI Layer (Activities, Fragments)
* ViewModel Layer (Data Management with LiveData)
* Repository Layer (APIs, Firebase interactions)
* Data Layer (Local storage and models)

Setup Instructions

1. Clone the repository using Git
2. Open the project in Android Studio
3. Connect the project to Firebase and add your own credentials
4. Generate a Google Maps API key and insert it in the Manifest file
5. Sync Gradle and run the project on an emulator or physical device




**Future Scope**
* In-app payments integration
* Enhanced real-time tracking of mechanics
* Push notifications with service updates

