# HorizonFx

This project was generated using [Angular CLI](https://github.com/angular/angular-cli) version 20.3.0.

## Development server

To start a local development server, run:

```bash
ng serve
```

Once the server is running, open your browser and navigate to `http://localhost:4200/`. The application will automatically reload whenever you modify any of the source files.

## Code scaffolding

Angular CLI includes powerful code scaffolding tools. To generate a new component, run:

```bash
ng generate component component-name
```

For a complete list of available schematics (such as `components`, `directives`, or `pipes`), run:

```bash
ng generate --help
```

## Building

To build the project run:

```bash
ng build
```

This will compile your project and store the build artifacts in the `dist/` directory. By default, the production build optimizes your application for performance and speed.

## Running unit tests

To execute unit tests with the [Karma](https://karma-runner.github.io) test runner, use the following command:

```bash
ng test
```

## Running end-to-end tests

For end-to-end (e2e) testing, run:

```bash
ng e2e
```

Angular CLI does not come with an end-to-end testing framework by default. You can choose one that suits your needs.

## Additional Resources

For more information on using the Angular CLI, including detailed command references, visit the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.

NgRx Packages (State Management)

@ngrx/store - Central state management store (Redux pattern for Angular)
@ngrx/effects - Handle side effects like API calls and async operations
@ngrx/entity - Manage collections of data efficiently (currency pairs, prices)
@ngrx/store-devtools - Browser debugging tools for NgRx state
@ngrx/router-store - Sync Angular router with NgRx store

Core Dependencies

rxjs - Reactive programming library (observables for real-time forex data)
date-fns - Date manipulation library (format timestamps, time zones)
chart.js - Charting library for price graphs and technical indicators
ng2-charts - Angular wrapper for Chart.js integration

Development Tools

@types/chart.js - TypeScript type definitions for Chart.js
cypress - End-to-end testing framework
prettier - Code formatter (automatic code styling)
husky - Git hooks (runs checks before commits)
lint-staged - Run linting only on staged files (performance optimization)
eslint-plugin-rxjs - ESLint rules for RxJS best practices

How They Work Together for HorizonFX
// NgRx manages forex data state
// RxJS handles real-time price streams  
// Chart.js displays price charts
// Date-fns formats timestamps
// Development tools ensure code qualityWhat Each Testing Tool Does
Karma + Jasmine (Unit Testing)

✅ Unit tests - Test individual components/services
✅ Integration tests - Test component interactions
✅ Already configured in Angular projects
✅ Fast execution for TDD workflow
✅ Your existing knowledge

Cypress (E2E Testing)

✅ End-to-end tests - Test complete user workflows
✅ Real browser testing - Test actual user interactions
✅ Visual debugging - See tests run in browser
✅ API testing - Test backend integrations

Testing Strategy for HorizonFX
Week 1-8: Unit Tests (Karma + Jasmine)

Test services (ForexDataService, ApiService)
Test components (price displays, charts)
Test NgRx stores and effects
Test utilities and pipes

Week 9-12: E2E Tests (Optional Cypress)

Test complete user workflows
Test real-time data updates
Test responsive design
Test accessibility features
