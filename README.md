# VimTS

<h3 align="center"> <a href="https://arxiv.org/abs/2404.19652">VimTS: A Unified Video and Image Text Spotter for Enhancing the Cross-domain Generalization</a></h3>


<h5 align="center">

[![arXiv](https://img.shields.io/badge/Arxiv-2404.19652-b31b1b.svg?logo=arXiv)](https://arxiv.org/abs/2404.19652)
[![Project page](https://img.shields.io/badge/Project-Page-white)](https://vimtextspotter.github.io/) 
[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FYuliang-Liu%2FVimTS&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=Visitor&edge_flat=false)](https://hits.seeyoufarm.com)
[![GitHub issues](https://img.shields.io/github/issues/Yuliang-Liu/VimTS?color=critical&label=Issues)](https://github.com/Yuliang-Liu/VimTS/issues?q=is%3Aopen+is%3Aissue)
[![GitHub closed issues](https://img.shields.io/github/issues-closed/Yuliang-Liu/VimTS?color=success&label=Issues)](https://github.com/Yuliang-Liu/VimTS/issues?q=is%3Aissue+is%3Aclosed) <br>
</h5>

<h2></h2>

# Description

VimTS is a unified video and image text spotter for enhancing the cross-domain generalization. It outperforms the state-of-the-art method by an average of 2.6% in six cross-domain benchmarks such as TT-to-IC15, CTW1500-to-TT, and TT-to-CTW1500. For video-level cross-domain adaption, our method even surpasses the previous end-to-end video spotting method in ICDAR2015 video and DSText v2 by an average of 5.5% on the MOTA metric, using only image-level data.

<br>
<p align="center">
    <img src="https://v1.ax1x.com/2024/05/02/7Kixoc.gif" width="666"/>
<p>

## News 
* ```2024.5.1 ``` 🚀 Release paper [VimTS](https://arxiv.org/abs/2404.19652).

## Framework

Overall framework of our method.

<p align="center">
    <img src="https://v1.ax1x.com/2024/05/02/7KihpO.png" width="666"/>
<p>

Overall framework of CoDeF-based synthetic method.

<p align="center">
    <img src="https://v1.ax1x.com/2024/05/02/7KiuUb.png" width="666"/>
<p>

## VTD-368K

We manually collect and filter text-free, open-source and unrestricted videos from NExT-QA, Charades-Ego, Breakfast, A2D, MPI-Cooking, ActorShift and Hollywood. By utilizing the CoDeF, our synthetic method facilitates the achievement of realistic and stable text flow propagation, significantly reducing the occurrence of distortions.


<p align="center">
    <img src="https://v1.ax1x.com/2024/05/02/7KiW25.jpg" width="888"/>
<p>

## Compared with MLMMs

<br>
<p align="center">
    <img src="https://v1.ax1x.com/2024/05/02/7KiKcw.jpg" width="666"/>
<p>
<br>

## Cite
If you wish to refer to the baseline results published here, please use the following BibTeX entries:

```BibTeX
@misc{liuvimts,
          author={Liu, Yuliang and Huang, Mingxin and Yan, Hao and Deng, Linger and Wu, Weijia and Lu, Hao and Shen, Chunhua and Jin, Lianwen and Bai, Xiang},
          title={VimTS: A Unified Video and Image Text Spotter for Enhancing the Cross-domain Generalization}, 
          publisher={arXiv preprint arXiv:2404.19652},
          year={2024},
}
```

## Copyright
We welcome suggestions to help us improve the VimTS. For any query, please contact Prof. Yuliang Liu: ylliu@hust.edu.cn. If you find something interesting, please also feel free to share with us through email or open an issue. Thanks!
