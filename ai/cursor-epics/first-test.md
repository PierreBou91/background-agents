# First test epic

**Owner:** Cursor epic workflow (do not remove)

## Steps

- [x] Step 1: Add a file called `step1.rs` with a hello world in Rust
- [x] Step 2: Add a file called `step2.js` with a hello world in JS
- [ ] Step 3: Add a file called `step3.go` with a hello world in Golang

## Decisions

- 2026-05-02: Step 2 uses `console.log` in a root-level `step2.js` runnable with `node step2.js`; no `package.json` to match the epic’s single-file scope.
- 2026-05-02: Kept Step 1 as a standalone `step1.rs` (no `Cargo.toml`) so `rustc step1.rs` is enough to build and run; avoids expanding scope beyond the epic wording.

## History

- 2026-05-02: Step 2 done — added `step2.js` with `console.log("Hello, world!");` at repo root.
- 2026-05-02: Step 1 done — added `step1.rs` with `println!("Hello, world!");` at repo root.
