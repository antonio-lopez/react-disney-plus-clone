<h1 align="center">Welcome to Disney+ Clone 👋</h1>
<p>
</p>

> A React Disney+ clone using Firebase and Redux. Firebase is used for handling a user's authentication and movie storage. Redux is used for handling a user and movie state.

### 🏠 [Homepage](https://antonio-disneyplus-clone.netlify.app)

![screenshot](https://raw.githubusercontent.com/antonio-lopez/react-disney-plus-clone/master/uploads/disneyplus-clone-screenshot.png?token=AIWOL57XFTCNR5IDLQQNSN3A7REPS)

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Create a Firebase project and get your project's [unique configuration object](https://firebase.google.com/docs/web/setup). Save the `firebaseConfig` object for later use. The format should be look like this.
  ```
  var firebaseConfig = {
  apiKey: "API_KEY",
  authDomain: "PROJECT_ID.firebaseapp.com",
  databaseURL: "https://PROJECT_ID.firebaseio.com",
  projectId: "PROJECT_ID",
  storageBucket: "PROJECT_ID.appspot.com",
  messagingSenderId: "SENDER_ID",
  appId: "APP_ID",
  measurementId: "G-MEASUREMENT_ID",
  };
  ```
- Create a Firestore Database. Start a new collection and name it `movies`. Add 16 new documents. Each new document should have an `Auto-ID` and have the following fields `[backgroundImg, cardImg, description, subTitle, title, titleImg, type]`, all of type `string`. Fill in the `values` with the values given in the `disneyplusMovies.json` file located in the `src` directory.
- Enable authentication using Google Sign In. Go to your projects `Athentication` tab, select `Sign-in Method`, and `enable` Google.

## Features

- Google sign in / sign out
- Firebase database fetching
- Redux state management

## Install

Clone respository: `https://github.com/antonio-lopez/react-disney-plus-clone.git`

```

cd react-disney-plus-clone/
npm install

```

Create a `.env` file in the root `react-disney-plus-clone` directory and add the following.

```

REACT_APP_FIREBASE_API_KEY=
REACT_APP_FIREBASE_AUTHDOMAIN=
REACT_APP_FIREBASE_PROJECT_ID=
REACT_APP_FIREBASE_STORAGEBUCKET=
REACT_APP_FIREBASE_MSSGINGSENDER_ID=
REACT_APP_FIREBASE_APP_ID=
REACT_APP_FIREBASE_MEASUREMENT_ID=

```

Fill in the values with your Firebase project's config values.

## Usage

```

cd react-disney-plus-clone/
npm start

```

## Author

👤 **Antonio Lopez**

- Website: [Antonio Lopez](https://www.antoniolopez.me/)
- Github: [@antonio-lopez](https://github.com/antonio-lopez)
