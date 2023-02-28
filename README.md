# architecture and Quality Team Roadmap

### 1. Establish coding standards and conventions

Define a set of coding standards and conventions that everyone on the team should follow. This should include things like naming conventions, file structure, code formatting, and documentation guidelines. This will help ensure that the code written by different developers is consistent and easy to understand.

### 2. Develop a shared architecture

Define a shared architecture that can be used across projects. This should include things like how data flows through the application, how communication with the backend is handled, and how data is serialized and deserialized. This shared architecture should be based on the `BlocManager package` and the `flutter-deriv--api package` that we already have.

### 3. Implement a code review process

Develop a code review process that ensures all code is reviewed by another team member before it is merged into the main codebase. This helps catch any inconsistencies or errors in the code and ensures that everyone is following the coding standards and conventions.

### 4. Develop shared libraries

Create shared libraries that includes all the common components and widgets used across projects. This can include things like UI elements, helpers, and Shared packages. This shared library should be maintained by the architecture and quality team, and all developers should use it when building new features.

### 5. Keep Flutter SDK up to date

Make sure to regularly update Flutter SDK to the latest stable version. This will ensure that codebase is up to date with the latest features and improvements. We should also monitor the changelog and breaking changes to make sure that any necessary changes are made to the shared architecture and library.

### 6. Add the code measuring tool to CI/CD pipeline

Add the code measuring tool to CI/CD pipeline so that it runs automatically on every build. This will ensure that we are consistently measuring code quality across all projects. Monitor progress over time to ensure that code quality is improving. Use the data provided by the code measuring tool to identify trends and areas for improvement. Make adjustments to coding standards and conventions as necessary to ensure that they are effective.

### 7. Maintain the codebase

Regularly review and update the shared architecture and shared library to ensure that they are meeting the needs of the projects. Also, monitor the codebase to identify any inconsistencies or areas for improvement, and make changes as necessary.
