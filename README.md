# Brain (based on [Urchin by Duckyb](https://github.com/duckyb/urchin))

![PCB Preview](./gallery/main/main-top.png)
![PCB Preview](./gallery/main/main-bottom.png)

<span>
  <img src="https://img.shields.io/github/last-commit/Wesztman/brain?style=flat-square">
  <a href="https://github.com/Wesztman/brain/releases">
    <img src="https://img.shields.io/github/v/release/wesztman/brain">
  </a>
  <a href="https://github.com/duckyb/urchin">
    <img src="https://img.shields.io/badge/based%20on-urchin-orange">
  </a>
  <img src="https://img.shields.io/static/v1?label=license&message=MIT&color=success&style=flat-square">
</span>

My first ever keyboard build was the Ferris Sweep, it's a wonderful keyboard! But I missed a few keys, the ctrl and shift keys on the left side and since I'm Swedish, I also wanted keys for åäö. Apart from this I was also only interested in wireless designs and was not interested in the TRRS jacks etc. The Urchin was the perfect solution for me, but I were still missing those oh so sought after keys. So I decided to make my own version of the Urchin, with a few extra keys and a little tweek to the edge cut to fit them nicely.

The result of this is the Brain, a wireless split keyboard based on the Urchin with 3 extra keys on each side. One extra pinky column with two keys and one extra thumb key. All 5 pinky keys are placed 2mm lower than the original Urchin keys, to make it easier to reach them.

**This is a strictly wireless-only design, and is only compatible with ZMK / nice!nano. Only Choc v1 switches + Hotswap are supported!**

## Features compared to [Urchin](https://github.com/duckyb/urchin)

- [x] Original pinky column lowered 2mm.
- [x] A new pinky column added with two buttons, also 2mm offset down from its neighbour.
- [x] One new thumb button added.

## Coming soon

- [ ] Add 3D printed case.
- [ ] Add travel case.

## Part list (for both sides)

#### Required

- 1× PCB Kit (files for it are in [releases](https://github.com/wesztman/brain/releases))
- 40× Kailh **CHOC** Hotswap Sockets
- 40× Kailh Choc v1 Switches
- 40× Keycaps
- 40× SMD diodes (SOD-123)
- 2× nice!nano
- 2× Lipo battery (301230)
- 48× mill-max machined pins
- 2× Pair of female mill-max headers (raised ones to fit battery, https://www.digikey.se/sv/products/detail/mill-max-manufacturing-corp/310-43-112-41-001000/1212186)

#### Optional

- 2× nice!view (needs higher sockets to get level above raised mill-max sockets, TODO add exact ones)
- 2× Reset switch (B3U-1000P(M))
- 2× Power switch (MSK 12C02)
- 10× adhesive silicone feet

## How do I make this?

Follow the the excellent build guide in the link below. The only difference is the 3 extra keys on each side.

<a href="https://youtu.be/CHSh1-dJq24" target="_blank">
<img src="https://gist.githubusercontent.com/duckyb/337340baa1f0c8bcc06fef7b3b57242b/raw/97e6e0748dd1b8a3fb54fac0a88e84e6b6e0e10a/build-guide-button.svg" height="44">
</a>

## Firmware

Brain supports ZMK only.

I have not managed to get a dedicated ZMK firmware for this keyboard set up yet.

Until I do, you can probably get something going based on the [zmk-urchin repository](https://github.com/duckyb/zmk-urchin). But since this keyboard has 3 extra keys added to the original Urchin, you will need to add those keys to the firmware.

## Credits

- Urchin by [duckyb](https://github.com/duckyb/urchin)
- Logo by [Ariyanto Deni](https://thenounproject.com/ariyantodeni/)
- 3D case by [iamDrakkir](https://github.com/iamDrakkir)

## License
[MIT](https://github.com/Wesztman/brain/blob/main/LICENSE)
