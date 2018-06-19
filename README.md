### Fitness Tracker
- User sign/signup.
- Choose from a list of exercises.
- Start/Stop/Continue exercise.
- View Past exercises.

### Setup
- Open terminal and clone the repositoy
```cmd
git clone https://github.com/kedarnadkarny/fitness-tracker.git
```

- Navigate inside the directory and install dependencies
```cmd
cd fitness-tracker
npm install
```

- Create a project in firebase and copy your firestore url in src/environments/environment.ts
```
export const environment = {
  production: false,
  firebase: {
    apiKey: "firebase-key",
    authDomain: "firebase-domain",
    databaseURL: "firebase-db-url",
    projectId: "project-id",
    storageBucket: "bucket",
    messagingSenderId: "message-id"
    }
};
```


- Run the application
```cmd
ng serve
```

### This projects implements-
- Materialize CSS
- RXJS Store
- Firestore and Authentication

### Project Images

| ![burger1](https://github.com/kedarnadkarny/burger-builder/blob/master/src/assets/images/burger1.png) | ![burger1](https://github.com/kedarnadkarny/burger-builder/blob/master/src/assets/images/burger1.png) | ![burger1](https://github.com/kedarnadkarny/burger-builder/blob/master/src/assets/images/burger1.png) |