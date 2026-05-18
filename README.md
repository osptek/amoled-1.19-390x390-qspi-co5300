# 1.19 寸 390×390 AMOLED QSPI 模组（CO5300）资料与示例

**English：** [`README_EN.md`](README_EN.md)

---

> 本仓库提供该模组的 **示例工程**，以及数据手册、规格与接口说明等资料，便于选型参考与集成开发。

## 产品概要

| 项目 | 说明 |
|:--|:--|
| 模组规格 | 1.19 英寸 **AMOLED**，分辨率 **390×390** |
| 接口 | **QSPI** |
| 驱动芯片 | **CO5300** |
| 规格标识 | 产品资料中常用 **`1.19-amoled-390x390-qspi-co5300`** 表示本规格 |

---

## 仓库结构

### 顶层目录

| 路径 | 说明 |
|:--|:--|
| `docs/` | 数据手册、规格说明、接口与初始化相关文档 |
| `examples/` | 按功能分类的 **示例工程** |

### `examples/` 分类

| 分类 | 说明 |
|:--|:--|
| `examples/` 根目录 | 基于 **esp-lvgl-adapter** 的 **LVGL8 / LVGL9** 示例 |
| `with-te/` | 使用 **TE** 的显示同步与防撕裂相关示例 |

### 示例工程路径

#### 基础与 esp-lvgl-adapter

| 说明 | 路径 |
|:--|:--|
| esp-lvgl-adapter + LVGL8 | `examples/esp32s3-idf5_co5300-qspi_esp-lvgl-adapter_lvgl8/` |
| esp-lvgl-adapter + LVGL9 | `examples/esp32s3-idf5_co5300-qspi_esp-lvgl-adapter_lvgl9/` |

#### with-te

| 说明 | 路径 |
|:--|:--|
| esp-lvgl-adapter + LVGL8 + AMOLED，含 TE | `examples/with-te/esp32s3-idf5_co5300-qspi_esp-lvgl-adapter_lvgl8_amoled-with-te/` |
| esp-lvgl-adapter + LVGL9 + AMOLED，含 TE | `examples/with-te/esp32s3-idf5_co5300-qspi_esp-lvgl-adapter_lvgl9_amoled-with-te/` |
