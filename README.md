# wasm-helloc
C Program to WASM

This is a sample code to try out deploying C program on to Browser using Web Assembly features.

Steps
1. Install emscripten (https://emscripten.org/docs/getting_started/downloads.html)
2. Use the main.c file to run `emcc main.c -s WASM=1 -o main.html`
3. Open the main.html in vscode, and run LiveServer (https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) OR use python to serve this directory using `python3 -m http.server`
4. Now your program will run inside browser's virtual machine.

I have added the compiled WASM binaries to the repo to get an idea. You can check out the html file and see how things are connected.

More details can be found on this article
https://www.codegully.com/blog/introduction-to-web-assembly



