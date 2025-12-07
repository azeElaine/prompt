# GPT-4V / Vision Prompting

## 核心技巧
1. 让模型按区域描述图像
2. 明确“观察指令”
3. 使用多轮提问聚焦细节
4. 将视觉输入转为结构化数据

## 示例 Prompt
```
请详细描述图像中出现的所有物体，并按以下格式输出：

{
  "objects": [
     {"name": "", "position": "", "color": ""}
  ],
  "scene": "",
  "possible_actions": []
}
```

### OCR 示例
```
请从图片中识别所有文本，按顺序输出。
```
