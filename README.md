# HTZ Trainer — HumanitZ 内置修改器 v2.3

HumanitZ（UE4.27 僵尸生存）**单机离线**内置修改器，基于 UE4SS 注入框架，悬浮菜单式操作，不修改游戏本体文件。

## ⬇ 下载（v2.3，约 5.6 MB）

| 线路 | 链接 |
|---|---|
| 🚀 推荐（jsDelivr 加速） | https://fastly.jsdelivr.net/gh/qinchuanzhang8-sketch/HTZTrainer@main/HTZTrainer_v2.3.zip |
| 备用① （jsDelivr 节点2） | https://gcore.jsdelivr.net/gh/qinchuanzhang8-sketch/HTZTrainer@main/HTZTrainer_v2.3.zip |
| 备用② （gh-proxy 反代） | https://gh-proxy.com/https://raw.githubusercontent.com/qinchuanzhang8-sketch/HTZTrainer/main/HTZTrainer_v2.3.zip |
| 备用③ （GitHub 直连） | 本仓库点击 `HTZTrainer_v2.3.zip` → 右上 Download |

> 某条线路慢或打不开时，请依次换下一条；文件完全一致（可校验 md5 `ca90ae1d7ffab1297cb9e2fc7539aef4`）。

## 功能一览

- **状态锁定**：锁血(上帝)/饥饿/口渴/耐力/感染/体温/电量，附加消耗速率归零，一键全锁
- **物品生成**：736 种游戏物品全量可刷（逐项经游戏数据表验证的真实代码，含 7.62/抗生素/感染药剂等），10大类分类 + 列表内打字搜索（字母/数字），可输数量 1~200
- **车辆生成**：38 种可驾驶车辆（吉普/皮卡/SUV/警车/装甲车/房车…），生成在面前
- **僵尸生成**：33 种（调试中）
- **世界控制**：时间/天气/移动速度 1x~5x
- **一键补满** / 状态面板 / 调试转储

## 安装（3 步）

1. 把解压出的 `HTZ修改器_v2.3` 文件夹整个放到**游戏根目录**（与 `HumanitZ` 文件夹同级）
2. 双击运行 `一键安装.bat`，等待“安装成功”
3. 启动游戏进入存档，按 **F1 或 小键盘1** 打开菜单

## 按键

- 进入/确认：`小键盘+` 或 `=` ｜ 返回/退出：`小键盘-` 或 `-`
- 快捷：小键盘 1~9 与 F1~F9 完全等效（1菜单 2上帝 3补满 4全锁 5物品 6僵尸 7世界 8面板 9转储）
- 菜单内：↑↓选择  ←→调整  PgUp/PgDn翻页  直接打字搜索物品

## 常见问题

- **双击原启动器无反应**：新版 Windows 的“智能应用控制”可能拦截原启动器，改用游戏根目录 `HumanitZ.exe` 或本包 `启动游戏.bat` 启动
- **游戏自带快捷栏/状态栏消失**：这是游戏自带的 HUD 显示开关被按到，其按键是 `Backspace`，再按一次即恢复
- **偶发闪退**：经对照实验（不加载修改器长时间运行）确认与修改器无关，为注入框架与游戏本体兼容性问题，不影响存档，重进即可

## 声明

仅限**单人离线模式**使用，请勿在联机服务器中使用。所有数据本地处理，无联网行为。
