## Exercise Scenario

In this exercise, you will convert an existing JavaScript project into TypeScript. This involves updating file extensions, adding type annotations, and addressing TypeScript errors during the build process. By completing this, you’ll gain hands-on experience transitioning JavaScript projects to fully-typed TypeScript projects.

### 1. Review the Project Setup

* Modify the `index.ts` file using the following starter code. Note that this code has not yet been converted to TypeScript:

* There are three JavaScript files in the `src/utilities` folder.
- **`strings.js`**
- **`numbers.js`**
- **`arrays.js`**

* Review the `package.json` file to understand the available scripts for running the project.

### 2. Convert the File Extensions

* Change the file extensions of the `.js` files in the `src/utilities` folder to `.ts`.

### 3. Update Modules

* Convert all CommonJS modules (`require` and `module.exports`) to ES6 modules (`import` and `export`).

### 4. Build the Project

* Run the build script to identify TypeScript errors.
* Address any errors reported by TypeScript.

### 5. Add Explicit Types

* Add explicit type annotations to all functions in the project.
* Use TypeScript types and interfaces where appropriate.

### 6. Fix Additional Issues

* Resolve any remaining issues detected during the build process to ensure the project compiles without errors.

**Note**

* A **"Renderer Failure: tsconfig.json"** popup may appear when starting this project. This occurs because comments in `tsconfig.json` are not valid JSON. However, these comments are safe to use and do not affect functionality. You can safely ignore this error.

By the end of this exercise, your project will be fully converted to TypeScript, benefiting from type safety and improved maintainability!