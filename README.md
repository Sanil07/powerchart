<h1>PowerChart</h1>

<p>
  PowerChart is a Flutter-based chat application that allows users to authenticate using Gmail and manage real-time conversations via Firebase. The application leverages Firebase for authentication, database storage, and real-time communication features, providing a seamless and secure chat experience.
</p>

<h2>Features</h2>
<ul>
  <li><strong>Gmail Authentication</strong>: Secure and easy user login through Gmail, powered by Firebase Authentication.</li>
  <li><strong>Real-Time Chat</strong>: Send and receive messages instantly using Firebase Realtime Database or Firestore.</li>
  <li><strong>Firebase Integration</strong>: Firebase is used for handling backend operations such as authentication, data storage, and real-time messaging.</li>
  <li><strong>Cross-Platform Support</strong>: Works on both Android and iOS platforms with a unified Flutter codebase.</li>
</ul>

<h2>Prerequisites</h2>
<ul>
  <li><strong>Flutter SDK</strong>: Install Flutter from the official <a href="https://flutter.dev">Flutter website</a>.</li>
  <li><strong>Firebase Account</strong>: Create a Firebase project in the <a href="https://console.firebase.google.com/">Firebase Console</a>.</li>
  <li><strong>Google Cloud API</strong>: Enable the Google Sign-In API for Gmail authentication.</li>
</ul>

<h2>Setup and Installation</h2>
<ol>
  <li>Clone the repository:
    <pre><code>git clone https://github.com/Sanil07/powerchart.git
cd powerchart</code></pre>
  </li>
  <li>Install dependencies:
    <pre><code>flutter pub get</code></pre>
  </li>
  <li>Set up Firebase:
    <ul>
      <li>Create a Firebase project in the Firebase Console.</li>
      <li>Add your Android/iOS app to Firebase and download the <code>google-services.json</code> (for Android) or <code>GoogleService-Info.plist</code> (for iOS).</li>
      <li>Place the configuration file in the appropriate directory in your Flutter project (for Android, in <code>android/app</code>; for iOS, in <code>ios/Runner</code>).</li>
      <li>Enable Firebase Authentication and configure Gmail login under the Authentication section.</li>
    </ul>
  </li>
  <li>Run the app:
    <pre><code>flutter run</code></pre>
  </li>
</ol>

<h2>Usage</h2>
<p>
  After logging in with a Gmail account, users can start chatting in real-time. The chat messages are stored and managed using Firebase's database services, ensuring that messages are delivered instantly.
</p>

<h2>Contributing</h2>
<p>
  Contributions are welcome! Feel free to fork the repository, create a new branch, and submit a pull request.
</p>

<h2>License</h2>
<p>
  This project is licensed under the MIT License. See the <a href="LICENSE">LICENSE</a> file for details.
</p>
