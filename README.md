
### 4. `yolo-training-inference-toolkit/README.md`

```markdown
# YOLO Training and Inference Toolkit

YOLO 目标检测训练与推理工程工具包。仓库内不包含客户数据集、商业权重或商业模型。

## 功能
- 数据集 YAML 配置与标注格式说明
- 训练/验证脚本
- 指标记录（mAP、loss 等）
- 导出 ONNX
- Python 推理入口
- C++ / ONNX Runtime 推理入口

## 技术栈
Python、PyTorch、Ultralytics YOLO、OpenCV、ONNX Runtime、CMake

## 快速开始
```bash
python train.py --data data.yaml --weights yolov8n.pt
python export.py --weights runs/train/exp/weights/best.pt --include onnx
