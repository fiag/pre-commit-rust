# Rust hooks for pre-commit

[Rust](https://www.rust-lang.org) tools package for [pre-commit](https://pre-commit.com).

## Using rust tools with pre-commit

```yaml
-   repo: https://github.com/doublify/pre-commit-rust
    rev: master
    hooks:
    -   id: fmt
    -   id: cargo-check
```
