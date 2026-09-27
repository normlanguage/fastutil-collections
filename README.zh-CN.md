# fastutil

[English](README.md) | [简体中文](README.zh-CN.md)

适配声明与可运行示例位于 `fastutil/collections`，固定 fastutil 8.5.19，发布坐标见 [module.norm](fastutil/collections/module.norm)。公开面覆盖常用 primitive list、set、int/long 到对象映射和对象到 int 映射。

独立 NAR 消费、primitive collections、泛型映射、普通 Norm 迭代协议和共享宿主 identity 由 `FastutilBindingIntegrationTest` 验收。完整 census 与未支持原因位于 NAR 的 `binding/java-api.json`。

[可运行示例](samples/README.zh-CN.md) 展示如何作为外部 Norm 依赖使用本库。
