# Comparative-analysis-of-various-LLM
# 大语言模型对比分析项目

## 📖 项目简介

本项目是一个大语言模型对比分析实验，通过在魔搭平台上部署和测试三个主流的中文大语言模型，对它们在复杂语言理解任务上的表现进行深入分析和对比。

## 🎯 研究目标

- 部署和配置多个大语言模型
- 设计具有挑战性的中文语言理解测试用例
- 分析不同模型在复杂语境下的表现差异
- 提供模型选择和应用的参考建议

## 🤖 测试模型

### 1. 通义千问 Qwen-7B-Chat
- **参数规模**: 7B
- **架构**: Transformer
- **特点**: 混合精度训练、模型剪枝优化

### 2. 智谱 ChatGLM3-6B
- **参数规模**: 6B  
- **架构**: GLM (General Language Model)
- **特点**: 针对中文语言特别优化

### 3. 百川 Baichuan2-7B-Chat
- **参数规模**: 7B
- **架构**: Transformer
- **特点**: 对话场景优化、多轮对话管理

## 🧪 测试用例

项目设计了5个具有挑战性的中文语言理解测试：

1. **语境反转理解**: "冬天/夏天：能穿多少穿多少"
2. **语义歧义分析**: "单身狗产生的原因"中的双重含义
3. **复杂逻辑嵌套**: "他知道我知道你知道他不知道吗？"
4. **句法结构解析**: "明明明明明白白白喜欢他"
5. **多义词理解**: 对话中"意思"的不同含义

## 📊 主要发现

### 模型表现排名
1. **通义千问 Qwen-7B-Chat** ⭐⭐⭐⭐⭐
   - 语境理解能力最强
   - 逻辑分析详细准确
   - 中文语言理解细致

2. **智谱 ChatGLM3-6B** ⭐⭐⭐⭐
   - 直接语义理解良好
   - 符合人类思维特点
   - 复杂逻辑处理有待提升

3. **百川 Baichuan2-7B-Chat** ⭐⭐⭐
   - 基础对话能力可用
   - 复杂语境理解不足
   - 需要进一步优化

### 关键洞察
- 参数规模相近的模型在中文理解能力上存在显著差异
- 训练数据和优化策略对模型性能影响巨大
- 复杂嵌套逻辑是当前大模型的共同挑战

## 🚀 快速开始

### 环境要求
- Python 3.8+
- 魔搭平台账号
- 阿里云账号（用于关联）

### 部署步骤

1. **登录魔搭平台**
   ```bash
   # 关联阿里云账号，打开Notebook
   ```

2. **克隆模型**
   ```bash
   # 通义千问
   git clone https://modelscope.cn/qwen/Qwen-7B-Chat.git
   
   # 智谱ChatGLM3
   git clone https://modelscope.cn/ZhipuAI/chatglm3-6b.git
   
   # 百川Baichuan2
   git clone https://modelscope.cn/baichuan-inc/Baichuan2-7B-Chat.git
   ```

3. **运行测试**
   ```bash
   # 编写并执行推理脚本
   jupyter notebook test.ipynb
   ```

## 📁 项目结构

```
├── README.md              # 项目说明文档
├── Qwen-7B-Chat/
│   ├── git_clone.png            
│   ├── Qwen-7B-Chat.png
│   ├── Q1.png
│   ├── Q2.png
│   ├── Q3.png
│   ├── Q4.png
│   ├── Q5.png
├── chatglm3-6b/
│   ├── git_clone.png         
│   ├── chatglm3-6b.png
│   ├── Q1.png
│   ├── Q2.png
│   ├── Q3.png
│   ├── Q4.png
│   ├── Q5.png
└── Baichuan2-7B-Chat/
    ├── git_clone.png           
    ├── Baichuan2-7B-Chat.png
    ├── Q1.png
    ├── Q2.png
    ├── Q3.png
    ├── Q4.png
    └── Q5.png
```

## 🔗 相关链接

- [项目仓库](https://github.com/xiangmaster/Comparative-analysis-of-various-LLM.git)
- [魔搭平台](https://modelscope.cn/)

---
