#### small crt0 

- gets you out of assembly fast.
- prints out argv and envp as demo.

#### Compiling
Most compilers should work, however, if you're at the point that youre stripping crt0, you should be on musl already.

Recommended Compilers
- openwrt prebuilts (gcc + musl)
  - example: https://downloads.openwrt.org/snapshots/targets/x86/64/
- zig cc (llvm + musl)
  - https://ziglang.org/download/
- otherwise roll your own. 

