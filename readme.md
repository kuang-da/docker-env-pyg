# Readme

This repository is a demo for setting up a VSCode Dev Container with [PyG](https://pytorch-geometric.readthedocs.io/en/latest/). The container is based on NVIDIA's PyTorch Docker image. To solve PyG's `NoneType` [AttributeError](https://github.com/rusty1s/pytorch_sparse/issues/127), and torch-sparse's [Import Error], I removed all the torch dependencies in NVIDIA's image. Then I select a combination from the PyG's wheel list(`https://data.pyg.org/whl/`), which is `torch-1.12.0+cu102`.
