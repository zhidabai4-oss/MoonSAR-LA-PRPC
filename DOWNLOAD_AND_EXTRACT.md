# Download and extract

## Algorithm package
Download `LA_PRPC_Paper_Package_Win64_2Examples_20261022.zip`, extract the complete archive, and run `RUN_EXAMPLES.bat` on Windows x64. The two example scenes and required supporting inputs are bundled.

## Mosaic product
Download **both** `MoonSAR_S1_mosaic_20261026.7z.001` and `MoonSAR_S1_mosaic_20261026.7z.002` into the same folder. Open the `.001` file with 7-Zip and extract it. Do not try to extract `.002` separately. The reconstructed folder contains the original `S1_mosaic.tif`, supporting rasters, metadata and per-file checksums. No raster values or georeferencing are changed by packaging.

Verify the downloaded assets against `SHA256SUMS.txt`. After extraction, a second checksum list inside the mosaic folder verifies its individual files.

## 中文
算法 ZIP 完整解压后运行 `RUN_EXAMPLES.bat`。镶嵌产品的 `.001` 和 `.002` 两卷必须下载到同一目录，用 7-Zip 打开 `.001` 并解压，不能单独解压第二卷。解压后得到原始 TIFF 及配套说明；分卷仅用于满足下载附件大小限制，不改变影像内容。
