+++
title = "Resource Types"
weight = 1
description = "High level information about LBPs resource types"
+++

# Info

Most of this information was found from Ennuo's LBP Toolkit, more specifically this file [here](https://github.com/ennuo/toolkit/blob/main/lib/cwlib/src/main/java/cwlib/enums/ResourceType.java)

# Resource Types

| Docs Page | Magic Number | Type ID (Hex) | Type ID (Decimal) | Extension | Description |
|---|---|---|---|---|---|
||`TEX` or `GTF`| 0x1 | 1 | `.tex` |  An image/texture, used in stickers among other things |
|| `MSH` | 0x2 | 2 | `.mol`| A 3d model/mesh |
|| None | 0x3 | 3 | `.fpo` | Fragment shader |
|| None | 0x4 | 4 | `.vpo` | Vertex Shader |
|| `ANM` | 0x5 | 5 | `.anim` | An animation |
|| `GSB` | 0x6 | 6 | `.gsub` | GUID Substitution |
|| `GMT` | 0x7 | 7 | `.gmat` | Graphical Material |
|| None | 0x8 | 8 | `.sbu` | SPU elf binary |
|| `LVL` | 0x9 | 9 | `.bin` | Level data, contains the layout of things |
|| None | 0xA | 10 | `.txt` | Filename, usually refers to FF or Bink |
|| `FSH` | 0xB | 11 | `.ff` | Fish Fingers script, the source of all evils in the world |
|| `CHA` | 0xC | 12 | `.cha` | Character settings |
|| None | 0xD | 13 | `.raw` | Raw Data |
|| `SSP` | 0xE | 14 | `.sph` | Softbody physics settings |
|| `FNT` | 0xF | 15 | `.fnt` | Fontface |
|| `MAT` | 0x10 | 16 | `.mat` | Physics Material |
|| `DLC` | 0x11 | 17 | `.dlc` | Downloadable Content |
|| None | 0x12 | 18 | `.edset` | Editor Settings |
|| `JNT` | 0x13 | 19 | `.joint` | Joint |
|| `CON` | 0x14 | 20 | `.con` | Game Contants |
|| `POP` | 0x15 | 21 | `.pop` | Poppet Settings |
|| `CLD` | 0x16 | 22 | `.cld` | Cached Level Data |
|| `PRF` | 0x17 | 23 | `.pro` | Synced Profile |
|| `BEV` | 0x18 | 24 | `.bev` | Bevel |
|| `GAM` | 0x19 | 25 | `.game` | Game |
|| `NWS` | 0x1A | 26 | `.nws` | Network settings, contains settings to do with the server, and p2p multiplayer. |
|| `PCK` | 0x1B | 27 | `.pck` | Packs |
|| `BPR` | 0x1C | 28 | `.bpr` | Big profile |
|| `SLT` | 0x1D | 29 | `.slt` | Slot list |
|| None | 0x1E | 30 | `.trans` | Translation data |
|| `ADC` | 0x1F | 31 | `.adc` | Adventure create profile |
|| `IPR` | 0x20 | 32 | `.ipr` | Local profile |
|| `LMT` | 0x21 | 33 | `.lmt` | Limit settings |
|| `TUT` | 0x22 | 34 | `.tut` | Tutorials |
|| `GLT` | 0x23 | 35 | `.glst` | GUID list |
|| `AUM` | 0x24 | 36 | `.aum` | Audio material |
|| `SSF` | 0x25 | 37 | `.flu` | Fluid settings |
|| `PLN` | 0x26 | 38 | `.plan` | Plan file, almost like a small level within a level, contains things, their properties, and how they are laid out, all poppet objects are plans.
|| `TXL` | 0x27 | 39 | `.yuv` | Texture list |
|| `MUS` | 0x28 | 40 | `.mus` | Music settings |
|| `MIX` | 0x29 | 41 | `.mix` | Mixer settings |
|| `REP` | 0x2A | 42 | `.rep` | Replay config |
|| `PAL` | 0x2B | 43 | `.pal` | Palette |
|| `SMH` | 0x2C | 44 | `.smh` | Static mesh |
|| `ATX` | 0x2E | 45 | `.atx` | Animated texture |
|| `VOP` | 0x2F | 46 | `.vop` | VOIP recording, responsible for all those terrible LBP movie audios |
|| `PIN` | 0x30 | 47 | `.pin` | Pin (self explanitory really) |
|| `INS` | 0x31 | 48 | `.rinst` | Instrument |
|| None | 0x32 | 49 | `.smp` | Sample |
|| `OFT` | 0x33 | 50 | `.oft` | Outfit list |
|| `PBR` | 0x34 | 51 | `.pbr` | Paint brush |
|| `REC` | 0x35 | 52 | `.rec` | Thing recording |
|| `PTG` | 0x36 | 53 | `.ptg` | Painting |
|| `QST` | 0x37 | 54 | `.qst` | Quest |
|| `ABK` | 0x38 | 55 | `.abnk` | Animation bank |
|| `AST` | 0x39 | 56 | `.aset` | Animation set |
|| `SMP` | 0x3A | 57 | `.smap` | Skeleton map |
|| `SRG` | 0x3B | 58 | `.sreg` | Skeleton registry |
|| `SAS` | 0x3C | 59 | `.sas` | Skeleton animation style |
|| None | 0x3D | 60 | `.cpv` | Crossplay Vita |
|| `CHK` | 0x3E | 61 | `.chk` | Streaming chunk |
|| `ADS` | 0x3F | 62 | `.ads` | Adventure shared data |
|| `ADP` | 0x40 | 63 | `.adp` | Adventure play profile |
|| `AMP` | 0x41 | 64 | `.amap` | Animation map |
|| `CCD` | 0x42 | 65 | `.ccd` | Cached costume data |
|| `DLA` | 0x43 | 66 | `.dla` | Data labels |
|| `ADM` | 0x44 | 67 | `.adm` | Adventure maps (plural) |