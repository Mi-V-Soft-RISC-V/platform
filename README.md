# Mi-V soft processor platform source code

## Repo organization

```
<platform>
  |
  |-- drivers
  |     |- fpga_ip
  |     |     | CoreGPIO
  |     |     | CoreSystemServices_PF
  |     |     | CoreUARTapb
  |     |
  |     |- off_chip
  |     |     |  .
  |     |     |  .
  |     |
  |-- hal
  |     |
  |-- miv-rv32-hal

  
```

The drivers published here are compatible with the improved SoftConsole project folder structure being used in the latest [example projects](https://github.com/Mi-V-Soft-RISC-V/miv-rv32-bare-metal-examples).
Thes drivers can also be used with legacy folder structure (released via Firmware Catalog) by enabling the MACRO **LEGACY_DIR_STRUCTURE** in the SoftConsole project settings.

