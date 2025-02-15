# Calculator App

## Project Overview
A modern, user-friendly calculator app for Android devices, supporting basic arithmetic operations.

## Features
- Addition
- Subtraction
- Multiplication
- Division
- Square Root
- Clear and Error Handling

## Technical Specifications
- Minimum Android Version: 5.0 (Lollipop)
- Target Screen Size: 6.5 inches and larger
- Language: Kotlin
- Architecture: MVVM

## Development Setup
### Cloning the Repository

#### Prerequisites
- Git installed on your system
- Android Studio
- JDK 8 or higher

#### Clone Steps
1. Open Terminal or Command Prompt
2. Navigate to the directory where you want to clone the project
3. Run the following command:

```bash
git clone https://github.com/Bluentray/calculator-app.git
```

#### Alternative: GitHub CLI
If you have GitHub CLI installed:

```bash
gh repo clone Bluentray/calculator-app
```

#### After Cloning
1. Open the project in Android Studio
2. Sync Gradle dependencies
3. Build the project
4. Run on emulator or physical device

## Continuous Integration

[![Android CI](https://github.com/Bluentray/calculator-app/actions/workflows/android_ci.yml/badge.svg)](https://github.com/Bluentray/calculator-app/actions/workflows/android_ci.yml)

Automated builds and tests are run on every push and pull request.

## Google Play Store Submission

### Preparation Checklist
- [x] Implement core functionality
- [x] Add unit and instrumentation tests
- [x] Set up CI/CD
- [x] Create Play Store metadata
- [x] Prepare screenshots
- [x] Create app icon
- [x] Write privacy policy

## App Assets
- [App Icon](app_icon.svg)
- [Screenshots Guidelines](SCREENSHOTS.md)
- [Privacy Policy](PRIVACY_POLICY.md)

### Submission Steps
1. Generate signed APK
2. Create Google Play Developer account
3. Prepare store listing
4. Upload APK
5. Set pricing and distribution

### Release Signing
- Use environment variables for keystore credentials
- Never commit keystore or credentials to repository

### Release Build
- Generate signed release APK:
  ```bash
  ./gradlew assembleRelease
  ```
- APK location: `app/build/outputs/apk/release/app-release.apk`

#### Keystore Management
- **IMPORTANT**: Keep `keystore.properties` and `release-keystore.jks` private
- Do not commit these files to version control
- Store securely and backup separately

## App Store Submission
- Refer to [Submission Checklist](SUBMISSION_CHECKLIST.md) for detailed steps

### Submission Workflow
1. Generate signed release APK
2. Complete store listing
3. Upload APK
4. Set distribution
5. Await approval

## Future Enhancements
- Scientific calculator mode
- History of calculations
- Theme customization


git config --global user.name "Bluentray"
git config --global user.email "karlkindwave@gmail.com"

git remote add origin https://github.com/Bluentray/calculator-app.git
