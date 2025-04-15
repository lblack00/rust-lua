# rust-lua
Lua5.4 interpreter written in Rust

## How to Install

`git clone https://github.com/lblack00/rust-lua.git`

## How to Run

Locate the `src` directory and change directories into it using your terminal.
Run this command `cargo run -- ../test_lua/hello_world.lua`

Output:
```
[src/parse.rs:37:2] &constants = [
    print,
    hello, world!,
]
[src/parse.rs:38:2] &byte_codes = [
    GetGlobal(
        0,
        0,
    ),
    LoadConst(
        1,
        1,
    ),
    Call(
        0,
        1,
    ),
]
hello, world!
```
