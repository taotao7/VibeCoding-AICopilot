---
layout: center
class: text-center
---

# Cursor 配置与使用技巧 ️

<div class="text-center mb-8">

###  配置建议

基于个人使用经验的推荐配置

</div>

---
layout: default
---

# 使用技巧 

<div class="grid grid-cols-2 gap-6 mt-8">
<div>

### 极致懒人版

```bash
/Generate Cursor Rules
```

在对话框输入即可自动生成rule

### 极致强迫症版

- 基于生成的rule做细化
- 把常用规范用notepads记录
- 通过@来获取上下文
- 在agent或聊天时调用

</div>
<div>

### Notepads vs Rules

- **Notepads**: 可以包含文件上下文，预编辑常用prompt
- **Rules**: 不能主动调用只能匹配触发

</div>
</div>

---
layout: default
---

# 使用注意事项 ️

<div class="space-y-4 mt-8">

### 常见误区

- **不是maxtoken就是最好** - 过多上下文影响代码质量
- **避免过度依赖自动化** - 一定要review代码,防止ai超过你的设计边界

<div class="grid grid-cols-2 gap-6">
<div>

### 最佳实践

- 多动手拖拽上下文
- 选中代码 cmd + i 缩小范围
- 拆分需求粒度，粒度越低越好
- **关闭自动commit** - 避免直接提交未review的代码

</div>
<div>

### Manual Mode 的意义

- 强制限制AI范围，减少幻觉
- 避免生成无法维护的代码
- 需要更多手动上下文，但代码质量更高

</div>
</div>

</div>

<!--  为什么有时候在官方的chat页面会比在cursor或 windosurf之类的工具里更准确,因为靠着压缩token可以减少成本 -->
