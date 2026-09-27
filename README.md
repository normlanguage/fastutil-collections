# fastutil

[English](README.md) | [简体中文](README.zh-CN.md)

The adapter declaration and runnable example are in `fastutil/collections`. It pins fastutil 8.5.19 and defines its package coordinates in [module.norm](fastutil/collections/module.norm). The public API covers common primitive lists and sets, int/long-to-object maps, and object-to-int maps.

`FastutilBindingIntegrationTest` covers standalone NAR consumption, primitive collections, generic maps, ordinary Norm iteration, and shared host identity. The complete API census and reasons for unsupported APIs are in the NAR's `binding/java-api.json`.

[Runnable samples](samples/README.md) demonstrate the library as an external Norm dependency.
