---
date: {{ .Date }}
title: prompt
description: 提示词工程
tags: ["prompt"]
series: ["LLM"]
---

# tip

- 使用分隔符对输入内容区分，例如```, """, < >, <tag> </tag>等
- 命令使用格式来输出，例如 json 格式
- 尽量拆解任务,使用-拆分
- 尽量避免输入的太长
- 使用例如 Your task is to，based on ，is intended for 等词明确目的

## static linking