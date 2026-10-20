# Basic Gates in Electric VLSI

This project brings together the transistor-level gate layouts I made while working on my ALU. I pulled them into one small library so they are easier to explore and reuse.

The Electric library contains seven gates: AND, NAND, NOR, NOT, OR, XOR, and XNOR. Each is stored as a layout cell in the `MoCMOS` technology.

## Gates

| Gate | Library cell | Logic |
| --- | --- | --- |
| AND | `AND_GATE` | `Y = A AND B` |
| NAND | `NAND_GATE` | `Y = NOT (A AND B)` |
| NOR | `NOR_GATE` | `Y = NOT (A OR B)` |
| NOT | `NOT_GATE` | `Y = NOT A` |
| OR | `OR_GATE` | `Y = A OR B` |
| XOR | `XOR_GATE` | `Y = A XOR B` |
| XNOR | `XNOR_GATE` | `Y = NOT (A XOR B)` |

## Open the library

1. Open Electric VLSI.
2. Open `Basic_Gates.jelib` as an Electric library.
3. Pick a gate cell to inspect or edit its layout.

The library records its technology as `MoCMOS` with five metal layers. If your Electric setup does not have that technology configured, you may need a compatible setup to open it correctly.

## File

- `Basic_Gates.jelib` - the original Electric VLSI library with all seven gate layout cells.

I kept the library as supplied. This repository does not claim simulation, design-rule, or fabrication results. No license has been chosen yet; add one if you want to grant reuse rights to others.
