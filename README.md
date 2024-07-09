# RustDllPoc
Proof of concept DLL written in Rust. Used in other projects to test DLL injection and other DLL-related attacks.

Exports a `DllMain` function that spawns a message box using the `MessageBoxW` Windows API call.

## Build
```PowerShell
# debug
cargo build

# release
cargo build --release
```
