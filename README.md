# Rust Data Race Example
This repository demonstrates a simple example of a data race in Rust caused by having multiple mutable references to the same variable.

The `bug.rs` file contains the code that produces the data race.  The `bugSolution.rs` file offers a solution that avoids the data race by using appropriate techniques like cloning, mutexes, or channels (depending on the concurrency model required).