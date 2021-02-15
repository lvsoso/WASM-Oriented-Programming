# WASM-Oriented-Programming


```shell
git clone https://github.com/emscripten-core/emsdk.git

cd emsdk

./emsdk update

./emsdk install latest

source "./emsdk_env.sh"

emcc hello.cc -o hello.js
emcc hello.cc -o hello.html

emcc capi_js.cc --js-library pkg.js -o capi_js.js
```