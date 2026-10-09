# Authenticated Notes

A Flutter notes app with Firebase authentication. It includes login, registration, and forgot-password screens (~11KB) plus a Firestore service layer for storing and retrieving notes per user. The auth flow overlaps heavily with the `login_app` repo — this one adds the notes CRUD layer on top.

**Tech stack:** Flutter / Dart, Firebase (Auth + Firestore)

**How to run:**
```
flutter pub get
flutter run
```
Note: you need a `google-services.json` (Android) / Firebase config with your own project settings before auth will work.

**Status:** Auth-tutorial build extended with notes functionality; functional but unfinished.
