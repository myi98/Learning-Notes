# Rust Learning Notes

There are a lot of learning notes for Rust here. This covers the general langauage characteristcs of Rust.

## Rust Installation

For Linux or Windows WSL
```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

For Windows

* Install Visual C++ 2013 up first
* Download RUSTUP-INIT.EXE and run

## First Rust Program

Use the ```cargo new hello``` command to create a project.
Then there is a directory "\hello" is created, inside the "\hello" directory there are two fiels Cargo.lock and Cargo.toml, two directories "\src" and "target"

There is a main.rs file inside the src director. It is shown here.

```
fn main() {
    println!("Hello, world!");
}

```

In the hello directory, input cargo run command, you will get the output





