---
File Creation date: 2024-01-22
---
[[Vulcan]]
[[Cargo]]

# How to 
- extension: .rs
compile:
```
rustc <file name>
```
format:
```
rustfmt <file name>
```
## Variables
create a **immutable** variable (can't be changed unless it's redeclared)
```
let <name> = <value>;
```
specify **type** of variable
```
let <name>: <type> = <value>;
```
**constant** variables can't be changed and must have a type specified
```
const <name>: <type> = <value>;
```
create a **non mutable** variable
```
let mut <name> = <value>;
```
you can **redeclare** a variable
```
let x = 1;
let x = x + 3;
```

![[Pasted image 20240122225910.png|300]]
output:
```
x is: 4
x is: 2
x is: 5
```
### Types of variables
#### Basic
- `bool`: Represents a boolean value, either `true` or `false`.
- `char`: Represents a single Unicode character.
- `String`: Represents a dynamically allocated, growable string.
- `&str`: A reference to a string slice, which is a view into a string.
#### values
- `i8`: 8-bit signed integer.
- `i16`: 16-bit signed integer.
- `i32`: 32-bit signed integer.
- `i64`: 64-bit signed integer.
- `i128`: 128-bit signed integer.
- `u8`: 8-bit unsigned integer.
- `u16`: 16-bit unsigned integer.
- `u32`: 32-bit unsigned integer.
- `u64`: 64-bit unsigned integer.
- `u128`: 128-bit unsigned integer.
- `f32`: 32-bit floating-point number.
- `f64`: 64-bit floating-point number.
#### Pointer Types
- `&T`: Immutable reference.
- `&mut T`: Mutable reference.
- `*const T`: Raw immutable pointer.
- `*mut T`: Raw mutable pointer.
#### Other
- **Tuples:** A fixed-size ordered list of elements with different data types.
	`let tuple: (i32, f64, char) = (42, 3.14, 'a');`
- **Arrays:** A fixed-size array of elements with the same data type.
	let array: [i32; 5] = [1, 2, 3, 4, 5];


## Cargo
- create new project: cargo new \<file name\>
- build: cargo build
- build and run: cargo run
- check if compileable: cargo check