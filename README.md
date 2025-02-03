This repository demonstrates a common error in unsafe Rust code involving raw pointers and vector reallocation. The `bug.rs` file contains code that attempts to modify a vector's elements using a raw pointer after the vector might have reallocated its internal memory. This leads to undefined behavior. The `bugSolution.rs` file provides a safe alternative.