# Valtio

A todo app using valtio as state management library.

The code is copied from: https://github.com/pmndrs/valtio/tree/main/examples/todo

## Modifications

We disabled `<StrictMode>`, because it's for development only. We would like to evaluation behaviors for production.

We add a key to `FilterRow` buttons list, otherwise React will complain.

We add a `console.log` to EVERY component, for example `console.log("TodoRow render");`

## How to run

```
yarn install
yarn dev
```

## Tests

For test rules and details, please go to the <a href="https://github.com/tylerlong/todo-state-management" target="_blank">main branch</a>.

## Result (passed 0 / 5)

- test 1 ❌
- test 2 ❌
- test 3 ❌
- test 4 ❌
- test 5 ❌
