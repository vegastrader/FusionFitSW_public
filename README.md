
The project revolves around an app running on [Angular][angular] + [Angular Material][angular-material] + [FlexLayout][flexlayout] with a minimal clean interface to fit both desktop and mobile. Icon set comes from both [Material][material] and [FontAwesome][fontawesome]. Including [Hammerjs][hammerjs] to handle gestures for material components. Using [Moment][momentjs] for time and locale management.

## Firebase

The app relies on several [firebase services][firebase]:

* Firebase Hosting
* Firebase Auth for user authentication 
* Cloud Firestore realtime database for user's profile and content
* Cloud Storage for user's images and files
* Cloud Functions to run key tasks server-side

## Internationalization

The project uses a content resolver to dynamically load contents in different languages by pre-fetching localilzed content from 'assets/i18n'.


[angular]: https://angular.io
[material]: https://material.io
[angular-material]: https://material.angular.io
[flexlayout]: https://github.com/angular/flex-layout/wiki
[firebase]: https://firebase.google.com
[fontawesome]: https://fontawesome.com
[hammerjs]: https://hammerjs.github.io
[momentjs]: https://momentjs.com
