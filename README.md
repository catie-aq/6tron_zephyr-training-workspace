# Zephyr OS workspace

6TRON workspace to train in Zephyr OS.

## Usage
- Initialize the Zephyr workspace
```bash
west init -m https://github.com/catie-aq/6tron_zephyr-training-workspace 6tron-workspace
```

- Update workspace
```bash
cd 6tron-workspace
west update
```
- Build and flash basic sample application
```bash
cd applications/hello_world
west build --board zest_core_fmlr-72
west flash
```
