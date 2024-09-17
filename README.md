# CYTOARK: Cytoarchitecture analysis in Python

![DALL·E 2024-03-28 08 42 27 - brain cells, neurons and axons like planets and stars, animals like monkeys dolphins and mice in the space, colorful, expressive oil painting](https://github.com/Vadori/cytoark/assets/36676465/8bed4528-ffea-49c8-81b9-e457b0d32bf3)

**Cytoark** aims to collect tools for the automatic analysis of histological data. The focus is on the cytoarchitecture of the brain for comparative neuroanatomy. The main component right now is **CISCA**, an instance segmentation and classification model described [here](https://www.arxiv.org/abs/2409.04175)

## CISCA

Delineating and classifying individual cells in microscopy tissue images is a complex task, yet it is a pivotal endeavor in various medical and biological investigations. We propose a new deep learning framework (CISCA) for automatic cell instance segmentation and classification in histological slices to support detailed morphological and structural analysis or straightforward cell counting in digital pathology workflows and brain cytoarchitecture studies. At the core of CISCA lies a network architecture featuring a lightweight U-Net with three heads in the decoder. The first head classifies pixels into boundaries between neighboring cells, cell bodies, and background, while the second head regresses four distance maps along four directions. The network outputs from the first and second heads are integrated through a tailored post-processing step, which ultimately yields the segmentation of individual cells. A third head enables simultaneous classification of cells into relevant classes, if required. We showcase the effectiveness of our method using four datasets, including CoNIC, PanNuke, and MoNuSeg, which are publicly available H\&E datasets. Additionally, we introduce CytoDArk0, a novel dataset consisting of Nissl-stained images of the cortex, cerebellum, and hippocampus from mammals belonging to the orders Cetartiodactyla and Primates. We evaluate CISCA in comparison to other state-of-the-art methods, demonstrating CISCA's robustness and accuracy in segmenting and classifying cells across diverse tissue types, magnifications, and staining techniques.

## Getting Started

### Dependencies

### Installing

### Executing program

## License

This project is licensed under the [NAME HERE] License - see the LICENSE.md file for details

## Acknowledgments



