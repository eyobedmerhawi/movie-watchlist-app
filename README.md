# Movie Watchlist App

A Flutter movie watchlist application created for CSC 4360 Mobile App Development.

The app displays a collection of movies and allows the user to select a movie to view more information about it.

## Features

- Displays a scrollable list of movies
- Uses local movie poster assets
- Shows the movie title and poster on the home screen
- Allows users to tap a movie to view its details
- Passes Movie objects between screens using Navigator
- Displays the selected movie's:
  - Poster
  - Title
  - Cast
  - Synopsis
- Dark movie-inspired interface
- Scrollable movie details screen

## Movies Included

- The Truman Show
- 1917
- Inception
- The Fault in Our Stars
- The Prince of Egypt

## Project Structure

```text
lib/
├── data/
│   └── movies_data.dart
├── models/
│   └── movie.dart
├── screens/
│   ├── details_screen.dart
│   └── home_screen.dart
└── main.dart

assets/
└── images/
```

## Navigation

The application uses Flutter's `Navigator.push()` and `MaterialPageRoute` to move from the Home Screen to the Details Screen.

The selected `Movie` object is passed to the Details Screen so that the screen can display the correct information without hardcoding a specific movie.

## Assets

Movie posters are stored locally inside:

```text
assets/images/
```

The assets are registered in `pubspec.yaml` and displayed using `Image.asset()`.

## Technologies

- Flutter
- Dart
- Material Design
- Git
- GitHub

## Running the App

Install the project dependencies:

```bash
flutter pub get
```

Run the application:

```bash
flutter run
```

## Author

Eyobed Gebregziabher