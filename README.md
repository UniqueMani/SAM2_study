# sam2_study

本仓库用于个人学习和对比 **SAM / SAM2 系列模型在医学图像分割中的效果**。

目前包含三个子项目的代码（直接拷贝在一个仓库中，方便统一管理和对比）：

- `I-MedSAM`：针对医学图像改进的交互式 Segment Anything 模型
- `Medical-SAM2`：基于 SAM2 的医学图像分割框架
- `segment-anything`：Meta 官方的原始 Segment Anything 实现

> 说明：本仓库只是个人学习用途的集合仓库，并非任一项目的官方镜像。  
> 具体模型细节、最新更新、预训练权重等，请以各子项目原始仓库为准。

---

## 目录结构

```text
sam2_study/
├─ I-MedSAM/          # I-MedSAM 源码及其配置 / 脚本
├─ Medical-SAM2/      # Medical-SAM2 源码
├─ segment-anything/  # 原始 SAM 实现
└─ README.md          # 当前说明文档
