# 🎯 Cross-Camera Player Mapping

This project performs identity matching of football players across two distinct camera views—**Tacticam** and **Broadcast**—using YOLOv11-based detection, Deep SORT tracking, OSNet ReID embeddings, and optional homography-based spatial alignment.

---

## 🧰 Environment Setup

### ✅ Recommended Environment
- Python 3.8+
- CUDA-enabled GPU for fast inference and embedding extraction
- OS: Linux or Windows (tested on Google Colab and Ubuntu 22.04)

---

## 📦 Dependencies

Install all necessary libraries:

```bash
pip install ultralytics torch torchvision torchreid opencv-python deep_sort_realtime
