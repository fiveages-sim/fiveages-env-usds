# FiveAges Env

面向 **Isaac Sim / 机器人仿真** 的环境与任务 USD 资产库，用于搭建桌面、货架、背景与各类任务场景。

## 仓库结构（简要）

| 目录 | 说明 |
|------|------|
| `static/` | 静态场景部件：桌子（如光学桌、圆桌）、箱子、货架等 |
| `moveable/` | 可移动物体：水果、药品等小物体资产 |
| `articulation/` | 关节/可动机构（如抽屉等） |
| `background/` | 环境与背景（如网格房间等） |
| `tasks/` | 按任务组织的组合场景（如桌面抓取、双臂抬箱、推块等） |

具体子目录与 `.usd` 文件可直接在仓库中浏览；任务场景通常引用 `static/`、`moveable/` 等路径下的资产。

## 资产来源与致谢

部分资产来自外部项目或官网分发，本仓库内路径与来源如下（便于核对许可与引用）：

| 本仓库路径 / 资产类型 | 来源 | 说明 |
|----------------------|----------|------|
| `moveable/fruits/` 等水果相关 USD | [Galaxea_Lab](https://github.com/userguide-galaxea/galaxea_lab) | `userguide-galaxea/galaxea_lab` |
| `articulation/drawer/` 等抽屉相关资产 | [Lightwheel · LeRobot Assets](https://lightwheel.ai/assets-type-content?type=LeRobotAssets) | 自 Lightwheel 官网「LeRobot Assets」等类别中下载（含 Kitchen 等可交互场景部件） |
