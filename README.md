# ONGEKI Controller Build (DOCUMENTATION INCOMPLETE)

DIY Controller for Ongeki.

## TODO

- Add Swing Mechanism files and documentation
- Add Main pcb files and documentation

## Electronics

- 22AWG wire
- various XH connectors
- Female Spade Crimp Terminals
- USB-C breakout board.

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
- Lever analog connector
- USB breakout board connector

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

- Sanwa OBSF-24 24mm round buttons or any other buttons
- Links
  - [Sanwa Official Store](https://www.rakuten.co.jp/sanwadenshi/)
  - [IST 24mm](https://www.us.istmall.co.kr/Product/Detail/view/pid/25/cid/)
  - AliExpress: 24mm round arcade button

---

## Wall Attack Device (WAD) sub-assembly

Documentation in [WAD assembly](WAD%20assembly/README.md).

## Swing Mechanism sub-assembly

Documentation in [Swing assembly](Swing%20assembly/README.md).

---

## Case

- mdf / sheet-metal
- Dimensions: 783x295x90mm (WxDxH)

### WAD Walls

- mdf / sheet-metal
- T-Nut to attach side wall to Main body
- slide down from top to attach

### Control Panel Acrylic

- Dimensions: 669x295mm (WxD)
- 5mm thick
- 3mm chamfers
- 5mm rounded corner

#### Panel Graphics printing options

- [silkscreen printing](https://www.acrylic.com.sg/silkscreen-printing/)
- UV printing
- Poster Paper

---

## Firmware

Thanks \_LittleC\_! [satorusaka/lkick-io4](https://github.com/satorusaka/lkick-io4)
