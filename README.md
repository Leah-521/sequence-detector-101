# Sequence Detector 101

## 1. 项目简介

使用 Verilog HDL 设计一个序列检测器，用于检测输入数据流中的 `101` 序列。

## 2. 项目功能

- 支持时钟和复位输入
- 检测目标序列 `101`
- 支持连续输入和重叠检测（以实际 RTL 实现为准）

## 3. 项目文件

- `sequence_detector.v`：RTL 设计文件
- `tb_sequence_detector.v`：Testbench 测试文件

## 4. 验证内容

- 正常序列检测
- 非目标序列输入
- 连续输入与重叠序列
- 复位行为

## 5. 使用工具

- Verilog HDL
- Icarus Verilog
- GTKWave

## 6. 项目总结

记录设计思路、遇到的 Bug、解决过程及仿真验证结果。