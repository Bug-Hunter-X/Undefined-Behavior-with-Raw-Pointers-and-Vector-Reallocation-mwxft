This repository demonstrates a common mistake in Rust: using raw pointers with vectors that might reallocate.  The `bug.rs` file shows the problematic code that leads to undefined behavior. The `bugSolution.rs` file presents a safer solution using standard vector indexing.