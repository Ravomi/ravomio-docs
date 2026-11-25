# Simulation & Linux SBC Deployment

## Hardware Simulation (`mio sim`)
```bash
mio sim --backend renode
mio sim --backend qemu
mio sim --backend wokwi
```

## Linux SBC SSH/SCP Deployment (`mio deploy`)
```bash
mio build --release
mio deploy --host root@192.168.42.1 --remote-dir /tmp --release --run
```
