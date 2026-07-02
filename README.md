The code will be made publicly available after the manuscript is accepted.
This repository provides the **California Central Valley (CCV) dataset** for remote sensing image spatiotemporal fusion.

The CCV dataset was constructed from paired **Sentinel-2** and **Sentinel-3** observations acquired over a representative agricultural region in California's Central Valley, USA. It is designed to evaluate spatiotemporal fusion models under cross-sensor agricultural monitoring scenarios.

## Dataset Organization

The dataset is organized into training, validation, and test subsets:

```text
CCV/
├── train/
│   ├── 2022-07-15_196/
│   ├── 2022-07-20_201/
│   ├── 2022-08-14_226/
│   ├── 2022-08-29_241/
│   ├── 2022-09-03_246/
│   ├── 2022-09-23_266/
│   └── 2022-10-03_276/
│
├── val/
│   ├── 2022-10-13_286/
│   └── 2022-10-23_296/
│
└── test/
    ├── 2022-10-03_276/
    └── 2022-10-13_286/
