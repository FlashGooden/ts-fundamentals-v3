**Typescript Notes**

  **tsconfig.json**

    - `Include Key`: Selects which file to compile ("include": ["src"] - will compile all the typescript files inside the `src` folder)
    - `compilerOptions` Key: Has options for specific things the compiler should do
      - `outDir`: Where to put the TS files ("outDir": "dist" - Places files in dist folder after compiling)
      - `target`: helps describe the language level of build output ("target": "ES3" - will support javascript built for IE6)
    - You can run the options that would be located in the Tsconfig file by passing a flag to the tsc script command (tsc --outDir dist && tsc --target es3)
