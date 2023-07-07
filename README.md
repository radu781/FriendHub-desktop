# FriendHub desktop application

## Setup

```bash
rustup target add wasm32-unknown-unknown
cargo install trunk
cargo install wasm-bindgen-cli
cargo install tauri-cli
```

## Run

```bash
cargo tauri dev  # dev build
cargo tauri build  # release build
```
