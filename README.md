# Architecture and Quality Team Roadmap

## Overview

| # | Goal | Priority | Status | Why | How |
| --- | --- | --- | --- | --- | --- |
| 1 | Establish coding standards and conventions | High | In Progress | Ensure code consistency and readability | Review existing codebase and document the agreed-upon standards |
| 2 | Develop a shared architecture | Medium | Not Started | Ensure consistency and scalability | Use `BlocManager` and `flutter-deriv-api` as a basis for the architecture |
| 3 | Implement a code review process | Medium | Not Started | Catch errors and ensure compliance with coding standards | Assign reviewers and establish review guidelines |
| 4 | Develop shared packages | High | In Progress | Promote code reuse and consistency | Maintain packages and encourage their use |
| 5 | Keep Flutter SDK up to date | High | In Progress | Ensure access to new features and improvements | Monitor changelog and breaking changes and make necessary updates to the architecture and packages |
| 6 | Add the code measuring tool to CI/CD pipeline | Low | Not Started | Ensure consistent measurement of code quality | Select a code measuring tool and integrate it into the pipeline |
| 7 | Maintain the codebase | Medium | Not Started | Ensure code quality and relevance | Monitor usage of packages and make updates as necessary |

## Definitions

### 1. Establish coding standards and conventions

Define a set of coding standards and conventions that everyone on the team should follow. This should include things like naming conventions, file structure, code formatting, and documentation guidelines. This will help ensure that the code written by different developers is consistent and easy to understand.

### 2. Develop a shared architecture

Define a shared architecture that can be used across projects. This should include things like how data flows through the application, how communication with the backend is handled, and how data is serialized and deserialized. This shared architecture should be based on the `BlocManager` package and the `flutter-deriv-api` package that we already have.

### 3. Implement a code review process

Develop a code review process that ensures all code is reviewed by another team member before it is merged into the main codebase. This helps catch any inconsistencies or errors in the code and ensures that everyone is following the coding standards and conventions.

### 4. Develop shared packages

Create shared packages that include all the common components and widgets used across projects. This can include things like UI elements, helpers, and Shared packages. These shared packages should be maintained by the architecture and quality team, and all developers should use them when building new features.

### 5. Keep Flutter SDK up to date

Make sure to regularly update Flutter SDK to the latest stable version. This will ensure that the codebase is up to date with the latest features and improvements. We should also monitor the changelog and breaking changes to make sure that any necessary changes are made to the shared architecture and packages.

### 6. Add the code measuring tool to CI/CD pipeline

Add the code measuring tool to CI/CD pipeline so that it runs automatically on every build. This will ensure that we are consistently measuring code quality across all projects. Monitor progress over time to ensure that code quality is improving. Use the data provided by the code measuring tool to identify trends and areas for improvement. Make adjustments to coding standards and conventions as necessary to ensure that they are effective.

### 7. Maintain the codebase

Regularly review and update the shared architecture and shared packages to ensure that they are meeting the needs of the projects. Also, monitor the codebase to identify any inconsistencies or areas for improvement, and make changes as necessary.
