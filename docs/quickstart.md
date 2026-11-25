# Quick Start

```bash
# 1. Check local toolchains
mio doctor

# 2. Search 2,339+ supported MCU, FPGA, and Linux SBC boards
mio boards stm32

# 3. Initialize a new project
mio init --board bluepill_f103c8 --framework embassy --dir my-app
cd my-app

# 4. Build & flash
mio build
mio flash --monitor
```
