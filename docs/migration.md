# Migrating from PlatformIO

Convert any existing `platformio.ini` project into `ravom.toml` with one command:

```bash
cd my-platformio-project
mio migrate
```

You can also import custom PlatformIO `boards/*.json` directories into RavomIO's unified TOML board registry:

```bash
mio boards --import /path/to/platform/boards --platform myplatform
```
