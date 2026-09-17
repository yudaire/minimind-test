# minimind-test
# MiniMind 从零训练实践

## 项目简介
基于 MiniMind 项目，从零完成一个小型语言模型的预训练与监督微调，
理解 Decoder-Only Transformer 的训练全流程。

## 我的工作
- 在单张 RTX 4090 上完成预训练与 SFT
- 独立解决环境配置、CUDA 兼容、数据挂载等问题
- 调整 batch size / learning rate，对比 loss 曲线变化
- 整理完整训练日志与踩坑记录

## 技术栈
Python, PyTorch, Transformers, CUDA, AutoDL, Git

## 进度
- [x] 本地准备 Git / VS Code
- [x] 租用 GPU
- [x] VS Code 远程连接
- [x] 克隆 minimind 代码
- [x] 安装依赖
- [ ] 下载数据集
- [ ] 预训练
- [ ] SFT
- [ ] 推理测试

## 目录说明
- docs/：分阶段实验记录
- results/：loss 曲线与模型输出
- notes/：问题与解决记录
