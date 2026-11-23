# Auto CMYK Studio

Starter Android project for approximate CMYK halftone film separation.

## Current features
- Import an image
- Generate C, M, Y, K black-and-white halftone PNG plates
- Adjustable LPI (10–150)
- Separate default screen angles for each plate
- Saves outputs to Pictures/AutoCMYKStudio

## Limitations
This is a starter implementation. RGB-to-CMYK conversion is approximate. It does not yet include calibrated color management, physical print-size/DPI controls, registration marks, or PDF export. Test output films before production.

## Build
Requires Android SDK and Gradle 8.9. Run `gradle :app:assembleDebug` from this directory.
