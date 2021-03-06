# Quickstart

Before you can start writing a Rocket application, you'll need a **nightly**
version of Rust installed. We recommend you use [rustup](https://rustup.rs/) to
install or configure such a version. If you don't have Rust installed and would
like extra guidance doing so, see the [getting started](/guide/getting-started)
section.

## Running Examples

The absolute fastest way to start experimenting with Rocket is to clone the
Rocket repository and run the included examples in the `examples/` directory.
For instance, the following set of commands runs the `hello_world` example:

```sh
git clone https://github.com/SergioBenitez/Rocket
cd Rocket
git checkout v0.3.15
cd examples/hello_world
cargo run
```

There are numerous examples in the `examples/` directory. They can all be run
with `cargo run`.
