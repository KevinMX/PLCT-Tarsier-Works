## week 0

### 本周工作

1. 入组考核&面试，熟悉 openEuler RISC-V。

基本完成了容器相关的测试用例（目前能跑得起来的），包括：

- Docker
- iSula(d)
- 系统容器
- 安全容器
- ...

详见：[openeuler-riscv-2303-test / System_and_Feature_Test / Containers](https://gitee.com/yunxiangluo/openeuler-riscv-2303-test/tree/master/System_and_Feature_Test/Containers)

2. 更新 StarFive VisionFive 2 的安装说明，更新硬件测试内容。

### 缺陷报告

|ID|缺陷内容|状态|
|-|-|-|
|[I6R1UT](https://gitee.com/openeuler/RISC-V/issues/I6R1UT)|iSulad 无法启动|Fixed|
|[I6R1UT](https://gitee.com/openeuler/RISC-V/issues/I6RDWA)|isula-build 服务无法启动|Fixed|
|[I6RSAC](https://gitee.com/openeuler/RISC-V/issues/I6RSAC)|lxcfs 服务无法启动|Fixed|
|[I6R9OQ](https://gitee.com/openeuler/RISC-V/issues/I6R9OQ)|kata-containers 软件包缺失|Confirmed - WIP|