# DocDoc: Your Comprehensive Medical Companion

DocDoc is a cross-platform mobile application built using Flutter, designed to serve as your ultimate medical companion. Whether you're seeking medical advice, scheduling appointments, or managing your health records, DocDoc has got you covered. This README file highlights the key features and technologies utilized in building this application.

![DOCDOC APPLICATION](https://github.com/ahmedabdelrahmanalghwalbi/docdoc/assets/64208176/fcfabe89-67df-4649-b93c-100891318aab)


![docdoc android 11 , 12 , ios](https://github.com/ahmedabdelrahmanalghwalbi/docdoc/assets/64208176/5f1ec5b7-f5d9-453c-8f4e-f7392d2b6471)



## Key Features

1. **Firebase Integration**: DocDoc seamlessly integrates with Firebase for authentication, real-time database management, and cloud storage. Firebase provides a robust backend infrastructure, ensuring secure and scalable services for user authentication and data storage.

2. **Firebase Distribution**: Firebase Distribution is utilized for distributing beta builds of the application to testers and stakeholders. With Firebase Distribution, you can easily distribute pre-release versions of DocDoc to your team for testing and feedback.

3. **GitHub Actions and Fastlane Integration**: DocDoc leverages GitHub Actions and Fastlane for streamlined CI/CD processes. GitHub Actions automate the build and deployment workflows, while Fastlane simplifies the release management process by handling tasks such as code signing, app store submission, and release notes generation.

4. **Flavors Usage**: DocDoc utilizes flavors to manage different configurations for development, staging, and production environments. Flavors allow you to build and deploy multiple versions of the application with customized settings, such as API endpoints, app icons, and branding.

## Powerful Usage of CI/CD Concepts

DocDoc employs a robust CI/CD pipeline, integrating with multiple providers to automate the software delivery process. Here's how each component contributes to the CI/CD workflow:

- **GitHub Actions**: GitHub Actions automate the CI/CD workflow by triggering builds, running tests, and deploying the application based on predefined workflows defined in the repository. This ensures continuous integration and delivery of updates to the application.

- **Fastlane**: Fastlane streamlines the release management process by automating tasks such as code signing, app store submission, and release notes generation. It provides a unified interface for managing the deployment of DocDoc to app stores and distribution platforms.

## Packages Used

DocDoc utilizes a variety of packages to enhance development efficiency and functionality. Here's a brief overview of the packages used:

- **build_runner**: A build system for Dart code generation and modular compilation, used for generating code and optimizing build processes.

- **flutter_bloc**: A state management library that helps manage the state of the application using the BLoC (Business Logic Component) pattern.

- **freezed** and **freezed_annotation**: Code generation libraries used for generating immutable classes and serialization/deserialization code.

- **get_it**: A dependency injection library used for managing dependencies and service locators in the application.

- **json_serializable** and **json_annotation**: Libraries used for automatically generating code for converting Dart classes to and from JSON.

- **dio** and **retrofit**: Networking libraries used for making HTTP requests and handling API communication.

- **pretty_dio_logger**: A Dio interceptor for logging HTTP requests and responses in a human-readable format.

- **intl** and **easy_localization**: Libraries used for internationalization and localization of the application.

- **flutter_native_splash**: A library used for generating and customizing native splash screens for Flutter applications.

- **flutter_svg**: An SVG rendering and widget library used for displaying SVG images in the application.

- **flutter_screenutil**: A library used for adapting screen and font sizes for different devices and resolutions.

## Getting Started

To get started with DocDoc, follow these steps:

1. Clone the repository to your local machine.
2. Install Flutter SDK and set up your development environment.
3. Set up Firebase project and configure authentication, database, and distribution services.
4. Configure GitHub Actions and Fastlane for CI/CD automation.
5. Customize flavor configurations for different environments.
6. Run the application on an emulator or physical device to explore its features.

For detailed instructions on setting up the development environment and running the application, refer to the documentation included in the repository.

## Contributing

We welcome contributions from the community to enhance DocDoc further. If you have any suggestions, bug fixes, or new features to propose, please feel free to submit a pull request or open an issue on GitHub.
