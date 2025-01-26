# ERP - Full Stack Project

## Introduction
This is a full-stack ERP implementation using the Angular framework with SASS and TypeScript. It utilizes Google Cloud Platform (GCP) services such as FireAuth, CloudSQL, and Cloud Run Functions for the backend. Testing is performed with Karma and Puppeteer, using Jasmine as the test runner on Edge. The frontend design follows [Material Design 3](https://m3.material.io/) principles to ensure a consistent and modern look and feel.

## Prerequisites
- Node.js
- Angular CLI
- Google Cloud SDK

## Project Setup

### Cloning the Repository
Clone the repository using the following command:
```bash
git clone https://github.com/Technovators-Society/ERP.git
```

### Install Dependencies
Navigate to the project directory and install the necessary dependencies:
```bash
cd ERP
npm install
```

## Development Server
Start the local development server:
```bash
ng serve
```
Open your browser and go to `http://localhost:4200/`. The application will automatically reload whenever you make changes to the source files.

## Code Scaffolding
Angular CLI includes powerful code scaffolding tools. To generate a new component, run:
```bash
ng generate component component-name
```
For a complete list of available schematics such as `components`, `directives`, or `pipes`, run:
```bash
ng generate --help
```

## Building the Project
To build the project, run:
```bash
ng build
```
This will compile your project and store the build artifacts in the `dist/` directory. The production build optimizes your application for performance and speed.

## Running Tests

### Unit Tests
To execute unit tests with Karma, use the following command:
```bash
ng test
```

### End-to-End Tests
For end-to-end (e2e) testing, run:
```bash
ng e2e
```

## Additional Resources
For more information on using the Angular CLI, including detailed command references, visit the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli/) page.

## Contributors
- **Technovators** - [Technovators GitHub](https://github.com/Technovators-Society)

## License
This project is licensed under the Apache-2.0 License - see the [LICENSE](https://github.com/Technovators-Society/ERP/blob/main/LICENSE) file for details.
