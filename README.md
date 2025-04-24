# 🚀 XIK的AI实验室

<div align="center">
  <img src="https://raw.githubusercontent.com/vimalverma558/vimalverma558/master/img/hello.gif" width="20%">
  <h3>专注于大模型与检索增强生成(RAG)的研究与应用</h3>
</div>

<p align="center">
  <img src="https://img.shields.io/badge/LLM-专家-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/RAG-研究者-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Transformer-工程师-orange?style=for-the-badge" />
</p>

## 🧠 Transformer架构

<div align="center">
<img src="./images/transformer.png" alt="Attention Is All You Need论文首页" width="80%" />
<p><i>👆 "Attention Is All You Need" - Transformer架构奠基论文</i></p>
</div>

<details>
<summary><b>🔍 点击展开Transformer详细结构说明</b></summary>

### Transformer架构核心组件

1. **输入嵌入 (Input Embedding)**：将输入token转换为向量表示
2. **位置编码 (Positional Encoding)**：为序列中的每个位置添加位置信息
3. **多头注意力机制 (Multi-Head Attention)**：
   - 查询(Query)、键(Key)、值(Value)三个映射矩阵
   - 并行计算多个注意力"头"，捕获不同角度的信息
4. **前馈神经网络 (Feed Forward Network)**：由两个线性变换和ReLU激活函数组成
5. **Add & Norm**：残差连接和层归一化，保证训练稳定性
6. **编码器-解码器结构**：用于序列到序列任务

</details>

## 🔥 核心技术栈

```mermaid
graph TD
    A[大语言模型] --> B[Transformer架构优化]
    A --> C[RAG技术]
    B --> D[注意力机制改进]
    B --> E[长文本处理]
    C --> F[知识图谱增强]
    C --> G[语义检索]
    C --> H[上下文工程]
    I[应用开发] --> J[Vue+FastAPI]
    I --> K[轻量级部署]
    L[领域应用] --> M[智能问答]
    L --> N[知识管理]
```

## 📚 主要项目

### [AI China Town: 斯坦福小镇中国版](https://github.com/xkj0127/ai_china_town)

<div align="center">
  <img src="https://user-images.githubusercontent.com/68011645/89026666-ad233a80-d35b-11ea-9f4b-d3fe26ae12cb.png" width="60%" />
</div>

**AI China Town** 是斯坦福小镇的中国本地化版本，特点包括：
- 使用本地模型部署，无需联网
- 提示工程中文化，适应中文语境
- 简化流程，降低使用门槛
- 优化中文环境下的智能体交互体验

### [QALite: 智能问答笔记系统](https://github.com/xkj0127/QAlite)

<div align="center">
  <img src="https://raw.githubusercontent.com/xkj0127/QAlite/main/mdimg/be789a5a-e2cd-4468-8164-720bfa13abfc.png" width="45%" />
  <img src="https://raw.githubusercontent.com/xkj0127/QAlite/main/mdimg/c0774ffd-013b-475b-8a78-4909082f89a8.png" width="45%" />
</div>

**QALite** 是一个轻量级的问答笔记应用，使用Vue 3前端和FastAPI后端，帮助您高效管理和复习知识点。特别适合用于记录AI面试问题、复习知识点、准备大模型微调数据集。

#### ✨ 特点:
- Markdown格式问答记录，多种视图模式
- 智能搜索与复习功能
- 支持导出为大模型训练数据
- 跨平台支持，一键启动

### [KnowledgeMapNotes: 知识图谱笔记系统](https://github.com/xkj0127/KnowledgeMapNotes)

<div align="center">
  <img src="https://raw.githubusercontent.com/xkj0127/KnowledgeMapNotes/main/screenshot.png" width="60%" />
</div>

**KnowledgeMapNotes** 是一个基于知识图谱的笔记系统，帮助用户以图谱形式组织和管理知识点，实现知识间关联的可视化展示与导航。

#### ✨ 特点:
- 知识点节点化，支持多维关联
- 智能关联推荐，自动建立知识间联系
- 直观的图形界面，拖拽式编辑
- 支持导出为多种格式

### [AI_NOTE: 个人知识支持图谱](https://github.com/xkj0127/AI_NOTE)

**AI_NOTE** 是一个便携式的个人知识管理系统，将AI与知识图谱技术相结合，为用户构建个性化的知识支持网络。

#### ✨ 特点:
- 自动从文档中提取核心概念并构建知识图谱
- 智能检索与推荐相关知识点
- 与大语言模型集成，提供上下文增强的问答
- 个人记忆扩展，辅助学习与工作

## 🛠️ 技术专长

### 大语言模型 (LLM)
- Transformer架构深度优化
- 自注意力机制变体研究
- 上下文窗口扩展技术
- 参数高效微调 (LoRA, P-Tuning)

### 检索增强生成 (RAG)
- 知识图谱增强检索
- 混合检索策略设计
- 向量数据库优化 (Milvus, Pinecone, Faiss)
- 上下文压缩与重组方法

### 应用开发
- 轻量级AI应用架构
- Vue+FastAPI全栈开发
- 模型本地部署与优化
- 中文场景AI体验优化

## 📊 数据可视化

<div align="center">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=xkj0127&layout=compact&theme=radical" width="45%" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=xkj0127&theme=radical" width="45%" />
</div>

## 🔗 了解更多

<p align="center">
  <a href="https://github.com/xkj0127"><img src="https://img.shields.io/badge/GitHub-xkj0127-100000?style=for-the-badge&logo=github&logoColor=white" /></a>
</p>

---

<p align="center">
    <img src="https://komarev.com/ghpvc/?username=xkj0127&color=blueviolet&style=flat-square&label=访问量" alt="访问量计数器" />
</p>

> "AI不是为了替代人类，而是为了增强人类能力，拓展我们的认知边界。"
