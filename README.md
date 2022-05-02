# My_Learning_Near

Learn everything about NEAR blockchain protocol

A playground for writing, compiling, testing smart contracts on Near chain(s): Mainnet, Testnet, Devnet.

## Installation

> The following is for Mac OS M1.

### `rustup`, `rustc`, `cargo`, `rustfmt`

* Install Rust i.e. `rustc`, `cargo`, `rustfmt`

```console
$ curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh

This will download and install the official compiler for the Rust
programming language, and its package manager, Cargo.

Rustup metadata and toolchains will be installed into the Rustup
home directory, located at:

  /Users/abhi3700/.rustup

This can be modified with the RUSTUP_HOME environment variable.

The Cargo home directory located at:

  /Users/abhi3700/.cargo

This can be modified with the CARGO_HOME environment variable.

The cargo, rustc, rustup and other commands will be added to
Cargo's bin directory, located at:

  /Users/abhi3700/.cargo/bin

This path will then be added to your PATH environment variable by
modifying the profile files located at:

  /Users/abhi3700/.profile
  /Users/abhi3700/.zshenv

You can uninstall at any time with rustup self uninstall and
these changes will be reverted.
```

```console
❯ rustup component add rustfmt                                                ⏎
info: component 'rustfmt' for target 'aarch64-apple-darwin' is up to date
```

`cargo`: Rust package manager
`rustc`: Rust compiler
`rustup`: Rust toolchain installer

* Update: `$ rustup update stable`
* Uninstall Rust i.e. `rustup`, `rustc`, `cargo`, `rustfmt`

```console
rustup self uninstall
```

> NOTE: If there is any error related to `linker` with C, follow this:

> You will also need a linker, which is a program that Rust uses to join its compiled outputs into one file. It is likely you already have one. If you get linker errors, you should install a C compiler, which will typically include a linker. A C compiler is also useful because some common Rust packages depend on C code and will need a C compiler.

> On macOS, you can get a C compiler by running:

```console
xcode-select --install
```

### For Near

#### `wasm`

As the Near chains accept `wasm` format as machine code language to run in the node's VM. That's why install this package in rust toolchains.

```console
rustup target add wasm32-unknown-unknown
```

#### `cli`

To install the `near-cli`, use this:

```console
npm install -g near-cli
```

verify installation

```console
near --version
```

## Troubleshoot

## References

### Repositories

### Blogs

### Videos

* [Intro to RUST by NEAR](https://www.youtube.com/watch?v=eVmVMrwZW0g)
