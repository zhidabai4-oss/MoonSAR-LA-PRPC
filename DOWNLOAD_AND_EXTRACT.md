# Download and extract

Companion data and software for **Locally Adaptive Piecewise RPC Modeling for Lunar South Polar SAR Orthorectification**.

## Algorithm package

Download the algorithm ZIP from the software release, extract the complete archive, and run `RUN_EXAMPLES.bat` on Windows x64. Example datasets and the required supporting inputs are bundled.

## Mosaic product

Download **both** `MoonSAR_S1_mosaic_20261026.7z.001` and `MoonSAR_S1_mosaic_20261026.7z.002` into the same folder. Open `.001` with 7-Zip and extract it. Do not extract `.002` separately. The extracted folder contains `S1_mosaic.tif`, supporting rasters, metadata, and per-file checksums.

Verify the downloaded assets against `SHA256SUMS.txt`. The checksum list inside the mosaic folder verifies its individual files.

## 中文

算法 ZIP 完整解压后运行 `RUN_EXAMPLES.bat`。镶嵌产品的 `.001` 和 `.002` 分卷必须下载到同一目录，用 7-Zip 打开 `.001` 并解压。下载校验清单用于核对文件完整性，数据包内的校验清单用于核对解压后的文件。
