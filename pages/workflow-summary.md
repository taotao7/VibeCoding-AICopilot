---
layout: center
class: text-center
transition: fade
---

# 工作流总结 

---
layout: default
---

## 没有Cursor前的工作流

<div class="text-center mb-8 mt-8">

### 开发模式

通过Aider实现完整的AI辅助编程工作流

</div>

<div class="grid grid-cols-2 gap-6">
<div>

###  核心命令

- AI? - 代表向AI提问
- AI! - 触发AI编辑
- aider --commit - AI生成commit信息
- aider --browser - 启动服务前端界面
- ...

</div>
<div>

###  优势

- 完全命令行操作
- 灵活的触发方式
- 容易进入心流状态
- 强大的上下文理解
- 多模型协作

</div>
</div>

---
layout: default
---

## 现在的选择策略

<div class="space-y-6 mt-8">

### 任务分类选择

<div class="grid grid-cols-3 gap-4">
<div class="text-center">

**复杂规划**  
GPT-o3 Ask Mode

</div>
<div class="text-center">

**代码实现**  
Claude-4 Agent Mode

</div>
<div class="text-center">

**多文件上下文**  
Gemini 2.5-Pro

</div>
</div>

### 工具组合

- **Cursor**: 主要开发环境
- **Aider**: 复杂上下文和结对编程
- **Jules**: 简单任务处理 （例如国际化）
- **MCP**: 特定功能增强

</div>

---
layout: default
---

## 关键建议 

<div class="grid grid-cols-2 gap-6 mt-8">
<div>

###  最佳实践

- 根据任务复杂度选择工具
- 项目结构规范、代码规范
- 重视代码Review
- 合理控制上下文范围
- 拆分需求粒度
- TDD 测试驱动开发很适合AI Agent

</div>
<div>

### ️ 注意事项

- AI Copilot & Agent 除了提效更应该写出高质量代码，纯粹的快只会让项目不断熵增
- 关闭自动commit
- 不盲目追求vibe coding
- 项目的规划和架构设计才是能够长期发展的关键
- 手动添加必要上下文
- 限制AI的活动

</div>
</div>
