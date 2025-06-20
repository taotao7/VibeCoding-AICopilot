---
layout: default
transition: fade
---

# Jules - Google 财大气粗

<div class="flex items-center justify-between mt-8">
<div class="w-2/3">

- **地址**: https://jules.google/
- **优势**: 代码能力和规划表现不错
- **适用**: 单一任务处理
- **价格**: Google 每天60次agent免费

</div>
<div class="w-2/3">

- 简单指定仓库、分支
- 输入任务等待完成
- review jules提交的PR
- gemini 2.5-pro 上下文理解能力强

</div>
</div>

---
layout: default
---

# Claude Code

### 核心功能
- 输入需求、生成代码、修改代码

### 缺点
- 对现有中型以上代码库分析能力较弱
- 模型能力强，但是工程能力不算顶尖

### 亮点
- 对编辑器集成有不错支持能够读取光标位置的代码和当前编辑器打开的文件
- mcp 支持

<!-- 说是支持图片和多模态输入我没找到入口 -->


---
layout: image
---

![claude-1.png](/claude-1.png)


---
layout: cover
---

# Aider - 结对编程利器

**链接**: https://aider.chat/

---
src: ./aider-deep-dive.md
hide: false
---



---
layout: image
---

![aider-1.png](/claude.jpeg)



---
layout: image
---

![aider-1.png](/aider.png)

<!--
两个同类工具对比,
  aider 上下文更长，项目分析能力和工程能力更强
  claude  同样的prompt最终结果没有完成任务，甚至入口都没找对
 aider能完成任务消耗输入token 2.4k 0.31刀,claude 消耗输入token 1.2k

  工具总结，基本上订阅制的工具都有这个问题，压缩token节约成本，token少了,成本少了，上下文少了，但是同时解决和定位问题的能力就弱了
  所以需要根据任务选择合适的工具，比如复杂任务用aider，简单任务用claude，或者用cursor的agent模式,其实我觉得claude code目前体验下来算是个较尴尬的位置,cursor基本覆盖claude的全部功能,还多了编辑时的智能提示
-->

---
layout: default
---

# 其他工具
### Cursor Bug Bot
- 从PR里找bug

### opencode
- claude code 开源版本

### Cursor Background
- 对标Jules

### roo code && cline
- vscode 系的插件

### augument code (黑马)
- 超长上下文
- 基本以插件的形式做到了cursor的全部功能
- 支持idea系列