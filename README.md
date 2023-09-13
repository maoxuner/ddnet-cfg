# DDNet 配置及绑定

![](https://badgen.net/badge/愛/臺灣/blue)
![](https://badgen.net/badge/爱/中国/red)

## 简介

[English README](#introduction)

### 啥是 DDRaceNetwork/DDNet？

游戏！令人上头！[官网](https://ddnet.org/)

全平台，支持[Windows、Linux、MacOS](https://ddnet.org/downloads/)，甚至[安卓（废弃）](https://ddnet.org/downloads/#9.3)。通过 Steam 环境或者使用独立的二进制版本均可运行。

### 这是啥？

1. 动态游戏配置（由 DDNet 命令支持）
2. 好用的配置、绑定管理
3. 易于切换 Tee 名称（大佬小号装萌新）
4. 便利的游戏技能绑定

### 这玩意儿咋使？

### 安装

#### 下载代码

把该项目克隆到 DDNet 配置目录下 （比如 Linux 下的`~/.teewords`，同目录可能有配置文件`settings_ddnet.cfg`）。项目的目标目录必须是`configs`。

#### 备份 `settings_ddnet.cfg`

如果有`settings_ddnet.cfg`文件的话，备份一下以防万一。

#### 应用配置

1. 启动游戏
2. 按`F1`打开控制台
3. 在控制台输入`exec configs/reset.cfg`并回车。<br>
   注意：该操作会重置你的名称。

#### 游戏中使用绑定的快捷键

| 按键       | 说明                                   |
| ---------- | -------------------------------------- |
| `ctrl`+`r` | 重置配置（重置按键绑定，不会删除好友） |
| `ctrl`+`h` | 速飞开关                               |
| `ctrl`+`x` | 切分身时自动切锤开关                   |
| `t`        | 分身同步                               |
| `n`        | 技能菜单（逐个显示）                   |
| `m`        | 开关当前菜单显示的技能                 |

## 参考

[Just bind it](https://forum.ddnet.org/viewtopic.php?f=16&t=2537)

---

# DDNet Config/Binds

## Introduction

### What is DDRaceNetwork/DDNet?

It's an awesome game! [Official Website](https://ddnet.org/)

Available for all polular platforms. [Windows/Linux/MacOS](https://ddnet.org/downloads/), even [Android(deprecated)](https://ddnet.org/downloads/#9.3). Steam runtime or standalone binary version is ok.

### What is this project?

1. Dynamic configuration supported by DDNet command
2. Useful config/binds management
3. Easy switch of mutiple tee names
4. Convenient binds for advanced game skills

## How to use?

### Install

#### Download the code

Clone the project to DDNet settings directory (For example, `~/.teewords` on Linux, there maybe a settings file named `settings_ddnet.cfg`). Target directory of this project must be `configs`.

#### Backup `settings_ddnet.cfg`

If there is a `settings_ddnet.cfg` file, backup it, keep it safe.

#### Apply configuration

1. Start the game
2. Open console by pressing `F1`
3. Input `exec configs/reset.cfg` into the console, then press enter.<br>
   WARNING: THIS OPERATION WILL RESET YOUR TEE NAMES

#### Use key binds during game

| Key        | Description                                                 |
| ---------- | ----------------------------------------------------------- |
| `ctrl`+`r` | Reset config(unset all bindings, friends won't be clean up) |
| `ctrl`+`h` | Deep fly on/off                                             |
| `ctrl`+`x` | Hammer take on/off                                          |
| `t`        | Dummy copy moves                                            |
| `n`        | Menu(walk through skills)                                   |
| `m`        | Turn on/off the skill in current menu                       |

## References

[Just bind it](https://forum.ddnet.org/viewtopic.php?f=16&t=2537)
