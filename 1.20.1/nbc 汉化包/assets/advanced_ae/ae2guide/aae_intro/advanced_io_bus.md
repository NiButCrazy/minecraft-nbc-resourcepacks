---
navigation:
  parent: aae_intro/aae_intro-index.md
  title: Advanced IO Bus
  icon: advanced_ae:advanced_io_bus_part
categories:
  - advanced items
item_ids:
  - advanced_ae:advanced_io_bus_part
---

# ME高级IO总线

<GameScene zoom="8" background="transparent">
  <ImportStructure src="../structure/cable_advanced_io_bus.snbt"></ImportStructure>
</GameScene>

**ME高级IO总线**是一种与外部库存交互的强大工具。  
它由 <ItemLink id="advanced_ae:import_export_bus_part" /> 与 <ItemLink id="advanced_ae:stock_export_bus_part" /> 组合而成，并继承了两者的全部功能。  

此外，ME高级IO总线的基础速度比 <ItemLink id="ae2:export_bus" /> 的基础速度**快 8 倍**。  
它需要一些时间才能加速到最大速度，但在完全升级后将会快得令人惊叹。

---

## 输出

ME高级IO总线会按照其过滤器进行输出，最多达到固定数量后就会停止输出。  
在界面的左侧还有一个配置选项，允许玩家选择是否调节物品库存。

---

## 输入

ME高级IO总线也会输入所有**未被设置为输出的物品**。  
输入与输出操作是分别计算的，因此总线不会卡在某一个操作上。  

当总线被配置为“调节”模式时，它会优先**输入超过设定数量的物品**。  
如果还有剩余的输入操作，它会输入所有未被过滤的物品。

---

<RecipeFor id="advanced_ae:advanced_io_bus_part" />