# Keymap for tsubasa with multifunctional rotary encoder
![keymap](https://imgur.com/wIRs6Eb.jpeg)

## Setup
Move this file to qmk_firmware
```bash
cp -r multifunc_encoder qmk_firmware/keyboards/handwired/tsubasa/keymaps
```

## Build and Flash
```bash
qmk compile -kb handwired/tsubasa -km default
```

Flashing example for this keyboard:

```bash
qmk flash -kb handwired/tsubasa -km default
```
