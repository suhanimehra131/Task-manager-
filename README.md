# WASM-Based ClearTax Clone

## Setup Instructions

### 1. Install Rust and WASM Toolchain
```sh
rustup target add wasm32-unknown-unknown
cargo install wasm-pack
```

### 2. Build WASM Module
```sh
cd wasm-module
wasm-pack build --target web
```

### 3. Run Backend
```sh
cd backend
npm install express cors
node server.js
```

### 4. Open Frontend
Simply open `frontend/index.html` in your browser.
