# Evaluating ResNet-based Speaker Verification Systems through Loss Landscape Visualization
## Loss Landscape


This repository contains the PyTorch code to generate loss landscapes for the master thesis Evaluating ResNet-based Speaker Verification Systems through Loss Landscape Visualization
> Tassia Heuser

The code is based on the github repository [https://github.com/tomgoldstein/loss-landscape](https://github.com/tomgoldstein/loss-landscape) which implements Li et al. paper.
> Hao Li, Zheng Xu, Gavin Taylor, Christoph Studer and Tom Goldstein. [*Visualizing the Loss Landscape of Neural Nets*](https://arxiv.org/abs/1712.09913). NIPS, 2018.

To generate loss landscapes a network architecture and its pre-trained parameters are needed.
To train a new Voxceleb model use the Voxceleb repository
If you need more guidance on the basics on how to utilize this repository, check out tomgoldstein which has a more in depth documentation. This repository maintains the baseline functionallity of tomgoldstein but adds some more options relevant to the master thesis.

## Strucutre
`
├── configs             stores configuration files that are \
│                       passed to plot_surface.py as argument for \
│                       --config instead of typing out all needed parameters \
│
├── voxceleb
│   ├── loss/
│   ├── model/
│   ├── trained_net/    holds parameter files for trained voxceleb networks
│   ├── dataloader
│   └── model_loader
├── dir3
├── file_in_root.ext
└── README.md`

├── example-directory/
│   ├── build/
│   ├── scripts/
│   ├── src/
│   │   ├── backend/
│   │   │   └── server/
│   │   └── frontend/
│   │       ├── js/
│   │       └── styles/
│   └── tests/