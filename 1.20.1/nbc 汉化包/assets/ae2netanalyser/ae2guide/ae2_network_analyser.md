---
navigation:
    parent: ae2:items-blocks-machines/items-blocks-machines-index.md
    icon: ae2netanalyser:network_analyser
    title: ME 网络分析仪
categories:
- tools
item_ids:
- ae2netanalyser:network_analyser
---

# ME 网络分析仪

<ItemImage id="ae2netanalyser:network_analyser" scale="4"></ItemImage>

您是否曾为找不到 ME 网络中的哪个设备处于离线状态而苦恼？或者只是想了解网络的运行情况？这里有 ME 网络分析仪！

## 问题出在我的ME网络上?

点击任何连接到ME网络的模块、线缆或设备，你会看到每个设备的状态以及它们之间的连接方式

![overview](./pic/showoff.png)

不同的颜色和形状代表着不同的状态：
- **蓝色方块**: 普通 ME 设备，拥有足够的频道，可传递最多 **8 个频道**。
- **黄色方块**：密集型 ME 设备，拥有足够的频道，可传递最多 **32 个频道**。
- **红色方块**：离线的 ME 设备，没有足够的频道。
- **蓝色连线**：此连接最多可承载 **8 个频道**。
- **黄色连线**：此连接最多可承载 **32 个频道**。
- **粉色连线**：这是一个 ME P2P（点对点）连接。
- **数字**：表示该连接当前承载的频道数量。

**注意**：最大频道数量实际上取决于你的 **ME 频道模式**。当启用 **无限频道模式** 时，分析器不会显示频道数量

## 自定义显示

**你可以在配置界面中更改分析模式和颜色**

![gui](./pic/gui.png)

**ME 网络分析器**（ME Network Analyser）有 5 种模式：

- **完整模式（Full）**：显示所有网络状态。
- **节点模式（Nodes）**：仅显示节点状态。
- **连接模式（Links）**：仅显示连接状态。
- **无数字模式（No Number）**：不显示频道数量。
- **P2P 模式（P2P）**：仅显示 ME P2P（点对点）连接。

你也可以更改 **节点** 或 **连接** 的颜色。

![gui2](./pic/color.png)

