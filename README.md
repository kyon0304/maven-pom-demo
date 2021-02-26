介绍 maven 中 **BOM(Bills Of Material)** 的用法，更加方便的管理组件版本。

项目结构：

- component-bom 中是组件模块，组件 c 依赖 b，a 是单独的组件
- service-base 中是服务模块，service-1 依赖了 a，service-2 依赖 c

master 分支中所有组件版本都是 1.0，update-b 分支中，b 组件升级至 2.0 版本，可以看到通过 bom  方式，如何简化模块管理。
