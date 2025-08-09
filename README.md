# BiomedParse_demo

1. git clone https://github.com/f10409/BiomedParse_demo.git
2. cd ~/BiomedParse_demo
3. uv sync
4. git clone https://github.com/microsoft/BiomedParse
5. source .venv/bin/activate
6. uv add git+https://github.com/facebookresearch/detectron2.git --no-build-isolation
7. python -m ipykernel install --user --name biomedparse