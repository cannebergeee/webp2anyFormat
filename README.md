# WebP 格式转换工具 (WebP Converter)

一个简单的 Python 桌面工具，用于将 WebP 图片（支持动图）批量转换为 **GIF**、**MP4** 或 **PNG** 格式。

适配 macOS 和 Windows，支持批量处理。

## 📦 安装依赖

复制以下命令在终端运行，安装必要的库：

```bash
pip install Pillow ttkbootstrap opencv-python
注：如果不转换视频，可以不安装 opencv-python。

🚀 如何使用
运行程序：

Bash

python webp_tools_for_mac.py
操作步骤：

选择 “文件夹批量模式” 或 “多文件列表模式”。

在左侧勾选要转换的格式（GIF / MP4 / PNG）。

点击 开始 按钮，完成后会自动打开输出文件夹。

✨ 功能简介
GIF 动图：保留原图动画。

MP4 视频：将动图转为视频文件。

PNG 序列：将动图拆解为每一帧图片。

自动备份：转换时可保留源文件。
