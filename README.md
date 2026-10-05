<div align="center">

# Hi, I'm 张继尧 (Zhang Jiyao)

**西安交通大学 · 信息与计算科学 · 2025 – 2029**

后端开发 / 本地大模型 / 机器学习 / 数学建模

[![Email](https://img.shields.io/badge/Email-zhangjiyao555@stu.xjtu.edu.cn-blue?style=flat-square&logo=maildotru&logoColor=white)](mailto:zhangjiyao555@stu.xjtu.edu.cn)
[![GitHub](https://img.shields.io/badge/GitHub-zjy--141-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/zjy-141)
[![Tuxun](https://img.shields.io/badge/Project-图寻-00A86B?style=flat-square&logo=googlechrome&logoColor=white)](https://tuxun.tiaozhan.com)
[![Practice](https://img.shields.io/badge/Project-社会实践平台-1E90FF?style=flat-square&logo=googlechrome&logoColor=white)](https://shijian.tiaozhan.com/)

</div>

---

## 教育背景

**西安交通大学** · 信息与计算科学专业 · 2025.09 – 2029.06（预期）

- **核心课程**：大学计算机-算法编程 **98**、高等代数与几何II-2 **88**、数学分析II-2 **86**、数论
- **英语**：CET-4 已通过，CET-6 备考中
- **竞赛**：全国大学生数学建模竞赛校赛 **三等奖**（队长）；中学阶段数学、化学奥赛省级奖项

---

## 技术栈

**编程语言与后端**  
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Gin](https://img.shields.io/badge/Gin-008ECF?style=flat-square&logo=go&logoColor=white)
![Gorm](https://img.shields.io/badge/Gorm-00ADD8?style=flat-square&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)

**数据库与部署**  
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**大模型与机器学习**  
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Transformers](https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![PEFT](https://img.shields.io/badge/PEFT-FF6F00?style=flat-square&logo=python&logoColor=white)

**前端了解**  
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vue3](https://img.shields.io/badge/Vue3-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)

---

## 项目经历

### 本地大语言模型全流程实践（独立完成）
**从零预训练 · SFT 微调 · RAG · LoRA/QLoRA · GGUF 部署**

- **从零预训练**：在 **RTX 5060 Laptop（8GB 显存，sm_120 架构）** 上完成 MiniMind 环境搭建、数据准备与预训练，使用 **127 万条** 数据训练 **2 个 epoch**，**loss 从 7.69 降至 1.49**，并解决 PyTorch cu128 对 sm_120 的兼容性问题。
- **指令微调 SFT**：基于 **LCCC-base** 中文对话数据集，处理并抽取 **5 万条** 高质量数据，通过调整学习率（1e-5 → 5e-5）与训练轮数，解决 SFT loss 不下降问题。
- **RAG 知识库问答**：基于 LangChain/LlamaIndex + FAISS/Chroma 实现文档切分、向量检索与检索增强生成，构建本地知识库问答流程。
- **LoRA/QLoRA 微调**：基于 Qwen 系列模型实践参数高效微调流程。
- **格式转换与部署**：完成 PyTorch → HuggingFace → GGUF 格式转换，部署至 **WSL + Ollama**，实现完全离线的本地大模型推理服务。
- **完整工程记录**：编写 **v6.0 操作指南**，记录环境配置、数据转换、训练监控、问题排查与部署全流程，保证可复现性。

链接：[minimind_try](https://github.com/zjy-141/minimind_try) · [finetune_qwen](https://github.com/zjy-141/finetune_qwen)

---

### 图寻｜后端开发与架构设计
**Go + Gin + Gorm + MySQL · RESTful API · 已上线**

- 独立负责全部后端开发与架构设计，采用 **Controller-Service** 分层架构，保证代码可维护性。
- 完成从需求分析、表结构设计到云服务器部署的全流程。
- 项目已上线并投入校内使用，服务校内用户。

链接：[tuxun.tiaozhan.com](https://tuxun.tiaozhan.com) · [代码仓库](https://github.com/zjy-141/tu-xun)

---

### 西安交通大学社会实践平台｜技术支持与维护
**线上运维 · Bug 修复 · 功能优化**

- 负责社团现有网站的技术支持与日常维护，处理线上 Bug 与功能优化请求。
- 保障网站持续稳定服务社团成员与用户，熟悉生产环境代码调试流程与用户反馈驱动的迭代节奏。

链接：[shijian.tiaozhan.com](https://shijian.tiaozhan.com/)

---

### 数学建模竞赛｜队长
**选题决策 · 核心算法 · 团队统筹**

- 担任队长，主导赛题研判与方向决策，综合评估数据可得性、模型适配度与工作量。
- 负责核心算法设计与代码框架搭建，统筹队友完成数据预处理与可视化。
- 获 **校级三等奖**，正带队备战全国大学生数学建模竞赛。

---

### 课程实践：数字化设计与制造 / 机器人创意设计

- 使用 **Autodesk Inventor** 完成零部件建模、装配体设计与工程图绘制。
- 基于 **Arduino-1.5.2** 搭建具备 **蓝牙信号接收** 与 **自动循迹** 功能的小车。
- 锻炼动手搭建能力与嵌入式逻辑思维，对软硬件协同工作有直观认识。

---

## GitHub 统计

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=zjy-141&show_icons=true&theme=radical&hide_border=true)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=zjy-141&layout=compact&theme=radical&hide_border=true)
![GitHub Streak](https://streak-stats.demolab.com?user=zjy-141&theme=radical&hide_border=true)

</div>

---

## 关于我

- 喜欢从零搭建系统，也喜欢把模型真正跑起来。
- 对后端工程、大模型训练与推理、机器学习底层原理有持续兴趣。
- 正在自学机器学习，逐步建立算法与模型背后的数学直觉。
- 相信 **可复现、可维护、可解释** 的工程实践。

---

<div align="center">

**感谢访问！欢迎交流技术、项目与合作。**

![Profile Views](https://komarev.com/ghpvc/?username=zjy-141&color=blueviolet&style=flat-square)

</div>