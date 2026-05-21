# Medical Image Segmentation with U-Net

A from-scratch implementation and study of U-Net architectures for 
semantic segmentation, progressing from a warm-up car-masking task 
to real medical imaging benchmarks.

## 🎯 Goals
- Implement U-Net from scratch in PyTorch (no high-level wrappers like `segmentation_models_pytorch`)
- Combine U-Net with a custom ResNet encoder backbone
- Benchmark on Carvana → ISIC (skin lesion) → Kvasir-SEG (polyp) datasets
- Compare against modern baselines (SegFormer, Swin-UNet)

## 📂 Project Structure
## 🛠️ Setup
```bash
conda create -n cv python=3.11
conda activate cv
pip install -r requirements.txt
```

## 📊 Datasets
| Dataset | Task | Status |
|---------|------|--------|
| Carvana | Car/background binary segmentation (warm-up) | 🔄 In progress |
| ISIC 2018 | Skin lesion segmentation | ⏳ Planned |
| Kvasir-SEG | Polyp segmentation | ⏳ Planned |

## 📈 Results
*Coming soon — work in progress.*

## 🧑‍💻 Author
Chang — MSc Computer Science, TU Dresden