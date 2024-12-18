**Exercise Scenario**

In this exercise, you will convert an existing JavaScript project into TypeScript, focusing on explicit typing for all mutable variables, function parameters, and return types. The goal is to ensure type safety throughout the application while maintaining its functionality. Once converted, you will build and run the application to verify that it works correctly.

---

## **Instructions**

1. **Convert the Project to TypeScript**  
   - Update the project by converting all JavaScript files to TypeScript files.  
   - Use explicit typing for:  
     - All mutable variables.  
     - Function parameters.  
     - Function return types.

2. **Review the `package.json` File**  
   - Open the `package.json` file to identify the available build script.  

3. **Build the Project**  
   - Use the build script to compile the TypeScript code.  
   - Address any errors reported during the build process.  

4. **Run the Application**  
   - Execute the built application to verify that it works as intended.  
   - The application should prompt the user to:  
     - Create a coffee beverage.  
     - Add quantities of ingredients.  

---

**Note:**  
- A **"Renderer Failure: tsconfig.json"** popup may appear when starting the project.  
  - This error is caused by comments in the `tsconfig.json` file, which are not valid JSON.  
  - These comments are safe to ignore and do not affect the TypeScript configuration.  

By completing this exercise, you will have successfully migrated the project to TypeScript, improving its type safety and maintainability!  