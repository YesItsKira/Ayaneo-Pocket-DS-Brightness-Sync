# Ayaneo Pocket DS Brightness Mirror

A utility for the Ayaneo Pocket DS that mirrors brightness between the two screens so they match visually in real life.

The Pocket DS has two seperate brightness sliders for the top and bottom screens. They can have noticeable brightness differences. This app lets you sync the bottom screen brightness to the top screen by creating a calibrated comparison between the two.

## What does it do?
- Guides you through setup (Shizuku install / Ayaneo Root Scripts / permission grant)
- Lets you calibrate the bottom screen brightness at multiple points (0/25/50/75/100%)
- Uses those calibration points to interpolate the in-between values
- Mirrors brightness changes so both screens track together more accurately.

## Features
- **Step-by-step main screen flow** with live status checkmarks:
  1) Detect Shizuku + open Play Store if missing  
  2) Explain enabling Shizuku in root mode (through AYA Settings)  
  3) Grant Shizuku permission  
  4) Enable brightness mirroring  
  5) Calibrate (with explanation of why it matters)
- Calibration system at: 0%, 25%, 50%, 75%, 100%
- Interpolation between calibration points for smooth matching
- Calibration slider minimum of 1 so that you cant turn the screen off through brightness setting.

## Basic usage (App will walk you through this)
1. Install Shizuku (if you don’t already have it)
2. Start Shizuku in root mode (AYA Settings → Device → Root scripts)
3. Open the app and press **Grant Shizuku**
4. Press **Enable Mirroring**
5. Go to **Calibration**:
   - Manually set Android brightness to **0%, 25%, 50%, 75%, 100%**
   - For each one, use the app’s calibration slider until the screens match
   - Save each point, then press **Done**
6. After calibration, mirroring should track much more accurately

## Notes / limitations
- Calibration is **device-specific** and depends on your displays, ambient light, and personal perception.
- Best results come from calibrating in the lighting conditions you use most often.

