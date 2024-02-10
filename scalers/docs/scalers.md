# Rust Data Types

Rust is a statically typed language, meaning the compiler must know the type of each variable at compile time. However, Rust can often infer the type based on the value assigned to the variable, defaulting to `i32` for integers if not explicitly specified.

## Scalar Types

Scalar types represent a single value. Rust has four primary scalar types: integers, floating-point numbers, Booleans, and characters.

### Integers

- **Definition**: Whole numbers that can be either signed (positive or negative) or unsigned (positive only).
- **Dependence**: The range of numbers depends on the computer architecture (32-bit vs. 64-bit).
- **Types**:
  - Signed (`i` prefix): Can store values from \(-2^{n-1}\) to \(2^{n-1}-1\).
  - Unsigned (`u` prefix): Can store values from 0 to \(2^n-1\).
- **Common Lengths**:
  
  | Length  | Signed | Unsigned |
  |---------|--------|----------|
  | 8-bit   | `i8`   | `u8`     |
  | 16-bit  | `i16`  | `u16`    |
  | 32-bit  | `i32`  | `u32`    |
  | 64-bit  | `i64`  | `u64`    |
  | 128-bit | `i128` | `u128`   |
  | Arch    | `isize`| `usize`  |

### Floating-Point Numbers

- **Definition**: Numbers with decimal points.
- **Types**: `f32` and `f64`, with `f64` being the default due to its precision.
- **Operations**: Support all standard numerical operations such as addition (+), subtraction (-), multiplication (*), division (/), and remainder (%).

### Booleans

- **Definition**: Can only be `true` or `false`.
- **Keyword**: `bool`.
- **Size**: 1 byte.
- **Usage**: Primarily used in conditional statements and loops.

### Characters

- **Definition**: Represents a single character.
- **Keyword**: `char`.
- **Notation**: Enclosed in single quotes (`'a'`, `'1'`, etc.).
- **Size**: 4 bytes, capable of representing more than just ASCII characters (e.g., emoji, accented letters).

## Summary

Rust's type system is designed to provide a high level of safety and performance. By understanding and correctly utilizing Rust's data types, developers can write efficient, safe, and bug-free code. The scalar types form the foundation of Rust's type system, enabling developers to perform a wide range of programming tasks, from simple arithmetic to complex logic involving multiple conditions and data representations.