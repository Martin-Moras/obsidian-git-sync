---
File Creation date: 2024-01-22
---
[[Vulcan]]
[[Cargo]]

# How to 
- extension: .rs
- compile: rustc \<file name\>
## Variables
create a immutable variable (can't be change)
```
let <name> = <value>
```
create a non static variable
```
let mut <name> = <value>
```
you can redeclare a varuable
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



## Cargo
- create new project: cargo new \<file name\>
- build: cargo build
- build and run: cargo run
- check if compileable: cargo check
