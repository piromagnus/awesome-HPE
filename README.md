# awesome-HPE

This repo will contains curated papers on HPE with links and some informations. I will keep it updated.

## Papers

### Monocular

#### Sapiens (2024)
Links : [Paper](https://arxiv.org/abs/2408.12569) [github](https://github.com/facebookresearch/sapiens)

Vision Transformer pretrained on a private dataset of 300M images. Rather slow.


| Model          | Dataset         | AP   | AR  |
|----------------|-----------------|------|-----|
| 2B             | Coco-WholeBody  | 74.4 | 81  |
| 2B             | Coco            | 82.2 | 86  |


#### TCFormer (2022/2024)
Links : [Paper v1](https://arxiv.org/abs/2204.08680) [Paper v2](https://arxiv.org/pdf/2407.11321) [github](https://github.com/zengwang430521/TCFormer)

Use a combination of Hierarchical Vision Transformer and CNN. Use Clustering-based token module.
fast.


| Model          |Params| Dataset         | AP   | AR  |
|----------------|---|-----------------|------|-----|
| Large             | 62.8M (?) /31.7G FLOPs| Coco-WholeBody  | 65.1 | 74.2  |
| Large              |62.4M / 25.1G FLOPs| Coco(val)        | 77.1 | 81.5|
| Large              |62.4M / 25.1G FLOPs| Coco(test)           | 76.1 | 86.1|


#### RTMPose/RTMW (2023/2024)
Links: [Paper](https://arxiv.org/abs/2307.09697) [rtmw](https://arxiv.org/pdf/2407.08634v1) [github](https://github.com/OpenGVLab/RTMPose)

Use 2d(or 3d) classification (SimCC) to detect the keypoints. Really fast.

| Model          |Size| Dataset         | AP   | AR  |
|----------------|---|-----------------|------|-----|
| RTMW-x |29.3 GFLOPS      | Coco-WholeBody  | 70.2 | 78.1  |
| RTMPose-X* |17.22 GFLOPS / 49.43M          | Coco   | 78.8 | -  |


#### VitPose (2022)
Links : [Paper](https://arxiv.org/abs/2204.12484) [github](https://github.com/ViTAE-Transformer/VitPose)

Plain Vision Transformer with very good performance without much sophisticated architecture. Fast.

| Model          | Dataset         | AP   | AR  |
|----------------|-----------------|------|-----|
| H              | Coco-WholeBody  | 61.2 |  -  |
| H              | Coco            | 79.8 | 84.8  |





### Multi-view
