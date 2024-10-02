<p align="center"><a href="https://github.com/MicheleAbategiovanni" target="_blank"><img src="logo.png" width="150" alt="Michele Abategiovanni Logo"></a></p>

# Flutter App Base

This repository contains the base structure for a Flutter app. It includes a CI/CD workflow that automates testing and building for both Android and iOS platforms.

## Features

- **Automated Testing**: Runs Flutter tests to ensure the app behaves as expected.
- **Build & Release**: If all tests pass, the workflow proceeds to build and release the app for both Android and iOS platforms.

## Workflow Overview

<img src="https://github.com/MicheleAbategiovanni/flutter_github_actions/actions/workflows/ci.yml/badge.svg">

The repository is equipped with a CI/CD pipeline that consists of two main stages:

1. **Testing Stage**
    - Runs `flutter test` on the application.
    - Ensures that all the app's tests pass successfully before proceeding to the next stage.

2. **Build & Release Stage**
    - Builds the Flutter app for Android and iOS.
    - Creates the release artifacts for both platforms (APK for Android and IPA for iOS).
    - This stage is triggered only if all tests in the first stage pass.

