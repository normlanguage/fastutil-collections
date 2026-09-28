# fastutil 示例

[English](README.md) | [简体中文](README.zh-CN.md)

[hello.norm](hello.norm) —— 使用原生整数集合统计值的总数和去重数。这是通过自身的 `Module module()` 声明依赖的独立消费者程序。

在仓库根目录运行：

```sh
norm run samples/hello.norm
```

[module.norm](../fastutil/collections/module.norm) 指定 Java 制品版本并定义公开 API。

预期输出：

```text
3
2
```

API 入口：[module.norm](../fastutil/collections/module.norm) 列出公开的 `IntArrayList` 和 `IntOpenHashSet`。[适配器验收示例](../examples/sample/fastutil/collections/Main.norm)覆盖更多绑定行为。
