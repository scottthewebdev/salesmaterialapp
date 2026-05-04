# salesmaterialapp
Sales is an Angular-based frontend for a sales/e-commerce application. It provides product browsing and management (list, grid, add/edit dialogs), filtering, shopping cart and checkout flows, theming, and image handling. The app is intended as a frontend for a backend API and includes development tooling and automated tests.

Tech Stack

- Angular 20.2.2
- TypeScript
- SCSS (Sass)
- Angular CLI
- Node.js & npm
- Karma + Jasmine for unit tests

Services

- `product-service.ts`: Fetches and manages product data from the backend API (list, detail, search).
- `cart-service.ts`: Manages shopping cart state, add/remove items, and cart calculations.
- `image-service.ts`: Handles image uploads, retrieval, and transformations for product images.
- `filter-service.ts`: Provides product filtering and search helpers used across components.
- `storage-service.ts`: Abstracts local/session storage usage for persisting user state.
- `theme-service.ts`: Manages application theming and exposes theme change utilities.

Stores

- `product.store.ts`: Client-side store for product collections, caching, and reactive updates.
- `image.store.ts`: Store for image metadata and in-memory image state used by UI components.

This project was generated using [Angular CLI](https://github.com/angular/angular-cli) version 20.2.2.

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
