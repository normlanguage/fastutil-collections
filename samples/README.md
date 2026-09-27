# fastutil samples

[English](README.md) | [简体中文](README.zh-CN.md)

[hello.norm](hello.norm) — Count values and distinct integers with primitive collections. This is a standalone consumer with its own `Module module()` dependency.

From the repository root, run:

```sh
norm run samples/hello.norm
```

[module.norm](../fastutil/collections/module.norm) pins the Java artifact and defines the public API.

Expected output:

```text
3
2
```

API reference: [module.norm](../fastutil/collections/module.norm) lists the exposed `IntArrayList` and `IntOpenHashSet`. The module's `Main.norm` remains its own adapter integration entry point.
