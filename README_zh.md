# MoonSAR：LA-PRPC 算法程序与 Mini-RF S1 镶嵌产品

本仓库提供论文配套资源说明，完整下载文件位于 **Releases**。

- [算法程序及两景测试数据](https://github.com/zhidabai4-oss/MoonSAR-LA-PRPC/releases/tag/software-20261022)
- [354景 S1 镶嵌产品](https://github.com/zhidabai4-oss/MoonSAR-LA-PRPC/releases/tag/mosaic-20261026)

- **算法程序（2026-10-22构建）**：Windows 64位程序与两景可运行的 Mini-RF 示例，包含四波段 CUB、info/EO 和 LOLA DEM 子集。示例为 `lsz_00769_1cd_xku_86s346_v1`、`lsz_03737_1cd_xku_90s137_v1`。原 ZIP 完整解压后运行 `RUN_EXAMPLES.bat`。
- **镶嵌产品（2026-10-26生成）**：30 m 网格的 Mini-RF S1 镶嵌，从368景可用输入中排除14景，保留354景。附像元来源、覆盖次数、景清单和新增缺口掩膜。下载两卷7z文件到同一目录，使用7-Zip打开 `.001` 解压。本下载不包含论文全部369景单景正射产品。

镶嵌使用月球南极立体投影，保留选中来源的像元值，未进行辐射归一化、羽化或缺口插补。分卷仅为满足附件大小限制，不改变原始影像或坐标信息。每项发布附校验值与解压说明；具体处理信息见数据包内说明。

算法和产品沿用原构建日期、生成日期，区别于GitHub发布日期。目前未指定项目级复用许可。

论文作者：Zhida Bai、Yuming Xiang、Doudou Hu、Shijie Liu、Jinyang Chen、Huan Xie、Xiaohua Tong（同济大学）。
