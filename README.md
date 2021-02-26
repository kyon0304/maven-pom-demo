介绍 maven 中 **BOM(Bills Of Material)** 的用法，更加方便的管理组件版本。

项目结构：

- component-bom 中是组件模块，组件 c 依赖 b，a 是单独的组件
- service-base 中是服务模块，service-1 依赖了 a，service-2 依赖 c
