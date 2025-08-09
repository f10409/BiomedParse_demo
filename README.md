# BiomedParse_demo

1. cd ~
2. git clone https://github.com/f10409/BiomedParse_demo.git
3. cd ~/BiomedParse_demo
4. conda deactivate
5. uv sync
6. git clone https://github.com/microsoft/BiomedParse
7. source .venv/bin/activate
8. uv add git+https://github.com/facebookresearch/detectron2.git --no-build-isolation
9. python -m ipykernel install --user --name biomedparse