# Ben Eater 8-Bit Breadboard Computer

A build log and reference notes following [Ben Eater's 8-bit breadboard computer series](https://eater.net/8bit).

---

## Build Status

| Module                    | Status         |
|---------------------------|----------------|
| Clock                     | ✅ Complete    |
| A & B Registers           | 🚧 In progres  |
| ALU                       | 🔲 Not started |
| RAM & MAR                 | 🔲 Not started |
| Program Counter           | 🔲 Not started |
| Output Register & Display | 🔲 Not started |
| Control Logic             | 🔲 Not started |

---

## Modules

### Clock Module
**Status:** Complete ✅
<img width="3880" height="1372" alt="Clock_Module" src="https://github.com/user-attachments/assets/4fb720cf-fd36-4984-be96-e63f1790ac10" />

The clock module uses a 555 timer in astable mode to generate a continuous square wave,
and a second 555 in monostable mode for single-step debugging. A debounced pushbutton
and selector switch allow toggling between automatic and manual clock modes.

### A & B Registers
**Status:** In progres 🚧

### ALU
**Status:** 🔲 Not started

### RAM & MAR
**Status:** 🔲 Not started

### Program Counter
**Status:** 🔲 Not started

### Output Register & Display
**Status:** 🔲 Not started

### Control Logic
**Status:** 🔲 Not started

---

## Hardware

- Logic family: 74LS series
- Breadboards: 14 × full-size
- Power supply: Regulated 5V

---

## Resources

- [Ben Eater's website](https://eater.net/8bit)
- [Ben Eater's YouTube playlist](https://www.youtube.com/playlist?list=PLowKtXNTBypGqImE405J2565dvjafglHU)
- [74LS173 datasheet](https://www.ti.com/lit/ds/sdls067a/sdls067a.pdf)
- [74LS245 datasheet](https://www.ti.com/lit/ds/symlink/sn74ls245.pdf)
- [555 timer datasheet](https://www.ti.com/lit/ds/symlink/ne555.pdf)

