# Summary-of-Re-ID-papers-and-codes
The repository for Re-ID research. Re-ID may consist of many tasks for Re-ID from many papers. 



# Re-ID Baseline

1.【郑哲东大佬，非常适合新手 】

- **知乎：**[信息门下迷妹：从零开始行人重识别](https://zhuanlan.zhihu.com/p/50387521)
- **代码：**[【郑哲东大佬的baseline 】](https://github.com/layumi/Person_reID_baseline_pytorch)

2.【罗浩大佬的strong baseline】

- **知乎：**[罗浩.ZJU：一个更加强力的ReID Baseline](https://zhuanlan.zhihu.com/p/61831669)
- **代码：**[罗浩大佬的strong baseline](https://github.com/michuanhaohao/reid-strong-baseline)

3.[【fastreid 京东，比较工程化，适合大佬】](https://github.com/JDAI-CV/fast-reid)

4.[【轻量级reid】](https://github.com/wangguanan/light-reid)

5.[【deep-person-reid】](https://github.com/KaiyangZhou/deep-person-reid)



# Video-based Person Re-identification

- ## MARS

| 期刊/会议 | 年份 |  方法名   | Rank-1 | Rank-5 | Rank-10 | Rank-20 | mAP  |
| :-------: | :--: | :-------: | :----: | :----: | :-----: | :-----: | :--: |
|   CVPR    | 2021 |    GRL    |  91.0  |  96.7  |    –    |  98.4   | 84.8 |
|   ECCV    | 2020 |  TCLNet   |  89.8  |   –    |    –    |    –    | 85.1 |
|   ECCV    | 2020 |    AFA    |  90.2  |  96.6  |    –    |    –    | 82.9 |
|   CVPR    | 2020 |   STGCN   |  89.9  |   –    |    –    |    –    | 83.7 |
|   CVPR    | 2020 |   MGRA    |  88.8  |  97.0  |    –    |  98.5   | 85.9 |
|   ICCV    | 2019 |   COSAM   |  84.9  |  95.5  |    –    |  97.9   | 79.9 |
|   ICCV    | 2019 |   GLTR    |  87.0  |  95.8  |    –    |  98.2   | 78.5 |
|   CVPR    | 2019 |   VRSTC   |  88.5  |  96.5  |    –    |  97.4   | 82.3 |
|   CVPR    | 2019 | Attribute |  87.0  |  95.4  |    –    |  98.7   | 78.2 |
|   AAAI    | 2019 |    STA    |  86.3  |  95.7  |    –    |  98.1   | 80.8 |
|   AAAI    | 2019 |    M3D    |  84.3  |  93.8  |    –    |  97.7   | 74.0 |
|   AAAI    | 2019 |   STMP    |  84.4  |  93.2  |    –    |  96.3   | 72.7 |
|   CVPR    | 2018 |   STAN    |  82.3  |   –    |    –    |    –    | 65.8 |
|   CVPR    | 2018 | Snippnet  |  86.3  |  94.7  |    –    |  98.2   | 76.1 |
|   ICCV    | 2017 |   ASTPN   |   44   |   70   |    –    |   81    |  –   |
|   CVPR    | 2017 | SeeForest |  70.6  |  90.0  |    –    |  97.6   | 50.7 |

> Existing methods usually focus on the most conspicuous image regions, thus they may easily miss out fine-grained clues due to the person varieties in image sequences.

**CVPR2021【GRL】**[Watching You: Global-guided Reciprocal Learning for Video-based Person Re-identification](https://arxiv.org/abs/2103.04337)

[code](https://github.com/flysnowtiger/GRL) 



