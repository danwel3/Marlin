# Ender 3 V3 SE Display

## Using Creality 1.0.4 TJC Firmware Version
No difference noticed with instruction set between 1.0.4 and 1.0.6 version in the screen at this stage. Will focus on using the 1.0.6 version of firmware.

### Marlinfw no changes
- Screen did not work using MarlinUI

### alpha-1
- Screen worked using MarinUI no Icons present
- Screen worked using Creality UI
  - No Icons Present
  - Display Resolution expected a larger screen

## Warning Messages that need resolving 

```bash
Marlin\src\lcd\e3v2\common\dwin_api.cpp: In function 'void dwinDrawString(bool, uint8_t, uint16_t, uint16_t, uint16_t, uint16_t, const char*, uint16_t)':
Marlin\src\lcd\e3v2\common\dwin_api.cpp:291:21: warning: unused variable 'widthAdjust' [-Wunused-variable]
  291 |   constexpr uint8_t widthAdjust = 0;
```