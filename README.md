<!DOCTYPE html>
<html>
<body>
  <h1>Pet Adoption App</h1>

  <h2>Project Description</h2>
  <p>This Android application enables users to browse and adopt pets conveniently. Utilizing Firebase as a backend, the app manages data on pets, including their photos, descriptions, and the adoption features</p>
  
  <h2>Features and Functionality</h2>
  <ul>
    <li><strong>User Authentication:</strong> Secure login options via email/password and Google Sign-In, ensuring user convenience and security.</li>
    <li><strong>Dynamic Pet Listings:</strong> Users can explore various pet categories through a responsive interface that fetches data dynamically from Firebase Firestore and external APIs.</li>
    <li><strong>Search and Favorites Management:</strong> Features include a robust search bar that filters pets by name and a system to manage favorite pets, enhancing user experience.</li>
    <li><strong>Adopt Me Feature:</strong> Users can initiate the adoption of pets directly from the PetDetailsActivity by clicking the "Adopt Me" button.</li>
    <li><strong>Add a Pet:</strong> Users contribute to the pet listings by adding new pet information, which is stored in the 'addedpets' collection in Firebase Firestore.</li>
  </ul>
  
  <h2>Installation</h2>
  <p>Follow these steps to install and run the Pet Adoption App on your Android device:</p>
  <ol>
    <li>Ensure your device or emulator is set up with Android OS that supports the app.</li>
    <li>Clone or download the project files from this repository to your local machine.</li>
    <li>Open the project in Android Studio.</li>
     <li>Build and run the application on your device or emulator.</li>
  </ol>
  
  <h2>Usage</h2>
  <p>Here’s how to navigate and use the Pet Adoption App:</p>
  <ol>
    <li>Log in or sign up from the Main Activity.</li>
    <li>Navigate through the WelcomeActivity where you can select different pet categories such as Dogs, Cats, etc.</li>
    <li>Choose a pet to view more details and proceed with the adoption using the "Adopt Me" button if interested.</li>
    <li>Use the search bar to filter pets by specific criteria or add pets to your favorites for easy access.</li>
    <li>To add a new pet, navigate to the AddedPetListActivity and use the 'Add Pet' button.</li>
  </ol>

  <h2>Technologies Used</h2>
  <ul>
    <li>Android Studio for development.</li>
      <li>Kotlin programming language</li>
    <li>Firebase Firestore for real-time database functionalities.</li>
    <li>Firebase Authentication for managing user access and security.</li>
    <li>External APIs for additional pet data integration.</li>
    <li>RecyclerView for displaying lists of data efficiently.</li>
  </ul>
  
  <h2>Resources</h2>
  <p>Additional documentation and resources to help you:</p>
  <ul>
    <li><a href="https://firebase.google.com/docs">Firebase Documentation</a></li>
    <li><a href="https://developer.android.com/docs">Android Developer Documentation</a></li>
      <li><a href="(https://api.petfinder.com/v2/">Petfinder API Documentation</a></li>
  </ul>
</body>
</html>
