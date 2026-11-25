# Open-Source FPGA Workflow

RavomIO supports community FPGA boards across **Lattice MachXO2**, **Lattice ECP5**, **Lattice iCE40**, **Gowin**, and **Xilinx Artix-7**:

```bash
mio init --board step_mxo2_lpc --framework rust-hdl --dir my-fpga
cd my-fpga
mio build   # runs rust-hdl Verilog export + yosys synthesis
mio flash   # flashes bitstream via openFPGALoader
```
