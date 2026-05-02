# first-test (test epic)

**Owner:** PierreBou91

## Steps

- [x] Step 1: Add a file called `step1.rs` with a hello world in Rust
- [x] Step 2: Add a file called `step2.js` with a hello world in JS
- [ ] Step 3: Add a file called `step3.go` with a hello world in Golang

## Decisions (newest first)

- **2026-05-02:** Step 2 uses `console.log('Hello, world!');` for Node-style JS hello world at repo root.
- **2026-05-02:** Implemented Step 1 as a standalone `step1.rs` at repo root, compilable with `rustc step1.rs` (no Cargo crate required for this epic step).

## History

- **2026-05-02:** Step 2 complete — added `step2.js` with `console.log('Hello, world!');`.
- **2026-05-02:** Step 1 complete — added `step1.rs` with `println!("Hello, world!");`.
