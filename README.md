# Hollow-Knight-Game
# 简化版《空洞骑士》游戏

> 大一下高级语言程序设计课程设计，独立完成的一款 2D 横版动作游戏

## 项目背景

- **课程**：高级语言程序设计
- **学校**：北京工业大学
- **时间**：2025.03 - 2025.05

## 游戏功能

- 玩家角色移动（WASD）与攻击（K键）
- 两种敌人类型：近战型 + 远程子弹型
- 盾牌道具：可抵挡一次攻击
- 多关卡设计（2关）
- 计时系统与得分系统
- 用户登录/注册（文件存储）
- 排行榜排序与展示
- 背景音乐与胜利音效

## 技术栈

- **语言**：C语言
- **图形库**：EasyX
- **数据结构**：链表（动态管理敌人和子弹）
- **文件I/O**：用户信息存储与读取

## 如何运行

1. 安装 Visual Studio + EasyX 图形库
2. 打开工程文件，编译运行
3. 注册账号后即可开始游戏

## 代码结构
├── main.c # 主函数、游戏主循环
├── login.c # 登录注册模块
├── game_level1.c # 第一关逻辑
├── game_level2.c # 第二关逻辑
├── enemy.c # 敌人链表管理
├── bullet.c # 子弹链表管理
├── ranking.c # 排行榜模块
└── images/ # 图片资源文件夹

## 项目截图

<img width="1793" height="1078" alt="image" src="https://github.com/user-attachments/assets/ccb98661-6eb5-489d-8a81-bc263374443b" />
<img width="690" height="552" alt="image" src="https://github.com/user-attachments/assets/a33e68b9-fefd-45e3-9199-ac1a60eabf0c" />



## 实验报告

见仓库中的 `高级语言程序设计课设报告_李萌.pdf`
