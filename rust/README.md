# Rust projects

* installing rust
```bash
curl --proto '=https' --tlsv1.2 https://sh.rustup.rs -sSf | bash
source $HOME/.cargo/env
rustup update
rustc --version
1.49.0
cargo --version
1.49.0
```

* cargo
```bash
cargo new hello_cargo
cd hello_cargo
cargo build
cargo run
cargo check
cargo build --release
```