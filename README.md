# Disentangling Foreground-Background Representations for Robust Camouflaged Object Detection

This repository provides partial implementation code and visualization results for our manuscript:

**Disentangling Foreground-Background Representations for Robust Camouflaged Object Detection**

The current repository includes part of the training, testing, evaluation, and network implementation files. The complete training/evaluation code, pretrained models, and additional experimental materials will be progressively released as the manuscript proceeds through the review process.

## Files

- `MyTrain.py`: training script.
- `MyTest.py`: testing script.
- `MyEval.py`: evaluation script.

## Dataset

The datasets used in this work follow the standard benchmark settings. The number of images in the training set and testing set is summarized below.

| Task | Dataset | Train | Test |
|---|---|---:|---:|
| Camouflaged Object Detection | CAMO | 1,000 | 250 |
| Camouflaged Object Detection | CHAMELEON | - | 76 |
| Camouflaged Object Detection | COD10K | 3,040 | 2,026 |
| Camouflaged Object Detection | NC4K | - | 4,121 |
| Salient Object Detection | DUTS | 10,553 | 5,019 |
| Salient Object Detection | DUT-OMRON | - | 5,168 |
| Salient Object Detection | HKU-IS | - | 4,447 |
| Salient Object Detection | ECSSD | - | 1,000 |
| Salient Object Detection | PASCAL-S | - | 850 |

You can find them [here](https://github.com/lartpang/awesome-segmentation-saliency-dataset#camouflaged-object-detection-cod).

## Visualization Results

Representative prediction maps and visualization results are available at:

[https://pan.baidu.com/s/1qYVzoyf_RAstOYJyVSYKIg?pwd=2sfi 提取码: 2sfi](这里替换成你的预测图链接)

## Code Availability

This repository currently provides partial implementation code for reproducibility reference. The complete codebase, pretrained weights, and additional results will be made available after further organization during the review/publication process.
