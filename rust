# Rust cheatsheet
General stuff to remember for Rust, this is just because I am 'le stupid'.

### Variables
Declare a new variable with `let`:
```rust
let x = 5;
```
By default, variables are immutable in Rust. To make a variable mutable, use `mut`:
```rust
let mut x = 5;
x = 10; // New declaration, since its mutable
```

### Types
Rust is a statically-typed language, which means that you must specify the type of each variable when you declare it. Some basics types include:

* `i32`: 32-bit signed integer, -(2^31) to (2^31)-1.
* `u32`: 32-bit unsigned integer, 0 to (2^31)-1.
* `f64`: 64-bit floating point number, -(2^63) to (2^63)-1.
* `bool`: Boolean value, true or false
* `char`: Single Unicode character, like `a` or `😁`.

Custom types are defined with:

* `struct`
* `enum`
* `trait`

### Functions
Declare a function with `fn`:

```rust
fn add(x: i32, y: i32) -> i32 {
    x + y
}
```
Note the -> i32 syntax, which specifies the return type of the function. If a function does not return a value, its return type is () (the unit type).

You can call a function with the usual syntax:

```rust
let result = add(5, 10);
```
