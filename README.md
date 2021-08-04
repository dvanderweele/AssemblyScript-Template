# AssemblyScript Template

This replit is a good starting point for AssemblyScript development, and it includes the `as-pect` testing library for easily testing your AssemblyScript in a manner that is reminiscent of Jest. 

## What is AssemblyScript?

AssemblyScript is a language syntactically inspired by TypeScript which compiles to WebAssembly (WASM).

## How to use this?

Although the focus of AssemblyScript is ostensibly the generation of `.wasm` modules that are suitable for deployment to the web, this Node.js-based replit is focused on a Test-Driven Development workflow via the included testing framework. 

Check the `package.json` for the scripts to compile or test your AssemblyScript. If you are on mobile and don't have access to the replit shell, [use the `.replit` file to configure the run button to run your `package.json` scripts.](https://docs.replit.com/programming-ide/configuring-run-button)

```
run = "npm run test"
```

[AssemblyScript Docs](https://www.assemblyscript.org/basics.html#strictness)
[As-pect Docs](https://tenner-joshua.gitbook.io/as-pect/as-api/test-structure)
