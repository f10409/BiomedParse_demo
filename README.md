# BiomedParse Demo
Zero-shot for medical image segmentation with BiomedParse.

**Po-Chih Kuo & Frank Li** | Datathon 2025

## Usage
```bash
cd ~
git clone https://github.com/f10409/BiomedParse_demo.git
cd ~/BiomedParse_demo
git clone https://github.com/microsoft/BiomedParse
mkdir ~/BiomedParse_demo/BiomedParse/pretrained
cp -f /mnt/efs/data/datasets/BiomedParse/biomedparse_v1.pt ~/BiomedParse_demo/BiomedParse/pretrained/biomedparse_v1.pt
```
Launch Jupyter and select the `biomedparse` kernel to run the demo.

## Installation
If the pre-installed environment doesn't work:
```bash
cd ~/BiomedParse_demo
conda deactivate
uv sync
source .venv/bin/activate
uv add git+https://github.com/facebookresearch/detectron2.git --no-build-isolation
python -m ipykernel install --user --name biomedparse
```
Launch Jupyter and select the `biomedparse` kernel to run the demo.
