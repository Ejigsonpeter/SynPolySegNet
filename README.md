# SynPolySegNet

A multi-architecture framework for automated polyp segmentation combining synthetic data generation (Stable Diffusion + SAM) with Faster R-CNN detection and five segmentation models.

## Overview

SynPolySegNet is a comprehensive framework for medical image segmentation that addresses the challenges of limited datasets through synthetic data generation. The system combines multiple state-of-the-art architectures with automated ground truth generation for robust polyp detection and segmentation.

## Features

- Synthetic data generation using fine-tuned Stable Diffusion
- Automated ground truth generation with SAM
- Multi-architecture segmentation framework including:
  - U-Net
  - PSPNet
  - FPN
  - LinkNet
  - MANet
- Faster R-CNN detection pipeline
- Comprehensive evaluation metrics system

## Performance

- Detection Performance:
  - Recall: 93.08%
  - Precision: 88.97%
  - F1 Score: 90.98%

- Best Segmentation Performance (FPN):
  - PSNR: 7.205893
  - SSIM: 0.492381
  - Precision: 77.00%

## Dataset
 - Link : https://drive.google.com/drive/folders/1MJVT0yRlz0mfwbxLWTqCD7idRcTV3hIY?usp=sharing
## Installation

```bash
# Clone the repository
git clone https://github.com/username/SynPolySegNet.git
cd SynPolySegNet

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```


## Citation

If you use this work in your research, please cite:

```bibtex
@article{synpolysegnet2024,
  title={Synthetic Data-Driven Multi-Architecture Framework for Automated Polyp Segmentation},
  author={[Ejiga Peter]},
  journal={[Journal Name]},
  year={2024}
}
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Segment Anything Model (SAM)](https://segment-anything.com/)
- [Stable Diffusion](https://stabilityai.com/)
- [PyTorch](https://pytorch.org/)

## Contact

For questions and feedback, please open an issue or contact [ojeji1@morgan.edu].

## Contributing

We welcome contributions! Please read our [contributing guidelines](CONTRIBUTING.md) before submitting a pull request.

---
Made with ❤️ for advancing medical image analysis
