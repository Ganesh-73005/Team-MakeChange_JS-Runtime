# Section 1: Basic JS Runtime

## Overview
This section covers the fundamentals of creating a basic JavaScript runtime using Rust and Deno core. We'll set up the project structure and implement a simple custom console function.

## Key Components

1. **Cargo.toml**: Project configuration and dependencies
2. **src/main.rs**: Main Rust file implementing the JS runtime
3. **src/runtime.js**: JavaScript file defining custom console functions
4. **example.js**: Example JavaScript file to run in our custom runtime


## Setup Instructions

1. Install Rust and Cargo
2. Create a new Rust project: `cargo init myjs`
3. Add dependencies to `Cargo.toml`:
   ```toml
   [dependencies]
   deno_core = "0.221.0"
   tokio = { version = "1.32.0", features = ["full"] }
   ```
4. Implement the runtime in `src/main.rs`
5. Create custom console functions in `src/runtime.js`
6. Create an example JavaScript file `example.js`

## Running the Runtime

Execute the following command in the project directory:
```
cargo run
```

This will build the project and run the `example.js` file using our custom runtime.

## Next Steps

- Experiment with adding more custom console functions
- Try running different JavaScript code in `example.js`
- Explore the Deno core documentation for more advanced features
