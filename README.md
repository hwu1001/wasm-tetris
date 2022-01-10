## wasm-tetris

Uses this framework: https://wasm4.org/

Based on this version in C: https://github.com/aduros/wasm4/tree/main/examples/watris

To build:
- `zig build -Drelease-small=true`
- `w4 run zig-out/lib/cart.wasm`

Or use `w4 watch` to build in real-time and watch for changes in source files