# Rust Cheat Sheets:

| Title           | Remark/code |
| --------------- | ----------- |
| [Setup](#Setup) | Hello World |

### Setup

- Do the following Setup
  `rustup toolchain install stable-x86_64-pc-windows-gnu`
  `rustup default stable-x86_64-pc-windows-gnu`

- Create your first hello world

```rust
fn main(){
    println!("Hello World");
}
```

- Compose it
  `rustc main.rs`
- Run it
  `./main`

[home](#Rust-Cheat-Sheets:)
