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

## References
- [Creating A DLL With Rust](https://samrambles.com/guides/window-hacking-with-rust/creating-a-dll-with-rust/index.html)
- [DllMain entry point](https://learn.microsoft.com/en-us/windows/win32/dlls/dllmain)
