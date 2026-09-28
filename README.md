# Application Skills for K1 / K3 RISC-V SoC

Fast, open, production-ready AI edge computing application demos and software skills for the SpacemiT K1 & K3 RISC-V SoCs.

This repository collects reusable application skills, sample code, inference pipelines, and best practices for AI edge workloads running on K1 and K3.

## Key Features

- **Mainline Linux support**: No vendor kernel forks. Works with upstream mainline Linux kernel.
- **Standard toolchain only**: Build directly with distro-provided GCC / LLVM / Binutils. No custom build pipeline or vendor-locked SDK required.
- **RISC-V native**: Optimized for K1 & K3 RISC-V silicon, targeting edge AI inference, sensor data processing, real-time control tasks.
- **Portable & open**: Minimal vendor-specific patches. Code can be reused on other standard RISC-V platforms with minor adaptations.

## What’s inside

- AI inference application examples
- Multicore task scheduling & real-time processing skills
- Peripheral driver usage (GPIO, UART, SPI, I2C, DMA)
- Memory management & cache tuning for edge AI workloads
- Performance profiling and benchmark scripts
- Deployment guides for rootfs, firmware and application packaging

## Build Requirements

- Linux distribution with mainline kernel supporting K1/K3
- Native or cross toolchain: GCC / LLVM (distro default packages)
- No proprietary vendor SDK, no custom patched toolchain

## Quick Start

```
# Clone this repo
git clone https://github.com/xxx/k1-k3-app-skills.git
cd k1-k3-app-skills

# Build sample apps
make

# Run on K1 / K3 board
./build/demo_infer
```

## Notes

All code examples are designed to work with upstream mainline software stack.
You do **not** need vendor-provided kernel forks or customized toolchains to compile and run.

## License

Apache-2.0
