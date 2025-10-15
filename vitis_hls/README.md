# Vitis HLS 优化提示词库（Optimize Prompts）

面向 Vitis HLS（推荐 2024.2）的 **分析与优化类**提示词集合。  
目标是：在 **访存瓶颈 / 计算调度 / Dataflow 重构** 三大方向上，快速获得结构化的诊断结论与可粘贴的 `pragma patch`。

---

## 📁 目录结构

prompts/

└─ vitis_hls/

 └─ optimize/
 
  ├─ memory_bottleneck.yaml # 访存瓶颈优化
  
  ├─ compute_scheduling.yaml # 计算/调度优化（II、资源）
  
  ├─ dataflow_rewrite.yaml # Dataflow / 模块级流水
  
  └─ router_entry.yaml # 统一入口路由器（自动选模板）
  
