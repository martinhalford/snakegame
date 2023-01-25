# snakegame

A demo snake game developed in Rust. 

Play demo snake game online at: [https://snake.halford.it](https://snake.halford.it) 

The snake game rust app runs in the browser and interacts with the user via a simple HTML/Typescript interface.

The JS/TS interface calls functions defined within the Rust app, compiled as WASM, using [WASM Bindgen](https://github.com/rustwasm/wasm-bindgen).

### Dependencies

1. Install rustup -> https://doc.rust-lang.org/book/ch01-01-installation.html

2. Install "wasm-pack" -> `cargo install wasm-pack`

3. Install npm dependencies -> `npm install` (must have Node JS) -> https://nodejs.org/)

### Compilation
Compile the rust code every time the changes are made in `src/lib.rs`

4. Compile rust code into web-assembly -> `wasm-pack build --target web`

5. Run the development server
`npm start`

6. Open the browser on `localhost:8080`

Note: This is a modified fork of an existing repo by Filip Jerga - [https://github.com/Jerga99/snake-rust-game](https://github.com/Jerga99/snake-rust-game)
