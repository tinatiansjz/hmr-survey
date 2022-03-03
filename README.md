<div align="center">

# Recovering 3D Human Pose and Shape from Monocular Images: A Survey

[Yating Tian](https://github.com/Tina-Husky), [Hongwen Zhang](https://hongwenzhang.github.io), [Yebin Liu](http://www.liuyebin.com), [Limin Wang](https://wanglimin.github.io)

### [Introduction](#introduction) | [Datasets](#datasets) | [Chronological Overview](#overview) | [Benchmarks](#benchmarks)

</div>

## Introduction

Understanding human from monocular images is a long-standing problem in computer vision. With the success of statistical body models, 3D human pose and shape recovery has been drawing broader attention. In order to obtain well-aligned and physically plausible results, two paradigms have been developed to overcome challenges in the 2D-to-3D lifting process: i) an optimization-based paradigm, where different data terms and regularization terms are exploited as optimization objectives; and ii) a regression-based paradigm, where deep learning techniques are embraced to solve the problem in an end-to-end fashion. Meanwhile, continuous efforts are devoted to improving the quality of pose and shape labels for a wide range of datasets. Though remarkable progress has been achieved in the past few decades, the task is still challenging due to flexible body motions, diverse appearances, complex environments, and insufficient in-the-wild annotations. To the best of our knowledge, this is the first survey to focus on the task of monocular 3D human pose and shape recovery. We start with the introduction of body models, and then introduce recovery frameworks and training objectives by providing in-depth analysis of their strengths and weaknesses. We also summarize datasets, evaluation metrics, and benchmark results. Open issues and future directions are discussed in the end, hoping to motivate researchers and facilitate their research in this area.


This repo will be continuously maintained. Please feel free to create issues if you have any suggestions!


## Datasets

#### Summary of the Datasets

<p align="center"> <img src="./assets/datasets.png" width="95%"> </p>

## Overview

### Chronological Overview

<p align="center"> <img src="./assets/timeline.png" width="95%"> </p>

## Benchmarks

<p align="center"> <img src="./assets/benchmarks.png" width="95%"> </p>


## Citation

If our survey helps in your research, please consider citing the following paper:

    @article{tian2022hmrsurvey,
      title = {Recovering 3D Human Mesh from Monocular Images: A Survey},
      author = {Tian, Yating and Zhang, Hongwen and Liu, Yebin and Wang, limin},
      year = {2022},
    }