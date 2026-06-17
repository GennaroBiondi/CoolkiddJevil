# Coolkidd Jevil Deltarune

Replaces Jevil with Coolkidd in Deltarune Chapter 1.

## Installation

### Requirements
- A legitimate copy of [Deltarune Chapter 1](https://www.deltarune.com/)
- [DeltaPatcher](https://github.com/marco-calautti/DeltaPatcher) (or any xdelta3 patcher)

### Steps
1. Download [DeltaPatcher](https://github.com/marco-calautti/DeltaPatcher/releases)
2. Launch DeltaPatcher
3. Set **Original File** to your Deltarune Chapter 1 `data.win`:
   - Steam: `Steam\steamapps\common\DELTARUNE\chapter1_windows\data.win`
   - Itch.io: `DELTARUNE Chapter 1\data.win`
4. Set **Patch File** to `coolkidd_jevil.xdelta`
5. Click **Apply Patch**
6. Copy the `Coolkidd/`, `lang/`, `mus/` and `Sounds/` folders into your Deltarune directory (next to `data.win`). For `mus/`, first copy the original files from your Deltarune install, then overwrite with the ones from this mod.

### Important
- Back up your original `data.win` before patching
- This mod only works with **Chapter 1**

### What's included
- `coolkidd_jevil.xdelta` - patches `data.win` to load Coolkidd sprites
- `Coolkidd/` - custom sprites and textures
- `lang/lang_en.json` - custom dialogue
- `mus/joker.ogg` - custom battle theme (replaces THE WORLD REVOLVING)
- `Sounds/joker*.wav` - custom voice lines
