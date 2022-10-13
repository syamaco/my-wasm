# Hello, WebAssembly!

## Visit Site
https://my-wasm.web.app

## How to buld _main.wasm_
```sh
(cd public; wat2wasm main.wat -o main.wasm)
```

## How to deploy
```sh
firebase deploy --only hosting:my-wasm
```

## Reference from
https://webassembly.github.io/wabt/demo/wat2wasm/index.html
