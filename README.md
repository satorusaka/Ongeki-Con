# ONGEKI Controller Build (DOCUMENTATION INCOMPLETE)

DIY Controller for Ongeki.

## Electronics

- 22AWG wire
- various XH connectors
- Female Spade Crimp Terminals

### Main PCB (Needs Documenting)

Raspberry Pi Pico breakout Board

- 13 Buttons connections
  - 6 Main Buttons
    - Button + MintyLED
  - 2 WAD Buttons
    - Button + WS2812b (panel or strips)
  - 2 Menu Buttons
  - Test Button
  - Service Button
  - Coin Button
- Lever analog
- USB breakout board

### WAD PCB

LED Panel with passthrough for Photosensor. Documentation in `/WAD assembly`.

### USB Breakout board

Any USB-C breakout board.

### Buttons

[Rhythm-cons.wiki: Buttons Guide](https://rhythm-cons.wiki/w/Buttons)

#### Main buttons (x6)

- Sanwa OBSA-60UK 60mm Square button
- using [Mintyleds](https://shop.mon.im/product/mintyleds)
- Links
  - [Sanwa Official Store](https://www.rakuten.co.jp/sanwadenshi/)
  - [IST 60UK](https://www.us.istmall.co.kr/Product/Detail/view/pid/67/cid/)
  - AliExpress: 60mm square arcade button

#### Menu buttons (x2) (1 Yellow, 1 Red)

- OBSF-24KK YELLOW & RED 24mm square button
- Links
  - [Sanwa Official Store](https://www.rakuten.co.jp/sanwadenshi/)
  - AliExpress: 24mm square arcade button

#### Extra buttons (Test,Service,coin) (x3)

- 24mm round buttons or any other buttons
- Sanwa OBSF-24
- Links
  - [Sanwa Official Store](https://www.rakuten.co.jp/sanwadenshi/)
  - [IST 24mm](https://www.us.istmall.co.kr/Product/Detail/view/pid/25/cid/)
  - AliExpress: 24mm round arcade button

---

## Wall Attack Device (WAD) sub-assembly

Replicates arcade cabinet design and function. Documentation in `/WAD assembly`.

## Lever sub-assembly (Needs Documenting)

### 3D Printed Parts

- Knob
- Frames, front and back
- sensor holder
- spring holder
- M8 T-coupler

### Lever Parts

- Handle Rod. 10mm Dia., 150mm Len. metal rod
- M8x90 Hex Bolt(x1). **pivot rod.**
- M8x60 Hex Bolt(x2). **End Rods.**
- M8 nuts(x4) (use threadlocker)
- Rubber Tube (8mm ID, 15mm OD, 23mm Length)
- 608 bearings(x2) (ID:8mm, OD:22mm, Width:7mm)
- 3.3v angle sensor
- 6x8 Shaft Coupler (D:14, L:25)
- M3x6 Bolt(x2) **angle sensor**
- M3 Countersunk Bolts(x6). (or 9mm + thickness of case.)
- M3x10 Bolts(x4) **Friction plate**
- M3x16 Bolts(x2) **T-Coupler clamp**
- M3x8 Bolts(x2) **T-Coupler Handle rod**
- M3 Nuts(x18) (Treaded Inserts)
- [Compression Spring](https://www.aliexpress.com/item/4000436939383.html) (Wire Dia. : 2mm, Len. : 80mm, OD: 30mm)
- Grease

---

## Controller Case

- mdf / sheet-metal
- Dimensions: 783x295x90mm (WxDxH)

## WAD Walls

- mdf / sheet-metal
- T-Nut to attach side wall to Main body
- slide down from top to attach

## Control Panel Acrylic

- Dimensions: 669x295mm (WxD)
- 5mm thick
- 3mm chamfers
- 5mm rounded corner

### Panel Graphics printing options

- [silkscreen printing](https://www.acrylic.com.sg/silkscreen-printing/)
- UV printing
- Paper insert

---

## Notes & References

- [rhythm-cons.wiki](https://rhythm-cons.wiki/w/Ongeki)
- [cab photos](https://photos.google.com/share/AF1QipPur0GExM6ftsZ-0MSKVLL0iPzG87EIehGkDcn-gwX2q84G2SUYe2BA4SfxvfC4WQ?key=WkkxV2FkOVNnX1l6QmFwUVhJeExXQUdNbjI2aFFn)

---

## Firmware

[satorusaka/lkick-io4](https://github.com/satorusaka/lkick-io4)
