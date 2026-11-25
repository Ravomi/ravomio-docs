# Framework, RTOS & Embedded UI Plugins

RavomIO manages frameworks via `ravom-plugin`:

- **Rust Async / RTOS**: `embassy`, `rtic`, `bare-metal`
- **C/C++ RTOS & SDK**: `esp-idf`, `freertos`, `zephyr`, `rt-thread`
- **Embedded UI**: `mirui` (`no_std` ECS UI framework for MCU screens & desktop preview)
- **FPGA HDL**: `rust-hdl`, `spade`, `veryl`

Select any framework during initialization:
```bash
mio init --board esp32s3 --framework mirui
```
