# 高斯泼溅三维建模手机 App

本仓库用于开发一个可调用手机摄像头、对真实三维世界进行高斯泼溅（Gaussian Splatting）建模的移动端应用。

## 目标

- 通过手机摄像头采集视频帧 + 位姿信息。
- 在移动端或边缘端完成增量式重建与高斯泼溅训练。
- 在移动端实时预览重建效果，并支持导出结果。

## 快速开始

当前仓库仅包含设计文档与规划说明，尚未初始化具体工程。

- 设计文档：`docs/gaussian-splatting-app.md`

## 后续计划

- 选型：原生（iOS/Android）或跨平台（Flutter/React Native）
- 视觉前端：ARKit/ARCore 获取位姿与深度
- 重建与训练：本地/云端混合管线
- 渲染：Metal/Vulkan/Unity 渲染高斯点云

