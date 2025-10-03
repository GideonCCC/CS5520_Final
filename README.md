PeePal 🚻

A location-based iOS app prototype for finding and rating public restrooms

📌 Overview

PeePal is a Swift-based iOS app developed as a semester project. It enables users to search for restrooms nearby, add new entries, leave ratings, and report issues, creating a crowd-sourced restroom finder. The app integrates Firebase Firestore for data persistence and Firebase Authentication for secure user accounts.

✨ Features

🔑 User Authentication – Register/Login with Firebase Authentication

🗺 Map Integration – View and locate restrooms using MapKit

➕ Add Restrooms – Submit new restrooms with name, address, type (public/accessible/etc.), and hours

⭐ Ratings & Reviews – Rate restrooms and view average ratings in real-time

🚨 Reporting System – Flag problematic restrooms, with warnings shown to other users

👤 Profile Section – Manage “My Ratings,” “My Added Toilets,” and “My Reports”

🎨 Modern UI/UX – Programmatic UIKit layout with Figma-inspired design

🛠 Tech Stack

Language: Swift (UIKit)

Backend: Firebase Firestore (real-time NoSQL DB)

Auth: Firebase Authentication

Map & Location: MapKit, CoreLocation

UI: UIKit, Auto Layout, custom Views

Design: Figma (prototyping)

📂 Project Structure
├── Controllers/         # ViewControllers for login, signup, add, ratings, reports  
├── Views/               # Custom UI components (LoginScreenView, ToiletDetailView, etc.)  
├── Models/              # Toilet, ReportedToilet, User models  
├── Utils/               # Icon utils, helpers  
└── Resources/           # Assets, storyboards (if any)

🚀 Getting Started
Prerequisites

Xcode 15+

iOS 16.0+ simulator or device

Firebase project (Firestore + Authentication enabled)

Setup

Clone the repo

git clone https://github.com/<your-username>/pee-pal-ios.git
cd pee-pal-ios


Install dependencies (via Swift Package Manager if needed).

Add your GoogleService-Info.plist (from Firebase console) to the project.

Build and run in Xcode.
