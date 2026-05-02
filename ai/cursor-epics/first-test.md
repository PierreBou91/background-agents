# First test epic

**Owner:** PierreBou

## Steps

- [x] Step 1: Add a file called `step1.rs` with a hello world in Rust
- [x] Step 2: Add a file called `step2.js` with a hello world in JS
- [ ] Step 3: Add a file called `step3.go` with a hello world in Golang

## History

- Step 2 complete: added repository-root `step2.js` with `console.log("Hello, world!")`.
- Step 1 complete: added repository-root `step1.rs` with a minimal Rust hello world (`println!`).

## Decisions

- Placed `step2.js` at the repo root next to `step1.rs`; hello world uses double-quoted string for consistency with common JS style. Verify with `node step2.js`.
- Kept `step1.rs` at the repo root without a `Cargo.toml`; the epic only asks for a file with hello world, and `rustc step1.rs` is sufficient to verify.
