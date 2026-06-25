# v14b compile fix

Fixes a text-replacement mistake from v14:

```rust
pub pub mod master_data;
```

is corrected to:

```rust
pub mod master_data;
```

No runtime logic is changed from v14.
