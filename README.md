# CLI to-do list created with Rust

## Commands
To add a new item:
```bash
cargo run -- add [item]
```
To mark a task as finished:
```bash
cargo run -- complete [item]
```
To view the existing list:
```bash
cat db.json
```
To clear the list:
```bash
rm db.json
```
