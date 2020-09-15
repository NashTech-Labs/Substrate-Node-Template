# Substrate based PoE Application

This templeate is based on tutorial provided by Substrate.   

## Building

### Install Rust


```bash
$ curl --proto '=https' --tlsv1.2 https://sh.rustup.rs -sSf | sh
```
### Install Substrate
```bash
curl https://getsubstrate.io -sSf | bash -s -- --fast
```

## Compiling Template

1. Clone the Template
```bash
$ git clone https://github.com/knoldus/Substrate-Node-Template.git
```
2. Initialize your WebAssembly build environment
```bash
source ~/.cargo/env

rustup update nightly
rustup update stable

rustup target add wasm32-unknown-unknown --toolchain nightly
```
3. Compile the Node Template
```bash
cd Substrate-Node-Template/
cargo build --release
```


