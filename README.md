# Wan-VisualPro-Skills

<div align="center">

![Logo](https://img.shields.io/badge/AI-Wan2.7%20Image-blue) ![License](https://img.shields.io/badge/License-MIT-green) ![Platform](https://img.shields.io/badge/Platform-OpenClaw-orange)

**Professional Image Enhancement Skills for Tongyi Wan2.7-Image Model**

*将普通图片转化为视觉中国级商业影像的 AI 技能套件*

[English](#english) | [中文说明](#中文说明)

</div>

---

## 🎯 项目简介 | Project Overview

这两个 Skill 能够调用**通义万相 Wan2.7-Image** 模型，将普通手机或相机拍摄的原始图片，转化为具有**极高商业价值**的图库级影像作品。

These two Skills leverage the **Tongyi Wan2.7-Image** model to transform ordinary photos into commercially valuable, stock-photo-grade professional images.

---

## ✨ 核心特性 | Key Features

| 特性 | 标准版 Standard | 灵活版 Modular |
|------|-----------------|---------------|
| **场景预设** | 6大商业场景 | 12大行业场景 |
| **交互方式** | 一键出片 | 智能定制 |
| **渲染引擎** | 4大固定模块 | 4大可组合引擎 |
| **适用用户** | 非专业/批量处理 | 专业创作者 |
| **输出变体** | 单张成品 | 4变体对比 |

---

## 📦 Skill 列表 | Skills Inventory

### 1. 视觉中国级影像优化-标准版 | Visual China Pro - Standard

```
skills/visual-china-pro-standard/
└── SKILL.md
```

**核心能力：**
- 6大商业场景预设（电商主图/品牌海报/社交封面/产品白底/人像修图/创意合成）
- 4维质量评估体系
- 标准化 API 调用协议

**适用场景：** 快速出片、批量处理、电商主图、品牌宣传

**Quick Start:**
```
上传图片 → 选择场景 → 自动渲染 → 获得成品
```

---

### 2. 视觉中国级影像优化-模块化灵活版 | Visual China Pro - Modular

```
skills/visual-china-pro-modular/
└── SKILL.md
```

**核心能力：**
- 12大行业场景（时尚美妆/美食餐饮/旅行风光/电商产品/品牌营销/企业形象/地产建筑/人像写真/汽车机械/珠宝钟表/医疗器械/生活方式）
- 4大渲染引擎（光影/色彩/质感/构图）
- 智能参数推荐系统
- 4变体生成对比

**适用场景：** 个性化创作、专业修图、品牌定制、艺术摄影

**Quick Start:**
```
描述创作意图 → 智能推荐配置 → 参数微调 → 生成4变体 → 选择最优 → 精修交付
```

---

## 🚀 快速开始 | Quick Start

### 前置要求 | Prerequisites

- OpenClaw 智能助手
- 通义万相 Wan2.7-Image 模型访问权限

### 安装步骤 | Installation

**方法一：复制文件**
```bash
# 将 SKILL.md 文件内容复制到 OpenClaw 的 skills 目录
# Windows: %USERPROFILE%\.qclaw\workspace\skills\
# macOS: ~/.qclaw/workspace/skills/
```

**方法二：通过命令安装**
```bash
npx skills add your-username/Wan-VisualPro-Skills -g -y
```

### 使用方法 | Usage

1. 在 OpenClaw 中加载对应 Skill
2. 上传需要优化的图片
3. 选择场景或描述创作意图
4. 等待 AI 生成专业级成品

---

## 📊 场景覆盖 | Scene Coverage

| 类别 | 场景 | 编号 |
|------|------|------|
| **电商零售** | 电商主图 | S1 |
| **品牌营销** | 品牌海报 | S2 |
| **社交媒体** | 社交封面 | S3 |
| **产品展示** | 产品白底 | S4 |
| **人像摄影** | 商业人像 | S5 |
| **创意设计** | 创意合成 | S6 |
| **时尚美妆** | 时尚美妆 | C1 |
| **餐饮美食** | 美食餐饮 | C2 |
| **旅行风光** | 旅行风光 | C3 |
| **生活方式** | 生活方式 | C4 |
| **企业形象** | 企业形象 | B3 |
| **专业领域** | 人像/汽车/珠宝/医疗 | P1-P4 |

---

## 🎨 渲染引擎参数 | Rendering Engine Parameters

### 光影引擎 | Lighting Engine

| 方案 | 色温 | 光质 | 适用场景 |
|------|------|------|---------|
| A1 自然纪实 | 4500K-5500K | 柔和散射 | 人文纪实 |
| A2 电影戏剧 | 1:4+光比 | 硬+柔组合 | 品牌故事 |
| A3 商业通透 | 1:1.5-1:2 | 三点布光 | 产品白底 |
| A4 创意氛围 | 彩色光源 | 霓虹/烛光 | 创意海报 |
| A5 黄金时刻 | 2800K-3200K | 低角暖光 | 婚纱摄影 |
| A6 蓝调时刻 | 6500K-9000K | 天空散射 | 夜景人像 |

### 色彩引擎 | Color Engine

| 方案 | 特征 | HEX 示例 |
|------|------|---------|
| B1 莫兰迪 | 低饱和高级灰 | #B8C4C8 |
| B2 青橙色调 | 电影感强对比 | #E8A87C |
| B3 商业中性灰 | 标准商业色 | RGB中性 |
| B4 复古胶片 | 富士/柯达风格 | 品红偏移 |
| B5 国潮中国风 | 红金配色 | #C41E3A |
| B6 马卡龙 | 甜美梦幻 | 饱和+40% |
| B7 赛博朋克 | 霓虹青粉 | #00F0FF |
| B8 参考提取 | 智能配色 | 自动提取 |

---

## 📋 质量评估 | Quality Assessment

### 4维评分体系 | 4-Dimensional Rating

| 维度 | 权重 | 评估指标 |
|------|------|---------|
| 商业传达力 | 30% | 主体突出度、品牌调性 |
| 视觉冲击力 | 30% | 光影张力、色彩吸引力 |
| 技术完成度 | 25% | 分辨率、细节完整度 |
| 创新性 | 15% | 场景独特性、记忆点 |

### 评级标准 | Rating Standards

| 评级 | 分数 | 建议 |
|------|------|------|
| A+ | 4.5-5.0 | 直接商用/图库销售 |
| A | 4.0-4.4 | 微调后商用 |
| B | 3.5-3.9 | 针对性优化 |
| C | 3.0-3.4 | 建议更换方案 |
| D | <3.0 | 重新设计 |

---

## 🔌 API 调用示例 | API Call Example

```json
{
  "model": "wanx2.7-image",
  "prompt": "[完整Prompt - 根据Skill生成的优化指令]",
  "negative_prompt": "blurry, low quality, watermark, text, logo, trademark, deformed, bad anatomy, oversaturated, plastic skin",
  "aspect_ratio": "1:1",
  "resolution": 1024,
  "style_preset": "commercial_photography",
  "quality": "hd"
}
```

---

## 📄 许可证 | License

本项目采用 **MIT 许可证**。

This project is licensed under the **MIT License**.

```
MIT License

Copyright (c) 2026 Wan-VisualPro-Skills

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND.
```

---

## 🤝 贡献指南 | Contributing

欢迎提交 Issue 和 Pull Request！

Welcome to submit Issues and Pull Requests!

1. Fork 本仓库
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 创建 Pull Request

---

## 📞 联系作者 | Contact

- **Author:** 杜宇峰
- **Email:** [your-email@example.com]
- **GitHub:** [https://github.com/your-username]

---

## 🙏 致谢 | Acknowledgments

- [通义万相 Wan2.7-Image](https://tongyi.aliyun.com/) - AI 图像生成模型
- [OpenClaw](https://openclaw.ai/) - 智能助手框架
- 所有贡献者的支持

---

<div align="center">

**如果这个项目对你有帮助，请给我们一个 ⭐**

**If this project is helpful to you, please give us a ⭐**

</div>
