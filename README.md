<h1>Firebase Authentication React Project</h1>
This project demonstrates a basic implementation of Firebase authentication in a React application. Users can sign up with their name, email, and password, and then log in using their registered email and password.
<h1>Firebase Authentication React Project</h1>
This project demonstrates a basic implementation of Firebase authentication in a React application. Users can sign up with their name, email, and password, and then log in using their registered email and password.


<h2>Images</h2>
<p align="center">
  <img src="src/components/images/WhatsApp Image 2024-02-20 at 16.12.52_b16f513a.jpg" width="700" >
  <img src="src/components/images/WhatsApp Image 2024-02-20 at 16.13.44_585860fe.jpg" width="700">
  <img src="src/components/images/WhatsApp Image 2024-02-20 at 16.14.19_b091df34.jpg" width="700" >
  <img src="src/components/images/WhatsApp Image 2024-02-20 at 16.19.13_f2095a79.jpg" width="700">
</p>


<h2>Setup Instructions</h2>

Clone the repository:
```
gh repo clone ishpreetkaurkhalsa/firebase-auth
```
Navigate to the project directory:
```
cd firebase-auth
```
Install dependencies:
```
npm install
```
Create a Firebase project in the Firebase console (https://console.firebase.google.com/).
Enable Email/Password authentication in the Firebase console.
Create a .env file in the project root and add your Firebase configuration:
```
REACT_APP_FIREBASE_API_KEY=your_api_key
REACT_APP_FIREBASE_AUTH_DOMAIN=your_auth_domain
REACT_APP_FIREBASE_PROJECT_ID=your_project_id
REACT_APP_FIREBASE_STORAGE_BUCKET=your_storage_bucket
REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
REACT_APP_FIREBASE_APP_ID=your_app_id
  ```
Start the development server:
```
  npm start
  ```
Open http://localhost:3000 in your browser to view the app.


<h2>Features</h2>
<ul>
<li>Sign up with name, email, and password.</li>
<li>Log in with registered email and password.</li>
<li>Firebase authentication handling.</li>
</ul>

<h2>Technologies Used</h2>
<ul>
<li>React</li>
<li>Firebase Authentication</li>
</ul>

