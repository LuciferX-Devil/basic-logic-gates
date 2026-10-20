# Basic Gates in Electric VLSI

This project brings together the transistor-level gate layouts I made while working on my ALU. The library contains seven gates: AND, NAND, NOR, NOT, OR, XNOR, and XOR.

I kept the original Electric library intact so each cell stays editable in Electric VLSI. The gates are saved as layout cells in the `MoCMOS` technology. This repository is a focused home for those layouts and a simple guide to what is inside.

## The gates

| Gate | Library cell | Logic |
| --- | --- | --- |
| AND | `AND_GATE` | `Y = A AND B` |
| NAND | `NAND_GATE` | `Y = NOT (A AND B)` |
| NOR | `NOR_GATE` | `Y = NOT (A OR B)` |
| NOT | `NOT_GATE` | `Y = NOT A` |
| OR | `OR_GATE` | `Y = A OR B` |
| XNOR | `XNOR_GATE` | `Y = NOT (A XOR B)` |
| XOR | `XOR_GATE` | `Y = A XOR B` |

## Open the library

1. Open Electric VLSI.
2. Open `Basic_Gates.jelib` as an Electric library.
3. Choose a gate cell from the library to inspect or edit its layout.

The library records its technology as `MoCMOS` with five metal layers. If your Electric installation does not have that technology configured, the library may need to be opened in a compatible setup.

## What's included

- `Basic_Gates.jelib` - the original Electric VLSI library, containing all seven gate layout cells.

The `.jelib` file is kept as supplied. No simulation, DRC, or fabrication result is claimed by this repository. No license has been selected yet; add one if you want to grant reuse rights to others.
