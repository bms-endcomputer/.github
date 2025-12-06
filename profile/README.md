# BMS（Battery Management System）代码仓库

欢迎来到bms-endcomputer的BMS代码仓库！  
本项目致力于提供高效、可靠的电池管理系统（BMS）软件解决方案，适用于电动汽车、储能系统等场景。

## 项目介绍

本仓库包含BMS的核心控制代码、通信协议实现、实时数据采集与分析等功能模块。代码结构清晰，便于二次开发和集成。

### 主要功能

- 电池单体电压、温度实时采集
- SoC（荷电状态）、SoH（健康状态）算法实现
- 均衡管理
- 过压、欠压、过温等异常检测与报警
- CAN、UART等多种通讯接口支持
- 历史数据记录与查询

## 文件结构

```shell
.
├── doc/              # 项目文档
├── src/              # 核心源代码
├── include/          # 公共头文件
├── tests/            # 单元测试代码
├── tools/            # 辅助工具及脚本
├── README.md         # 项目说明文档
└── ...
```

## 快速开始

1. **环境依赖**

   请确保已安装如下依赖环境：
   - GCC 或 Clang
   - CMake 3.10 及以上
   - 必要的硬件开发板驱动

2. **编译项目**
   ```bash
   mkdir build && cd build
   cmake ..
   make
   ```
3. **运行与测试**
   ```bash
   make test
   ```

## 参与贡献

欢迎提交issue和pull request！  
如需贡献，请遵循[贡献指南](./CONTRIBUTING.md)和[代码规范](./CODE_STYLE.md)。

## 许可证

本项目采用 MIT 许可证，详情见 [LICENSE](./LICENSE)。

---

如需更多帮助，请参考[项目文档](./doc/)或通过issue与我们联系。
