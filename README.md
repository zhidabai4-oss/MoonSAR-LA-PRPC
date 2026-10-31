# MoonSAR: LA-PRPC algorithm program and Mini-RF S1 mosaic

Companion resources for locally adaptive piecewise RPC modeling and lunar SAR orthorectification. Large downloads are distributed through **Releases**, separately from this documentation repository.

## Downloads

- [Algorithm program with two examples](https://github.com/zhidabai4-oss/MoonSAR-LA-PRPC/releases/tag/software-20261022)
- [354-scene S1 mosaic](https://github.com/zhidabai4-oss/MoonSAR-LA-PRPC/releases/tag/mosaic-20261026)

- **Software, build 2026-10-22:** Windows x64 algorithm package with two runnable Mini-RF examples, their info/EO files and a LOLA DEM subset. Scene IDs: `lsz_00769_1cd_xku_86s346_v1` and `lsz_03737_1cd_xku_90s137_v1`. Extract the original ZIP and run `RUN_EXAMPLES.bat`.
- **Mosaic, product 2026-10-26:** 30 m Mini-RF S1 mosaic made from 354 retained scene products after 14 exclusions from 368 available inputs. Download both 7z volumes and extract `.001` with 7-Zip. The release includes pixel source IDs, coverage counts, scene inventories and a new-gap mask. This download does not contain all 369 individual orthoproducts from the manuscript.

The mosaic uses lunar south-polar stereographic coordinates. It preserves selected source values and includes no radiometric normalization or feathering. Coverage gaps are retained. Product details and source identifiers are documented in the archive.

Checksums and bilingual extraction instructions accompany the releases. The software and mosaic retain their original build/product dates; the GitHub publication date is distinct. No project-specific reuse license has been specified.

Paper authors: Zhida Bai, Yuming Xiang, Doudou Hu, Shijie Liu, Jinyang Chen, Huan Xie, and Xiaohua Tong (Tongji University).

See [中文说明](README_zh.md).
