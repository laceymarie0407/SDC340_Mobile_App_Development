Aura – Personalized Beauty Profile & Inventory App

Build Your Look. Define Your Style.

Aura is an Android mobile application developed in Kotlin using Android Studio.
The app allows users to create a personalized beauty profile, manage product inventory, and simulate compatibility scoring based on personal traits.

This project demonstrates mobile UI design, multi-activity navigation, structured data handling, and scalable architecture planning.

Features:

**Beauty Profile System**
Hair color, texture, and length selection
Skin tone and skin texture selection
Eye color and face shape selection
Profile photo upload
Editable profile with saved selections

**Inventory Management**
Seeded sample beauty products
Product detail screen
Match percentage scoring
Add-to-inventory confirmation
Searchable inventory list

**Scan Product (Prototype)**
Simulated scanning screen
Designed for future barcode/AI integration

**Navigation & Architecture**
Multi-activity Android structure
Intent-based navigation
Centralized state management using:
ProfileStore
InventoryStore
Toast feedback for user actions

**Technical Stack**
Kotlin
Android Studio
XML Layout Design
Intent Navigation
Spinner Dropdowns
Image Picker (Activity Result API)
Custom Launcher Icon
Gradient UI Styling

**Architecture Overview**
Aura uses a multi-activity architecture:
LoginActivity
HomeActivity
ScanActivity
InventoryActivity
ProductDetailActivity
ProfileActivity
ProfileSetupActivity
User profile and inventory data are stored in centralized in-memory data models (ProfileStore and InventoryStore) to simulate persistent data handling.

**Future Development Plans**
Aura is designed with scalability in mind. Future improvements include:
Room database integration for persistent storage
Firebase cloud synchronization
AI-powered product compatibility engine
Expanded profile personalization metrics
Social sharing & product tagging features
Community review integration

**Target Audience**
Aura is designed for individuals of all ages and genders interested in:
Personal care
Beauty and grooming
Product organization
Personalized recommendations
Structured self-care routines
The app emphasizes inclusivity and adaptability across diverse skin tones, hair types, and personal styles.

**How to Run**
Clone the repository.
Open the project in Android Studio.
Allow Gradle to sync.
Build and run the application on an emulator or Android device.

**Developer**
Lacey Roof
Android Mobile Application Project

**Project Status**
This project was developed as part of an Android Mobile Application course and serves as portfolio material demonstrating mobile design, development, and scalability planning.
