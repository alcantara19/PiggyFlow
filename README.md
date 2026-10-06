PiggyFlow

PiggyFlow is an Android-based personal finance application designed to help users track, manage, and organize their daily expenses in a simple and intuitive way.

The application allows users to record their expenses, view their transaction history, and manage their financial records through a clean and user-friendly interface.

Features

* Add new expense records
* View a list of recorded transactions
* Update existing expense records
* Delete expense records
* Store financial data locally on the device
* Display transactions dynamically using RecyclerView
* Simple and user-friendly Material Design interface

Tech Stack

* Language: Java
* IDE: Android Studio
* Architecture: MVVM (Model-View-ViewModel)
* Database: Room Database
* UI: XML, Material Design
* Components: RecyclerView, Fragment, ViewModel, LiveData
* Build System: Gradle

Architecture

PiggyFlow follows the MVVM (Model-View-ViewModel) architecture to separate the application’s UI, business logic, and data management.

User
  ↓
UI / Fragment
  ↓
ViewModel
  ↓
Repository
  ↓
Room Database

This architecture makes the application easier to maintain, test, and extend as new features are added.

Database

PiggyFlow uses Room Database for local data persistence. Expense records are stored directly on the user’s device, allowing the application to access transaction data without requiring an internet connection.

The application supports basic CRUD operations:

* Create — Add a new expense
* Read — View saved expenses
* Update — Edit an existing expense
* Delete — Remove an expense

User Interface

The application uses Android’s Material Design components to provide a clean and consistent user experience. Transaction data is displayed using RecyclerView, allowing the expense list to be updated dynamically as users add, edit, or remove records.

Project Structure

PiggyFlow/
├── app/
│   ├── src/
│   │   └── main/
│   │       ├── java/
│   │       └── res/
│   └── build.gradle
├── gradle/
├── build.gradle
├── settings.gradle
└── README.md

Purpose

This project was developed as an Android application project to practice and implement concepts such as:

* Android application development
* Java programming
* MVVM architecture
* Local database management
* Room Database
* CRUD operations
* RecyclerView
* Fragment-based UI
* Material Design

Future Improvements

Some features that could be added in future versions include:

* Expense categories
* Monthly spending summaries
* Budget management
* Financial statistics and charts
* Search and filtering
* Dark mode
* Cloud synchronization
* User authentication
