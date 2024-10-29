# Useful Commands for Expo Development

## Setup Commands
- **`npm install -g expo-cli`**: Installs the Expo CLI globally on your system, allowing you to create and manage Expo projects.

- **`expo init MyReactApp`**: Initializes a new Expo project named `MyReactApp` with the necessary directory structure and configuration files.

- **`expo start`**: Starts the Expo development server, enabling you to run your app in the Expo Go app or on an emulator.

## Dependency Installation
- **`npm install expo --save`**: Installs the core Expo package as a dependency in your project, ensuring you have access to Expo's APIs and components.

- **`npm install metro-config --save`**: Installs Metro configuration as a dependency, useful for customizing the Metro bundler's behavior in your project.

- **`npm install -g expo-cli@6.0.8`**: Installs a specific version (6.0.8) of the Expo CLI globally, which may be necessary for compatibility with certain projects.

## User Authentication
- **`expo login`**: Logs you into your Expo account from the command line, allowing you to access your projects and use Expo's services.

## EAS CLI Commands
- **`npm install -g eas-cli`**: Installs the Expo Application Services (EAS) CLI globally, enabling you to build and deploy your Expo apps.

- **`eas build:configure`**: Configures your project for EAS Build, setting up necessary files and settings for building your app.

## PowerShell Configuration
- **`Set-ExecutionPolicy RemoteSigned -Scope CurrentUser`**: Changes the PowerShell execution policy to allow running scripts, which may be necessary for executing the EAS CLI commands.

## Build Commands
- **`eas build -p android`**: Initiates the build process for an Android application, producing an APK or AAB file for distribution or testing.

- **`eas build -p android --profile preview`**: Builds an Android application using the `preview` profile, typically configured to generate an APK for direct installation and testing.
