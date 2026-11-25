# `mio` CLI Reference

- `mio init --board <ID> [--framework <FW>] [--dir <DIR>]` — Initialize a project
- `mio build [-e <ENV>] [-r]` — Build firmware or FPGA bitstream
- `mio run [-e <ENV>] [-t upload] [-r]` — PlatformIO-style build/upload
- `mio flash [-e <ENV>] [-r] [-m]` — Flash via `probe-rs` or `openFPGALoader`
- `mio monitor [--list | --rtt | --port <PATH> --baud <BAUD>]` — Serial/RTT monitor
- `mio boards [QUERY] [--import <DIR> --platform <NAME>]` — Search or import boards
- `mio migrate [--dir <DIR>]` — Convert `platformio.ini` to `ravom.toml`
- `mio sim [--backend renode|qemu|wokwi]` — Run firmware in a simulator
- `mio deploy --host <USER@HOST> [--remote-dir /tmp] [--run]` — Deploy to Linux SBC
- `mio doctor [--install-target <TRIPLE>]` — Check/install toolchains
- `mio ui` — Launch the `ravom-ui` egui desktop workbench
