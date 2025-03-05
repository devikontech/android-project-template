## Multi-Module Kotlin Android Project Template

This template is designed to simplify and accelerate Android development by providing a well-structured, multi-module Kotlin project. It includes all necessary configurations to ensure a smooth development experience.

## Key Features:
Modular Architecture: The project is divided into multiple modules (e.g., app, core, data, domain, feature) to promote separation of concerns and reusability.

Kotlin-First: Built entirely in Kotlin, leveraging its modern features and concise syntax.

Gradle Configuration: Pre-configured Gradle files for dependency management, build types, and flavors.

Testing Setup: Includes unit tests, instrumentation tests, and test utilities for each module.

CI/CD Ready: Pre-configured for continuous integration and deployment (e.g., GitHub Actions, GitLab CI).

Third-Party Libraries: Common libraries like Retrofit, Hilt, Coroutines, and Jetpack components are pre-integrated.

Code Quality Tools: Includes tools like Detekt, Ktlint, and Spotless for maintaining code quality.

Scalable and Maintainable: Designed to scale with your app and team size.

## Project Structure
```
project-root/
├── app/                  # Main application module
├── core/                 # Shared utilities, extensions, and base classes
├── data/                 # Data layer (repositories, APIs, databases)
├── domain/               # Business logic and use cases
├── feature/              # Feature-specific modules (e.g., login, profile)
├── build.gradle.kts      # Root build configuration
├── settings.gradle.kts   # Module inclusion and project settings
├── gradle/               # Gradle wrapper and properties
└── README.md             # Project documentation
```

