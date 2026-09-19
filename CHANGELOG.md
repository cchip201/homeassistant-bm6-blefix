# Changelog

<!--next-version-placeholder-->

## 1.0.5
- Bluetooth discovery now matches the BM6 by its advertised name (`BM6*`) instead of five generic
  service UUIDs (0x1800, 0x1801, 0x180A, 0xFEE0, 0xFFF0). Those UUIDs are carried by ordinary phones,
  OBD dongles, headphones and locks, so Home Assistant offered dozens of unrelated devices as BM6
  monitors, and rotating private addresses brought the same phones back under new MACs. A real BM6
  advertises the name `BM6` with 0xFFF0; the four manufacturer-data matchers are unchanged.
## 1.0.3
- Added support for multiple Bluetooth scanners/gateways. Now the BM6 device is supported by more than one Bluetooth scanner/gateway. The scanner with the best signal strength is automatically selected to connect to the BM6. If you have more than one scanner/gateway, this version is just for you.
## 1.0.2
- Improvement of code especially translation.
## 1.0.1
- Improvement of code especially translation.
## 1.0.0
- First release.