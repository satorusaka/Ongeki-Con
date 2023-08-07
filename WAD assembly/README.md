# Wall Attack Device (WAD) sub-assembly

I've designed this WAD to be accurate to the original design and function, using photo sensor for trigger, and flat spring for return mechanism.

There is a STEP file provided for this assembly, you can use it as a guide or modify it to your needs.

## Photos

![WAD Photo](Images\WAD-Assy.png)
![WAD Photo](Images\WAD%201.JPG)
![WAD Photo](Images\WAD%202.JPG)
![WAD Photo](Images\WAD%203.JPG)
![WAD Photo](Images\WAD%204.JPG)

## Required Parts

parts needed for the PCB are listed under the [PCB Section](#custom-wad-pcb)

| Part                                               | Qty                                            | Links                                                                        |
| -------------------------------------------------- | ---------------------------------------------- | ---------------------------------------------------------------------------- |
| LG-JT01 photo interrupter                          | 2                                              | [AliExpress](https://www.aliexpress.com/item/33015487463.html)               |
| JST H3P-SHF-AA\*                                   | 1                                              | [LCSC](https://www.lcsc.com/product-detail/_JST-Sales-America-_C495211.html) |
| JST SHF-001T-0.8BS\*                               | 3                                              | [LCSC](https://www.lcsc.com/product-detail/_JST-Sales-America-_C141769.html) |
| EVA foam tape, single sided, 10mm width, 1mm thick | 1 roll                                         | [AliExpress](https://www.aliexpress.com/item/1005001829983926.html)          |
| m3 threaded inserts                                | (x9 with pcb) or (x5 no pcb)                   |                                                                              |
| m3x4 bolts                                         | 4 (x2 for flat spring) (x2 for sensor trigger) |                                                                              |
| m3x6 bolts                                         | 6 (x4 for PCB) (x2 for Button Limiter)         |                                                                              |
| m3 bolts (button frame to side panel)\*\*          | 6                                              |                                                                              |
| m4 bolts (WAD cover to side panel)\*\*             | 5                                              |                                                                              |
| m3 and m4 nuts                                     |                                                |                                                                              |

\* for connecting LG-JT01, alternatively you can use dupont connectors.

\*\* bolt length depends on panel thickness

## Printed Parts

![Printed Parts](Images\Printed-parts.png)

Print 2 each, 1 per side. I recommend printing the button face vertically for a nicer looking surface.

| Parts          | Qty | Notes                                                            |
| -------------- | --- | ---------------------------------------------------------------- |
| Button Face    | 2   |                                                                  |
| Sensor Trigger | 2   |                                                                  |
| Button Limiter | 2   |                                                                  |
| WAD Cover      | 2   |                                                                  |
| Button Frame   | 2   | Use (No PCB) if you are use LED strips instead of Custom WAD PCB |

## Custom Parts

### Flat Spring

![Flat Spring Dimensions](Images/Spring%20Dimensions.png?raw=true)

- Dimensions: 20x50mm
- thickness: 0.64mm
- Sheet brass/steel
- apply grease on contacting surface.

### Pivot Shaft

![Pivot Dimensions](Images\pivot-rod.png?raw=true)

- 3.97mm dia., 150mm length
  Optionally, you can tap rod ends with M4 threads and use m4 nuts and washers on both ends to secure. personally I just use friction fit

### Custom WAD PCB

![WAD PCB](Images\WAD-PCB.png?raw=true)

LED Panel with cable passthrough for Photosensor. Alternatively, you can use WS2812b LED Strips in place of the PCB.

#### BOM

| Part                 | qty |
| -------------------- | --- |
| WS2812B              | 8   |
| 0.1uF 0603 Capacitor | 8   |
| JST S4B-XH-A-1       | 1   |
| JST S3B-XH-A-1       | 1   |
| JST XHP-4            | 1   |
| JST XHP-3            | 1   |
| JST XH contacts      | 7   |

### Sticker Decal

![wad decal](Decal\WAD-decal.png)
