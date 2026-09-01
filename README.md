# 3D Printing

自动化称重系统相关 3D 打印文件，包含打印模型、切片文件，以及少量 STEP 交换格式。

## 本地目录对应关系

- 本仓库对应本地目录：`F:\SW\3D`

## 更新说明

- 更新修改了旧版文件

## 文件类型

| 格式 | 说明 |
|------|------|
| `.3mf` | 3D 打印模型（可直接导入切片软件） |
| `.gcode.3mf` | 已切片的打印任务（含打印参数） |
| `.STL` | 三角网格，通用打印格式 |
| `.STEP` | CAD 交换格式，可用 SolidWorks 等软件打开 |

## 主要打印件

**料斗与称重**

- `料斗1.3mf` / `chengzhongliaodou1.3MF` / `hopper(2).3mf` — 料斗
- `liaodou1.gcode.3mf` / `weigh1.gcode.3mf` / `hopper(3)_planter.gcode.3mf` — 料斗切片件

**盖板与连接件**

- `gaiban1.3mf` / `盖板Duzhaoyang.3MF` / `盖板Duzhaoyang2.3mf` — 盖板
- `底板连接件Du.3mf` / `2.底板连接件Du.3mf` / `3.底板连接件Du.3mf` — 底板连接件
- `45°直角支架.3mf` / `直角架4.3mf` — 支架

**螺旋落料**

- `luoxuan80.3MF` / `luoxuan90mm1.3mf` / `luoxuan90mm2.3mf` — 螺旋
- `可拆卸式螺旋4Du.3mf` / `可拆卸式螺旋4Du.STL` — 可拆卸式螺旋

**机械臂与其他**

- `机械臂2.STL` / `机械臂2(1).3mf` / `机械臂2(2).3mf` — 机械臂相关件
- `电磁铁.3mf` / `电磁铁.STL` — 电磁铁
- `杯.STEP` / `盖.STEP` / `轨道改.STEP` — STEP 交换文件

## 使用说明

1. 模型文件（`.3mf` / `.STL`）可用 Bambu Studio、OrcaSlicer、Cura 等切片软件打开。
2. `.gcode.3mf` 为已切片文件，可直接发送到对应打印机（请确认机型与材料参数是否匹配）。
3. `.STEP` 可用 SolidWorks、Fusion 360 等 CAD 软件打开后重新导出打印网格。
