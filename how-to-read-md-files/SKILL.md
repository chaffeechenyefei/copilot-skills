---
name: how-to-read-md-files
description: how to read and use the markdown files where there are coding requirements inside.
---

<!-- Tip: Use /create-skill in chat to generate content with agent assistance -->

# Modification Rules
- 每次改动(增加代码), 代码中必须要有注释, 中英文双语都需要
- 改动结束后, 需要判断是否更新README.md
- [thinking]或者<thinking></thinking>中的内容, 是我希望你(coding agent)自己考虑并作出判断的内容, 这里之所以特别标注出来, 是为了提示你进行判断, 因为我也不确定哪个方案更好
- 改动结束后, 如果发现本文档中其他部分与现有内容有冲突, 请修改本文档其他部分的描述, 确保二者相互匹配

## 状态更新规则
- 一般只需要对[new]或者<new></new>中的内容进行改动, 改动结束后, 标记为[modified]或者对应的<modified></modified>, 并根据实际改动内容, 对[new]或者<new></new>进行改动, 主要是对修改的说明,便于之后coding agent理解. 即:完成实现后，请将本文档各段落前缀从 `[new]` 改为 `[modified]`（可按 section 级别更新）。
