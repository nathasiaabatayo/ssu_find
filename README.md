# SSU Find - Flutter Web App

A Flutter web application for finding and managing items at SSU (Samar State University).

## Features

- User authentication with Firebase
- Item management and search
- Image upload and storage
- Real-time database with Firestore
- Responsive web design

## Deployment

This app is automatically deployed to GitHub Pages using GitHub Actions.

### Live Demo
Visit: https://nathasiaabatayo.github.io/ssu_find/

### Manual Deployment Steps

If you need to deploy manually:

1. **Build the web app:**
   ```bash
   flutter build web --release
   ```

2. **Enable GitHub Pages:**
   - Go to your repository settings
   - Navigate to "Pages" section
   - Select "Deploy from a branch"
   - Choose "gh-pages" branch
   - Save the settings

3. **The app will be available at:**
   `https://[your-username].github.io/ssu_find/`

## Development

### Prerequisites
- Flutter SDK (3.24.0 or higher)
- Dart SDK
- Firebase project setup

### Setup
1. Clone the repository
2. Run `flutter pub get`
3. Configure Firebase credentials
4. Run `flutter run -d chrome` for development

## Technologies Used

- Flutter Web
- Firebase (Auth, Firestore, Storage)
- GitHub Actions for CI/CD
- GitHub Pages for hosting
