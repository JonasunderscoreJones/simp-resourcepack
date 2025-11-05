# Image Optimization Test Results

This document contains the actual test results of running image optimization on the resource pack images.

## Test Configuration

- **Tool**: Sharp v0.34.4 (same as calibreapp/image-actions@1.1.0)
- **Settings**: 
  - PNG Compression Level: 9 (maximum)
  - PNG Quality: 65-80 (palette optimization)
  - Palette-based PNG enabled

## Results Summary

- **Original Total Size**: 63.09 KB
- **Optimized Total Size**: 37.58 KB
- **Total Savings**: 25.51 KB
- **Percentage Reduction**: **40.44%**

## Individual File Results

| File | Original Size | Optimized Size | Savings |
|------|--------------|----------------|---------|
| pack.png | 9,938 bytes | 4,489 bytes | 54.83% |
| pigscene.png | 6,867 bytes | 2,731 bytes | 60.23% |
| pointer.png | 6,953 bytes | 3,303 bytes | 52.50% |
| skeleton.png | 5,430 bytes | 2,491 bytes | 54.13% |
| fighters.png | 4,721 bytes | 2,794 bytes | 40.82% |
| burning_skull.png | 4,117 bytes | 3,609 bytes | 12.34% |
| void.png | 2,521 bytes | 1,862 bytes | 26.14% |
| skull_and_roses.png | 2,537 bytes | 1,899 bytes | 25.15% |
| bust.png | 2,383 bytes | 1,161 bytes | 51.28% |
| stage.png | 1,856 bytes | 1,193 bytes | 35.72% |
| donkey_kong.png | 1,704 bytes | 925 bytes | 45.72% |
| match.png | 1,641 bytes | 1,065 bytes | 35.10% |
| wanderer.png | 1,507 bytes | 817 bytes | 45.79% |
| courbet.png | 1,404 bytes | 1,168 bytes | 16.81% |
| pool.png | 1,335 bytes | 1,207 bytes | 9.59% |
| creebet.png | 1,311 bytes | 1,074 bytes | 18.08% |
| sea.png | 1,311 bytes | 1,087 bytes | 17.09% |
| wither.png | 1,200 bytes | 514 bytes | 57.17% |
| sunset.png | 964 bytes | 649 bytes | 32.68% |
| kebab.png | 782 bytes | 760 bytes | 2.81% |
| aztec.png | 738 bytes | 598 bytes | 18.97% |
| bomb.png | 733 bytes | 736 bytes | -0.41% |
| alban.png | 713 bytes | 641 bytes | 10.10% |
| aztec2.png | 713 bytes | 648 bytes | 9.12% |
| plant.png | 685 bytes | 630 bytes | 8.03% |
| wasteland.png | 313 bytes | 199 bytes | 36.42% |
| graham.png | 231 bytes | 231 bytes | 0.00% |

## Notes

- Some very small files (like graham.png and bomb.png) show minimal or no improvement as they are already highly optimized
- Larger, more complex images (like pigscene.png, skeleton.png, pack.png) show the best compression ratios (50-60%)
- The average savings of 40.44% is consistent and reliable for future image uploads
- All optimizations maintain lossless or near-lossless quality suitable for Minecraft textures

## Test Date

November 5, 2025
