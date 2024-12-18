## Exercise Scenario

In this exercise, you'll use the **Classroom Workspace **(or your local machine) to set up an NPM project using TypeScript. You'll configure TypeScript, add a build script for a production-ready version, and ensure everything works as expected. By the end, you'll gain familiarity with setting up and running a TypeScript project.

1. **Create an NPM Project**  
   * Initialize a new NPM project in your workspace.  
   * Ensure TypeScript is installed and properly set up.
1. **Configure TypeScript**  
   * Open the `tsconfig.json` file and configure it as needed.

```typescript
{
  "compilerOptions": {
    "target": "es2020",
    "module": "commonjs",
    "outDir": "./build",           /* Redirect output files to the 'build' folder */
    "strict": true,
    "esModuleInterop": true
  },
  "include": ["src/*.ts"],             /* Include all TypeScript files in the root directory */
  "exclude": ["node_modules", "build"]
}

```

1. **Add a Build Script**  
   * Add an NPM script to your `package.json` file to build the production version of your TypeScript project.
1. **Test the TypeScript File**
   * Create the `index.ts` file in a `src` folder. 

```typescript
//index.ts
const myName = "your name";

const hello = (userName: string): string => `hello, ${userName}`;

console.log(hello);  

```

* Run the TypeScript file to ensure it works correctly.
   1. **Build the Project**  

```undefined
npm run build
```

* Execute the build script you added.  
* Analyze the output to verify it meets expectations.

```undefined
node build/.
```

**Note:**    

* The comments in the `tsconfig.json` file are valid for TypeScript configuration, so you don’t need to remove them.  

By completing this exercise, you'll understand the steps to configure and run a TypeScript project in an NPM environment!