# LUT Pack — Installation Guide

## DaVinci Resolve (Recommended)

1. Open DaVinci Resolve
2. Go to the **Color** page
3. In the **LUTs** panel (left side), right-click anywhere
4. Select **"Open LUT Folder"** — a File Explorer window opens
5. Copy all subfolders from this pack into that folder
6. Back in Resolve: right-click the LUTs panel → **"Refresh"**
7. The LUT pack appears organized by category

**Applying a LUT:**
- Drag any LUT onto a node in the node tree
- Or right-click a node → "LUTs" → browse your installed packs
- Adjust the **Key Output Gain** to blend the LUT strength (0.5–0.8 recommended start)

## Adobe Premiere Pro

1. In the **Lumetri Color** panel, go to the **Creative** tab
2. Click the **Look** dropdown → click **Browse...**
3. Navigate to any `.cube` file
4. Apply — adjust the **Intensity** slider

**For batch application:**
Create a Lumetri preset with your chosen LUT applied, then use **Edit → Paste Attributes** across clips.

## After Effects

1. Apply the **Lumetri Color** effect to your footage layer
2. In **Creative → Look**, click Browse and select a `.cube` file
3. Adjust Intensity

## Final Cut Pro

1. Add the **Custom LUT** effect to your clip (found in Effects browser → Color)
2. In the Inspector, click the **LUT** dropdown → **Choose Custom LUT**
3. Select your `.cube` file
4. Adjust the **Mix** slider

## OBS Studio (for stream color grading)

1. Add a **Color Correction** filter to your scene/source
2. Under **LUT**, click Browse and select a `.cube` file
3. Adjust **LUT Amount**

## Default LUT Folder Paths

```
DaVinci Resolve:
  Windows: C:\ProgramData\Blackmagic Design\DaVinci Resolve\Support\LUT\
  Mac:     /Library/Application Support/Blackmagic Design/DaVinci Resolve/LUT/

Premiere Pro:
  Windows: C:\Program Files\Adobe\Common\LUTs\
  Mac:     /Library/Application Support/Adobe/Common/LUTs/
```
