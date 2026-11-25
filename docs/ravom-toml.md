# `ravom.toml` Reference

All RavomIO projects and board definitions use TOML.

```toml
[project]
name = "my-app"
default_envs = ["bluepill_f103c8"]

[env.bluepill_f103c8]
platform = "ststm32"
board = "bluepill_f103c8"
framework = "embassy"
build_flags = []
lib_deps = []
upload_protocol = "probe-rs"
monitor_speed = 115200
```

Migrate an existing PlatformIO project automatically with `mio migrate`.
