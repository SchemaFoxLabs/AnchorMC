# 玩法特性与机制

[English](../GAMEPLAY_FEATURES.md) · **中文** · [日本語](GAMEPLAY_FEATURES.ja-JP.md) · [हिन्दी](GAMEPLAY_FEATURES.hi-IN.md)

[返回 AnchorMC](README.zh.md)
本文档说明 AnchorMC 的玩法、性能与无障碍相关改进。功能逐步上线期间，不同子服的可用情况可能不同。

## 战斗

- 缩小并提高弹射物碰撞箱精度，包括末影珍珠、箭、鸡蛋和雪球。
- 更快的位置更新：有效移动位置精度由每两 tick 更新 4/32 方块，提高为每 tick 更新 1/32 方块。
- 对玩家与弹射物交互进行延迟补偿。
- 修复命中事件被意外取消的问题。

## 安全与性能

- 持续进行安全更新。
- 重构历史遗留的“面条代码”，提高可维护性。
- 基于 [BambooSpigot](https://github.com/error-nullindex/BambooSpigot) 开发变更进行 TPS 优化。

## 无障碍

无障碍功能仍在规划中，行为确定后将在本文档说明。
