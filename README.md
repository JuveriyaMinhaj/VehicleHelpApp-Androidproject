
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

ScreeShots
![Screenshot 2025-06-20 185629](https://github.com/user-attachments/assets/d372a8d3-b25f-4a83-91a3-31b6ecb25bc5)
![Screenshot 2025-06-20 185636](https://github.com/user-attachments/assets/cb30b907-bf5c-404b-a86b-6dd3791a441a)
![Screenshot 2025-06-20 185642](https://github.com/user-attachments/assets/633d3b7e-8173-4807-b38e-d2279ce19a0e)
![Screenshot 2025-06-20 185648](https://github.com/user-attachments/assets/1159925e-ab48-4ebd-91ae-3bb864a44874)
![Screenshot 2025-06-20 185655](https://github.com/user-attachments/assets/42d363c1-1d9f-4e44-81be-309f5c46a1d4)
![Screenshot 2025-06-20 185701](https://github.com/user-attachments/assets/351b38b7-eeb3-4f60-98f8-b9b79ce54358)


**Future Scope**
* In-app payments integration
* Enhanced real-time tracking of mechanics
* Push notifications with service updates

