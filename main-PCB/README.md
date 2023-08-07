# Pico-ONGEKI v3.0 (Needs Documenting)

![Pico-ONFGKI v3.0](Images\Pico-ONGEKI.png)

- 13 Buttons connections
  - 6 Main Buttons
    - Button + MintyLED
  - 2 WAD Buttons
    - Button + WS2812b (panel or strips)
  - 2 Menu Buttons
  - Test Button
  - Service Button
  - Coin Button
- Lever analog connector
- USB breakout board connector
- card reader connector

## configuration needed

Needs the correct io file.

Configure COM ports to port 1 & 3. for LED and Card Reader.

update stools conf

```ini
[aime]
enable=0
aimePath=DEVICE\aime.txt

[io4]
enable=0

[io3]
enable=0
```

## Firmware

Thanks \_LittleC\_! [satorusaka/lkick-io4](https://github.com/satorusaka/lkick-io4)
