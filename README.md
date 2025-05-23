# 批量快速将多张BMP图片合并转换为BIN文件

## 描述

本资源文件提供了一个批量快速将多张BMP图片转换为BIN文件的工具。该工具适用于需要将多张24位深度的BMP图片转换为BIN文件的场景，BIN文件可以选择8位（RGB323）、16位（RGB565）或24位（RGB888）输出格式。生成的BIN文件可用于烧录到外部Flash存储器中，供单片机读取并显示图像。

## 功能特点

- **批量处理**：支持同时处理多张BMP图片，快速生成对应的BIN文件。
- **多种输出格式**：支持8位（RGB323）、16位（RGB565）和24位（RGB888）三种输出格式，满足不同需求。
- **图片信息记录**：生成的BIN文件中包含每张图片在Flash中的起始位置、图片尺寸和大小信息，方便单片机读取和显示。
- **枚举索引**：每张图片的枚举索引与图片文件名一同记录，便于快速图像化处理和单片机图形界面的开发。

## 适用场景

- 单片机图形界面开发：适用于需要将多张图片烧录到外部Flash中，并通过单片机读取和显示的场景。
- 嵌入式系统开发：适用于嵌入式系统中需要快速加载和显示多张图片的应用。

## 使用说明

1. **准备BMP图片**：确保所有待处理的BMP图片均为24位深度。
2. **运行工具**：使用本工具进行批量转换，选择所需的输出格式（8位、16位或24位）。
3. **生成BIN文件**：工具将自动生成包含所有图片信息的BIN文件，并记录每张图片的起始位置、尺寸和大小。
4. **烧录到Flash**：将生成的BIN文件烧录到外部Flash中，供单片机读取和显示。

## 注意事项

- 确保输入的BMP图片均为24位深度，否则可能导致转换失败或输出格式不正确。
- 在选择输出格式时，根据实际需求选择合适的位深度，以平衡图像质量和存储空间。

通过本工具，您可以快速、高效地将多张bMP图片转换为BIN文件，极大地方便了单片机图形界面的开发和嵌入式系统的应用。

## 下载链接
[批量快速将多张BMP图片合并转换为BIN文件](https://pan.quark.cn/s/08dc718319ff) 

(备用: [备用下载](https://pan.baidu.com/s/1yVOpdU2bRqGJrLcSK1YOmQ?pwd=1234))

## 说明

该仓库仅用于学习交流，请勿用于商业用途。
