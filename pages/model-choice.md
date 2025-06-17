---
layout: center
transition: fade
title: 模型选择指南
background: linear-gradient(135deg, #92400e 0%, #b45309 50%, #92400e 100%)
class: text-center
---

# 模型选择指南

<div class="bg-amber-100 border-l-4 border-amber-500 p-4 mb-6 rounded-r-lg shadow-lg inline-block">
<p class="text-amber-800 font-medium">选择合适的AI模型是提升编程效率的关键</p>
</div>

---
layout: default
---

# 评估基准

<div class="grid grid-cols-2 gap-6 mt-8">
  <div class="bg-white/95 backdrop-blur-sm border border-amber-200 rounded-lg p-6 shadow-lg hover:shadow-xl transition-shadow">
    <h3 class="font-bold text-lg text-amber-800 mb-3">Aider Leaderboards</h3>
    <a href="https://aider.chat/docs/leaderboards/" target="_blank" class="text-amber-600 hover:text-amber-800 underline block mb-2">访问排行榜</a>
    <div class="text-amber-700 space-y-1 text-sm">
      <div>• 专业的AI编程助手评估排行榜</div>
      <div>• 实时更新的模型性能对比</div>
    </div>
  </div>
  
  <div class="bg-white/95 backdrop-blur-sm border border-amber-200 rounded-lg p-6 shadow-lg hover:shadow-xl transition-shadow">
    <h3 class="font-bold text-lg text-amber-800 mb-3">SWE-Bench</h3>
    <a href="https://www.swebench.com/" target="_blank" class="text-amber-600 hover:text-amber-800 underline block mb-2">访问基准测试</a>
    <div class="text-amber-700 space-y-1 text-sm">
      <div>• 软件工程任务基准测试</div>
      <div>• 基于真实GitHub问题的评估框架</div>
    </div>
  </div>

  <div class="bg-white/95 backdrop-blur-sm border border-amber-200 rounded-lg p-6 shadow-lg hover:shadow-xl transition-shadow">
    <h3 class="font-bold text-lg text-amber-800 mb-3">Artificial Analysis</h3>
    <a href="https://artificialanalysis.ai/models" target="_blank" class="text-amber-600 hover:text-amber-800 underline block mb-2">Artificial Analysis</a>
    <div class="text-amber-700 space-y-1 text-sm">
      <div>• 模型能力对比</div>
      <div>• 模型选择参考</div>
    </div>
  </div>
</div>

---
layout: default
---

# 关于 SWE-Bench

<div class="bg-amber-100/90 backdrop-blur-sm rounded-lg p-6 mb-8 shadow-lg border border-amber-300">
  <p class="text-amber-800 font-medium mb-4">SWE-Bench 是一个用于评估大型语言模型（LLMs）在软件工程任务中表现的基准测试框架，特别是针对真实世界的代码库问题修复能力。</p>
  
  <div class="bg-white/95 rounded-lg p-4 border border-amber-200">
    <h4 class="font-semibold text-amber-800 mb-3">核心特点</h4>
    <div class="grid gap-3">
      <div class="flex items-start space-x-2">
        <div class="w-1.5 h-1.5 bg-amber-600 rounded-full mt-2 flex-shrink-0"></div>
        <span class="text-amber-700 text-sm">基于 GitHub 仓库中的真实问题（Issues）</span>
      </div>
      <div class="flex items-start space-x-2">
        <div class="w-1.5 h-1.5 bg-amber-600 rounded-full mt-2 flex-shrink-0"></div>
        <span class="text-amber-700 text-sm">对应的代码修复（Pull Requests）</span>
      </div>
      <div class="flex items-start space-x-2">
        <div class="w-1.5 h-1.5 bg-amber-600 rounded-full mt-2 flex-shrink-0"></div>
        <span class="text-amber-700 text-sm">要求模型理解问题描述并生成正确的代码修改</span>
      </div>
      <div class="flex items-start space-x-2">
        <div class="w-1.5 h-1.5 bg-amber-600 rounded-full mt-2 flex-shrink-0"></div>
        <span class="text-amber-700 text-sm">评估模型在实际开发场景中的能力</span>
      </div>
    </div>
  </div>
</div>

---
layout: default
---

# 重要考量因素

<div class="bg-amber-200/30 backdrop-blur-sm border border-amber-300 rounded-lg p-6 shadow-lg">
  <h3 class="font-bold text-lg text-white mb-4">模型上下文长度限制</h3>
  
  <div class="space-y-4">
    <p class="text-amber-100 mb-4">选择模型时需要特别注意：</p>
    <div class="flex gap-4 overflow-hidden">
      <img src="/context.png" alt="模型上下文长度限制" class="w-1/2 h-auto object-contain">
      <img src="/Intelligence&Context.png" alt="模型智力和上下文长度" class="w-1/2 h-auto object-contain">
    </div>
  </div>
</div>

---
layout: default
---

# 选择建议

<div class="bg-white/95 backdrop-blur-sm border border-amber-200 rounded-lg overflow-hidden shadow-lg mt-8">
  <div class="bg-amber-100 px-6 py-3 border-b border-amber-200">
    <h3 class="font-semibold text-amber-800">不同场景的模型选择参考</h3>
  </div>
  
  <div class="overflow-x-auto">
    <table class="w-full text-sm">
      <thead class="bg-amber-50">
        <tr>
          <th class="px-6 py-3 text-left text-xs font-medium text-amber-700 uppercase tracking-wider">场景</th>
          <th class="px-6 py-3 text-left text-xs font-medium text-amber-700 uppercase tracking-wider">推荐上下文长度</th>
          <th class="px-6 py-3 text-left text-xs font-medium text-amber-700 uppercase tracking-wider">适用模型类型</th>
        </tr>
      </thead>
      <tbody class="divide-y divide-amber-200">
        <tr>
          <td class="px-6 py-4 text-amber-900 font-medium">简单函数修改</td>
          <td class="px-6 py-4 text-amber-700">4K-8K tokens</td>
          <td class="px-6 py-4 text-amber-700">轻量级模型</td>
        </tr>
        <tr class="bg-amber-50/50">
          <td class="px-6 py-4 text-amber-900 font-medium">中等项目重构</td>
          <td class="px-6 py-4 text-amber-700">16K-32K tokens</td>
          <td class="px-6 py-4 text-amber-700">平衡型模型</td>
        </tr>
        <tr>
          <td class="px-6 py-4 text-amber-900 font-medium">大型项目分析</td>
          <td class="px-6 py-4 text-amber-700">64K+ tokens</td>
          <td class="px-6 py-4 text-amber-700">长上下文模型</td>
        </tr>
      </tbody>
    </table>
  </div>
</div>

<style>
.slidev-layout {
  background: linear-gradient(135deg, #92400e 0%, #b45309 50%, #92400e 100%);
  color: white;
}
</style>