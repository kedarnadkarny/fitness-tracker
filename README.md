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

![fitness1](https://github.com/kedarnadkarny/fitness-tracker/tree/master/src/assets/images/fitness1.png)

![fitness2](https://github.com/kedarnadkarny/fitness-tracker/tree/master/src/assets/images/fitness2.png)

![fitness3](https://github.com/kedarnadkarny/fitness-tracker/tree/master/src/assets/images/fitness3.png)

![fitness4](https://github.com/kedarnadkarny/fitness-tracker/tree/master/src/assets/images/fitness4.png)

![fitness5](https://github.com/kedarnadkarny/fitness-tracker/tree/master/src/assets/images/fitness5.png)

![fitness6](https://github.com/kedarnadkarny/fitness-tracker/tree/master/src/assets/images/fitness6.png)

![fitness7](https://github.com/kedarnadkarny/fitness-tracker/tree/master/src/assets/images/fitness7.png)

![fitness8](https://github.com/kedarnadkarny/fitness-tracker/tree/master/src/assets/images/fitness8.png)