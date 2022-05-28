# z3-wasm

A simple Z3 SMT2 analyzer, ran entirely in your browser using WebAssembly.

## Website

#### https://virb3.github.io/z3-wasm/

## Building

```bash
npm i
npm run build
```

The built website will be in `dist/`.

## Running locally

```bash
md z3-wasm
xcopy dist z3-wasm
npx parcel z3-wasm\index.html
```

Open a browser to http://localhost:1234


## Credits

Front end heavily influenced from [cpitclaudel/z3.wasm](https://github.com/cpitclaudel/z3.wasm).

* integration with released version of z3 forked from ViRb3, 

* multiple examples based on Phillip Zucker's demo
