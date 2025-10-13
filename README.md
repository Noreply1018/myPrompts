# myPrompts

一个用于系统化管理 AI 提示词（Prompts）的个人仓库。

## 目录结构
- `prompts/`：个人平时积累的提示词

## 使用方法
1. 在目录下新建一个 `.md` 文件
2. 在文件顶部填写元信息（见下方模板）
3. 通过 Git 提交版本，记录每次修改的意图与变化

## 提示词文档模板（复制到每个新提示词文件最上方）
```yaml
---
title: <提示词标题>
model: <GPT-4|Claude|Gemini|本地模型...>
purpose: <这个提示词解决什么问题>
version: 0.1.0
last_updated: YYYY-MM-DD
inputs:
  - 名称: 说明
  - 名称: 说明
