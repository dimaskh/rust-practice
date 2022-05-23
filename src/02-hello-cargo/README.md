# Hello Cargo

A program that demonstrates basic Cargo usage

## Usage

Build the program:

    cargo build

This command creates and executable file in _target/debug/hello_cargo_, that can be ran by:

    ./target/debug/hello_cargo

We can also use `cargo run` to compile the code and then run the resulting executable all in one command:

    cargo run

Cargo also provides a command called `cargo check`. This command quickly checks the code to make sure it compiles but doesn't produce an executable:

    cargo check
