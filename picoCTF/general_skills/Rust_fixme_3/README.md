# picoCTF – fixme3 (Rust Unsafe Block Challenge)

## Executive Summary

This challenge involved debugging a Rust project that failed to compile due to unsafe memory operations. The objective was to analyze the compiler error and apply the correct fix while maintaining memory safety principles.

Primary Concept:
- Rust memory safety enforcement
- Unsafe blocks
- Raw pointer handling

This challenge highlights how modern systems languages like Rust enforce secure coding practices at compile time.

---

## Technical Analysis

### 1. Initial Issue

Running:


cargo run


Produced the error:


error[E0133]: call to unsafe function std::slice::from_raw_parts
is unsafe and requires unsafe function or block


The failing line:

```rust
std::slice::from_raw_parts(decrypted_ptr, decrypted_len);