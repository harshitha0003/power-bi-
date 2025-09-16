# Installing @Types for d3

NOTE: The Typings npm library is deprecated. You must use @types instead.

To use any external JavaScript libraries, the typescript compiler needs typings. The @types nom packages cover a wide variety of Javascript libraries. Installing @types for d3 will give you access to d3 types so you can utilize it in typescript.
See [commit](https://github.com/Microsoft/PowerBI-visuals-sampleBarChart/commit/2bb0f64718864a27e7d4b9c5b1d35d267bba6202) for what was added at this step.

For more in depth details about @types, visit the package page on npm. [@types Documentation](https://www.npmjs.com/~types)

## Add Typings to your Project
To install types for d3 at version 3.5 (the most recent version supported by pbiviz) as a dev dependency, run the following command.

```
// install d3 typings 
npm install @types/d3@3.5 --save-dev
```

You should now have an @types directory in your node modules.