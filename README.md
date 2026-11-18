# Teven examples

Example designs for Teven (InDrik Systems), the
Verilog and SystemVerilog hierarchy, trace and waveform tool. Teven for VS Code downloads them with
**Open Example Design**; you can also download them here and open them yourself.

The designs are the release assets of this repository (Releases), not files in it.

| Release | File | What it is |
|---|---|---|
| `darjeeling-v1` | `darjeeling_lite.zip` (2.4 MB) | Darjeeling, an open-source chip from OpenTitan: the RTL and a filelist, about 19,600 instances. Top module: `chip_darjeeling_lite_asic` |

## Use it without VS Code

Unzip it, then open `darjeeling_lite/darjeeling_lite.f` in Teven (**Open…**) with the top module
`chip_darjeeling_lite_asic`.

## Licence

The design files come from [OpenTitan](https://github.com/lowRISC/opentitan), copyright
lowRISC contributors, under the Apache License 2.0. The licence is in the zip
(`darjeeling_lite/opentitan/LICENSE`). They are unchanged apart from being selected and given a
filelist. Teven itself is not open source; this repository holds only example designs.
