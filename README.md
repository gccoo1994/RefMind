<p align="center">
  <img src="refmind_flutter/assets/icon/app_icon.png" width="120" alt="RefMind Logo">
</p>

<h1 align="center">RefMind</h1>

<p align="center">
  <strong>AI-Native Academic Research Assistant</strong><br>
  <em>从文献阅读到论文写作，一站式搞定。</em>
</p>

<p align="center">
  <a href="#-核心特性">核心特性</a> •
  <a href="#-为什么选择-refmind">为什么选择 RefMind</a> •
  <a href="#-快速开始">快速开始</a> •
  <a href="#-参与贡献">参与贡献</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/platform-Windows-blue" alt="Platform">
  <img src="https://img.shields.io/badge/version-1.0.1-green" alt="Version">
</p>

---

## 痛点

> 研究人员每天面对数十篇文献，手动整理 metadata、标注、笔记、写作引用……工具零散、流程割裂。

**RefMind 把文献管理、PDF 阅读、AI 辅助、笔记写作全部整合在一个桌面应用里。**

---

## 核心特性

### 1. 智能文献库管理

- **拖拽导入** PDF / Word / EPUB / CAJ 等主流格式
- **智能元数据提取** — AI 自动补全标题、作者、摘要、关键词
- **DOI / 链接直录** — 一行 DOI 自动抓取完整引用信息
- **批量操作** — 批量 AI 字段生成、批量重命名、批量导出
- **文件夹 + 项目** — 双层组织体系，文献可同时归属多个项目

### 2. 原生 PDF 阅读器

- **沉浸式阅读** — 双栏、单栏、连续滚动，支持多标签页
- **精准标注** — 高亮、下划线、文本注释、区域注释
- **选区即引用** — 选中文字一键创建溯源笔记，自动绑定页码与锚点
- **OCR 识别** — 支持多种 OCR 引擎，扫描件也能读
- **PDF 全文翻译** — AI 翻译 + 对照阅读，一键生成译文 PDF

### 3. AI 研究助手

| 功能 | 说明 |
|------|------|
| **对话式问答** | 基于 RAG 的文献问答，AI 会引用你库中的真实文献 |
| **文献综述生成** | 输入研究方向，AI 从你的文献库中综合分析并生成综述 |
| **智能字段提取** | 一键批量生成摘要、关键词、研究方法、创新点等结构化字段 |
| **选区翻译** | PDF 中划词即译，支持多语言互译 |
| **研究图表生成** | AI 辅助生成研究框架图、数据可视化 |

### 4. 研究笔记与写作

- **溯源笔记** — 从 PDF 选区直接创建，自动关联原文位置
- **文献笔记** — Markdown 富文本编辑，支持代码块、公式
- **写作工作台** — 支持分段撰写、引文插入、版本管理
- **引文回溯** — 从笔记一键跳转回原文 PDF 对应位置
- **导出格式** — 支持导出 Word、PDF、PPT

### 5. 研究看板

- **可视化研究图谱** — 将文献、笔记、问题节点以卡片形式自由连接
- **项目级 AI 导入** — AI 推荐相关文献并自动入库
- **多项目支持** — 按研究课题独立管理文献与笔记

### 6. 数据安全 & 同步

- **本地优先** — 所有数据存储在本地，你的文献永远在你手里
- **WebDAV 同步** — 支持坚果云、中国科技云数据胶囊、自定义 WebDAV
- **自动备份** — 支持手动/定时备份与恢复
- **敏感信息加密** — API Key 等使用系统级加密存储

---

## 为什么选择 RefMind

| 对比维度 | RefMind | Zotero | EndNote |
|----------|---------|--------|---------|
| AI 原生集成 | ✅ 对话问答 + RAG + 字段提取 | ❌ 需插件 | ❌ |
| 溯源笔记 → 引文回溯 | ✅ 全链路 | ⚠️ 部分 | ⚠️ 部分 |
| 本地优先 + 隐私 | ✅ 数据不离开本机 | ⚠️ 可选 | ❌ |
| 多引擎 OCR | ✅ 扫描件智能识别 | ❌ | ❌ |
| 研究看板 | ✅ 可视化图谱 | ❌ | ❌ |

---

## 快速开始

### 环境要求

- **Windows 10/11** (64-bit)

### 安装

> 详细安装指南即将上线。目前可通过源码构建运行：

```bash
git clone https://github.com/your-username/RefMind.git
cd RefMind/refmind_flutter
flutter pub get
flutter run -d windows
```

---

## 参与贡献

RefMind 仍处于活跃开发阶段，欢迎贡献！

1. Fork 本仓库
2. 创建特性分支 (`git checkout -b feature/amazing-feature`)
3. 提交更改 (`git commit -m 'Add amazing feature'`)
4. 推送到分支 (`git push origin feature/amazing-feature`)
5. 创建 Pull Request

---

## 路线图

- [ ] macOS 平台支持
- [ ] 更多 AI 模型接入
- [ ] 插件系统

---

<p align="center">
  <strong>RefMind</strong> — 让研究回归思考本身。<br>
  <em>Focus on research, not on tools.</em>
</p>
