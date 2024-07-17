# Document_Extract-InternLM
基于文档内容的知识抽取

### 项目简介
本项目旨在利用InternLM的能力，构建文档内容知识抽取的功能。用户通过上传pdf文档或者text文档或者输入一段内容，并构建知识抽取prompt，利用InternLM抽取文档知识。主要功能包括：

1. **文件上传功能**：支持pdf、text等格式文档、支持内容输入。
2. **知识抽取prompt**：支持用户自定义知识抽取prompt

### 项目功能
![知识抽取助手](https://github.com/cgq0816/Document_Extract-InternLM/blob/main/1.png)

### 后续更新方向
1. **文件类型**：支持doc、excel等格式文件解析。
2. **模型微调**：使用XTuner工具对模型进行LoRA、QLoRA或全量参数微调，提升知识抽取效果。
