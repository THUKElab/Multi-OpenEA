# LODEME
![](https://img.shields.io/badge/version-1.0.1-blue)
[![Pytorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?e&logo=PyTorch&logoColor=white)](https://pytorch.org/)
[![ICASSP023](https://img.shields.io/badge/ICASSP-2023-%23bd9f65?labelColor=%23bea066&color=%23ffffff)](https://2023.ieeeicassp.org/)

- [*Vision, Deduction and Alignment: An Empirical Study on Multi-modal Knowledge Graph Alignment*](https://arxiv.org/abs/2302.08774)
>Entity alignment (EA) for knowledge graphs (KGs) plays a critical role in knowledge engineering. Existing EA methods mostly focus on utilizing the graph structures and entity attributes (including literals), but ignore images that are common in modern multi-modal KGs. In this study **we first constructed Multi-OpenEA — eight large-scale, image-equipped EA benchmarks**, and then evaluated some existing embedding-based methods for utilizing images. In view of the complementary nature of visual modal information and logical deduction, we further developed a new multi-modal EA method named  **`LODEME`** **using logical deduction and multimodal KG embedding**, with state-of-the-art performance achieved on Multi-OpenEA and other existing multi-modal EA benchmarks.

## 🚀 Code for LODEME
>The code is currently being organized and refined. Once the code is ready, it will be made available on this repository. Thank you for your patience and understanding.

## 📚 Dataset (Multi-OpenEA)

>We proposed a generic multi-modal EA benchmarks construction process and constructed new multi-modal EA benchmarks based on the eight existing OpenEA benchmarks by adding multiple images to each entity.
>
>Our Multi-OpenEA benchmarks vs the existing multi-modal EA benchmarks. Ours have larger scale (#Entity), more enti-
>ties associated with images (Coverage), and more images per entity (Ratio).


| Benchmark                         | KGs         | #Entity | #Images | Ratio  | Coverage | Similarity |
| --------------------------------- | ----------- | ------- | ------- | ------ | -------- | ---------- |
| FB15K-DB15K \cite{chen2020mmea}   | FB15K       | 14,951  | 13,444  | 0.899  | 90.0%    | -          |
|                                   | DB15K       | 12,842  | 12,837  | 0.999  | 99.9%    |            |
| DBP-WD(norm) \cite{liu2021visual} | DBP         | 15,000  | 8,517   | 0.517  | 57.1%    | -          |
|                                   | WD          | 15,000  | 8,791   | 0.586  | 58.6%    |            |
| EN-FR-15K-V1                      | EN15K(V1)   | 15,000  | 44,657  | 2.977  | 99.7%    | 0.757      |
|                                   | FR15K(V1)   | 15,000  | 42,286  | 2.819  | 94.5%    |            |
| EN-FR-15K-V2                      | EN15K(V2)   | 15,000  | 44,932  | 2.995  | 99.9%    | 0.767      |
|                                   | FR15K(V2)   | 15,000  | 42,622  | 2.841  | 94.5%    |            |
| EN-FR-100K-V1                     | EN100K(V1)  | 100,000 | 296,934 | 2.969  | 99.6%    | 0.751      |
|                                   | FR100K(V1)  | 100,000 | 280,288 | 2.803  | 94.1%    |            |
| EN-FR-100K-V2                     | EN100K(V2)  | 100,000 | 299,403 | 2.994  | 99.9%    | 0.752      |
|                                   | FR100K(V2)  | 100,000 | 282,063 | 2.821  | 94.4%    |            |
| D-W-15K-V1                        | DBP15K(V1)  | 15,000  | 44,776  | 2.985  | 99.8%    | 0.829      |
|                                   | WD15K(V1)   | 15,000  | 44,823  | 2.988  | 99.8%    |            |
| D-W-15K-V2                        | DBP15K(V2)  | 15,000  | 44,911  | 2.994  | 99.9%    | 0.820      |
|                                   | WD15K(V2)   | 15,000  | 44,945  | 2.996  | 99.9%    |            |
| D-W-100K-V1                       | DBP100K(V1) | 100,000 | 296,749 | 2.9867 | 99.5%    | 0.833      |
|                                   | WD100K(V1)  | 100,000 | 297,354 | 2.974  | 99.6%    |            |
| D-W-100K-V2                       | DBP100K(V2) | 100,000 | 299,338 | 2.993  | 99.9%    | 0.832      |
|                                   | WD100K(V2)  | 100,000 | 299,607 | 2.996  | 99.9%    |            |

❗NOTE: The organisation of the data is consistent with OpenEA Dataset v1.1 and the text portion can be downloaded directly from [*OpenEA*](https://github.com/nju-websoft/OpenEA). Download the image embedding via CLIP encoding from [*Baidu Cloud Drive*](https://pan.baidu.com/s/1SUgFfObgHCtgk4hn-rBiBQ), with the pass code **`tuds`** and the raw images from [*Baidu Cloud Drive*](https://pan.baidu.com/s/1oikW9BlutAvfJHcfMLDcDQ), with the pass code **`aoo1`** 

## 🤝 Cite:

Please condiser citing this paper if you use the ```code``` or ```data``` from our work.
Thanks a lot :)

```bigquery
@inproceedings{li2023vision,
  title={Vision, Deduction and Alignment: An Empirical Study on Multi-Modal Knowledge Graph Alignment},
  author={Li, Yangning and Chen, Jiaoyan and Li, Yinghui and Xiang, Yuejia and Chen, Xi and Zheng, Hai-Tao},
  booktitle={ICASSP 2023-2023 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)},
  pages={1--5},
  year={2023},
  organization={IEEE}
}
```

## 💡 Acknowledgement
- We appreciate [```OpenEA```](https://github.com/nju-websoft/OpenEA), [```PRASE```](https://github.com/qizhyuan/PRASEMap), [```EVA```](https://github.com/cambridgeltl/eva), and many other related works for their open-source contributions.

