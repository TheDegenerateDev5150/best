# best
Bam Error STats (BEST): analysis of error types in aligned reads.

## Development
### Running
1. Install [Rust](https://www.rust-lang.org/tools/install).
2. Run `cargo build --release`.
3. Run `cargo run --release -- input.bam reference.fasta prefix/path` or
`target/release/best input.bam reference.fasta prefix/path`.

This will generate stats files with the `prefix/path` prefix.

The built binary is located at `target/release/best`.

### Formatting
```
cargo fmt
```

### Comparing
Remember to pass the `-t 1` option to ensure that only one thread is used for
testing.
