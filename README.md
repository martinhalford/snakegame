# snakegame

A demo snake game developed in Rust. 

The snake game rust app runs in the browser and interacts with the user via a simple HTML/Typescript interface.

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