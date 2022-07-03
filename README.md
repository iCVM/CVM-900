CVM-900: a Cervical Vertebral Maturation Benchmark
==================================================

CVM-900 is a benchmark dataset for Cervical Vertebral Maturation. 900 lateral cephalograms from 6 Cervical Stages (CS) are collected and annotated. The distribution of different stages is showed below:

| Stage | # Images |
| :---: | :------: |
|  CS1  |     85   |
|  CS2  |    135   |
|  CS3  |    100   |
|  CS4  |    200   |
|  CS5  |    180   |
|  CS6  |    200   |

This repo only contains the meta information of the CVM-900 dataset. Check [https://icvm.github.io](https://icvm.github.io) on how to apply for the dataset. The file tree of CVM-900 is as follows:

```
CVM-900
├── README.md
├── annotations
│   ├── CVM-900-Subset.txt
│   ├── CVM-900.txt
│   └── Splits
│       ├── CVM-900-1.txt
│       ├── CVM-900-2.txt
│       ├── CVM-900-3.txt
│       ├── CVM-900-4.txt
│       ├── CVM-900-5.txt
│       ├── CVM-900-Subset-1.txt
│       ├── CVM-900-Subset-2.txt
│       ├── CVM-900-Subset-3.txt
│       ├── CVM-900-Subset-4.txt
│       └── CVM-900-Subset-5.txt
└── images
    ├── CS1
    │   ├── 0000.png
    │   ├── ...
    │   └── 0086.png
    ├── CS2
    │   ├── 0087.png
    │   ├── ...
    │   └── 0224.png
    ├── CS3
    │   ├── 0225.png
    │   ├── ...
    │   └── 0325.png
    ├── CS4
    │   ├── 0326.png
    │   ├── ...
    │   └── 0559.png
    ├── CS5
    │   ├── 0560.png
    │   ├── ...
    │   └── 0758.png
    └── CS6
        ├── 0759.png
        ├── ...
        └── 0962.png
```

`annotations/CVM-900.txt` contains the full set of 900 images, while 'annotations/CVM-900-Subset.txt' is a subset of 508 images. The files in `annotations/Splits` specify the splits for 5-fold cross-validation as described in our paper.

## Citation

```BibTeX
@article{liao2022icvm,
  title={iCVM: An Interpretable Deep Learning Model for CVM Assessment under Label Uncertainty},
  author={Liao, Ni and Dai, Jian and Tang, Yao and Zhong, Qiaoyong and Mo, Shuixue},
  journal={IEEE Journal of Biomedical and Health Informatics},
  year={2022},
  volume={},
  number={},
  pages={},
  doi={10.1109/JBHI.2022.3179619}
}
```
