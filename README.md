# AI Reasoning Notes

一个围绕 AI reasoning 主题的个人知识库，用来沉淀阅读笔记、可运行 notebook、实验观察、问题记录与想法演化。

这个仓库不是某一个上游项目的镜像，而是一个长期积累的个人内容库。  
当前内容主要来自 `Reasoning Kingdom`，后续也会逐步加入其他 repo、论文和实验材料。

## 运行环境

```bash
pip install -r requirements.txt
```

依赖：`numpy` `matplotlib` `gensim` `torch` `scikit-learn` `plotly`（详见 `requirements.txt`）。ch02 无外部依赖。

---

## 这个仓库包含什么

- 阅读笔记
- 按章节整理的实验 notebook
- 对实验结果的 review 与修正
- 中间想法、问题与待验证观察
- 相关论文与仓库索引

目标不是只做“读后总结”，而是把阅读过程转化为：

- 可执行的实验
- 可检验的观察
- 可复用的笔记

---

## 当前目录结构

```text
ai-reasoning-notes/
├── requirements.txt
├── notes/
│   ├── reasoning-kingdom/                  ← 阅读笔记、计划、开放问题
│   │   └── main/volume1/                   ← 章节笔记
│   └── inbox/
│       └── ideas.md                        ← 临时想法与待整理内容
├── notebooks/
│   ├── reasoning-kingdom/                  ← 可运行实验 notebook
│   └── scratch/                            ← 临时实验草稿
└── sources/
    ├── reasoning-kingdom.md
    ├── papers.md                           ← 读过的论文
    └── url.md                              ← 网络文章、视频、播客等
```

---

## 原则

- 用自己的语言写笔记，不复制原文；notebook 以改写、扩展、验证为主
- 优先保留可运行实验，而不是只保留结论
- 来源统一记录在 `sources/`（repo/书用独立文件，论文用 `papers.md`，网络资料用 `url.md`），派生内容与上游内容严格分开
- 保留不确定性，不是每条笔记都已经是定论

---

## 当前状态

这是一个持续演化中的仓库。

有些笔记已经相对成型，有些内容仍在从长阅读日志中提炼，有些 notebook 还处于活跃修改阶段。  
这里更像一个长期维护的研究与学习工作台，而不是一次性完成的成品集。

