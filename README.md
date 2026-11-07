> ⚠️ **本仓库内容已完整合并进 [cpp-oi-roadmap](https://github.com/Peter1384345/cpp-oi-roadmap)** 的 `codequest/` 目录（逐字节一致，仅少 LICENSE/README 两个仓库元数据文件）。cpp-oi-roadmap = C++ OI 学习路线图 + CodeQuest 平台二合一。本仓库 Pages 暂保留在线，后续更新请前往主仓库。
>
# CodeQuest C++ 竞赛学习平台

> C++ 信息学竞赛一体化学习平台 · 课程 + 练习 + 路线图 + 仪表盘

![License](https://img.shields.io/badge/license-MIT-blue)
![Status](https://img.shields.io/badge/status-active-brightgreen)
![Stars](https://img.shields.io/github/stars/Peter1384345/codequest-cpp?style=flat)

## 项目简介

CodeQuest 是一个面向 C++ 信息学竞赛学习者的综合学习平台，整合了系统课程、练习中心、可视化路线图和学习仪表盘，帮助学习者从零基础高效进阶到 CSP-J / CSP-S 水平。

## 在线访问

**GitHub Pages:** https://peter1384345.github.io/codequest-cpp/

## 平台组成

### 新版学习平台 (cpp-olympiad-site/)

| 页面 | 路径 | 功能 |
|------|------|------|
| 课程首页 | index.html | 平台入口与课程介绍 |
| 学习路径 | path.html | 28 天 CSP-J 系统学习路径 |
| 练习中心 | practice.html | 分章节练习题与评测 |
| 学习仪表盘 | dashboard.html | 学习进度可视化统计 |
| 课程详情 | course.html | 单课程详细内容 |

### 可视化路线图 (cpp-olympiad-roadmap/)

- CSP-J → CSP-S → NOIP 四阶段路线图
- 每阶段学习目标、核心知识点、配套书籍
- 动态粒子网络背景，科技感十足

### 旧版网站 (cpp-olympiad-site/old/)

保留旧版学习网站，兼容历史访问。

## 功能亮点

- 🎯 **28 天 CSP-J 系统课程** — 从零基础到竞赛入门的完整路径
- 📝 **练习中心** — 分章节题库，即时反馈与解析
- 📊 **学习仪表盘** — 进度统计、正确率分析、学习曲线
- 🗺️ **可视化路线图** — 清晰的学习阶段划分与进阶路径
- 🎨 **科技感界面** — 暗色主题、霓虹渐变、粒子特效

## 项目结构

`
codequest-cpp/
├── index.html                        # 入口页（跳转到新版平台）
├── checkin_sections.html             # 签到章节页
├── cpp-olympiad-site/                # 新版学习平台
│   ├── index.html                    # 课程首页
│   ├── path.html                     # 学习路径
│   ├── practice.html                 # 练习中心
│   ├── dashboard.html                # 学习仪表盘
│   ├── course.html                   # 课程详情
│   ├── old/                          # 旧版网站
│   ├── _shared/                      # 共享资源
│   └── assets/                       # 静态资源
└── cpp-olympiad-roadmap/             # 竞赛路线图
    └── cpp-olympiad-roadmap.html     # 路线图页面
`

## 本地预览

`ash
# 任意静态服务器，例如：
npx serve .
# 然后访问 http://localhost:3000
`

或直接用浏览器打开 cpp-olympiad-site/index.html。

## 相关项目

- [cpp-oi-roadmap](https://github.com/Peter1384345/cpp-oi-roadmap) — C++ OI 学习路线图（独立部署版）

## License

[MIT](LICENSE)