# Removing visual occlusion of construction scaffolds via a two-step method combining semantic segmentation and image inpainting
[Paper](https://www.researchgate.net/publication/387754791_Removing_visual_occlusion_of_construction_scaffolds_via_a_two-step_method_combining_semantic_segmentation_and_image_inpainting) | [Dataset](#dataset) | [Citation](#citation)


## Introduction
![image](https://github.com/user-attachments/assets/60bc8345-a4a0-453f-b45e-084bed371d1d)

With increasing computer vision (CV) applications in automated construction management, the visual occlusion issue caused by crisscrossing, wide-coverage, and immovable scaffolds has become one of the most challenging. This study proposes a novel deep learning-based two-step method combining pixel-level semantic segmentation and contextual image inpainting to remove scaffolds visually and restore the occluded visual information. A low-cost data synthesis method using only unlabeled data has also been developed to alleviate the shortage of labeled data for deep neural network (DNN) training. Experiments on the synthesized test data show that the proposed method achieves performances of 92% mean intersection over union (MIoU) for scaffold segmentation and over 82% structural similarity (SSIM) for scene restoration after removing scaffolds. This research set a precedent for addressing the visual occlusion issue of scaffolds, and the proposed method is verified in real-world cases that it helps existing CV models perform better in scaffolding scenarios.

**Keywords**: Construction management, Computer vision, Deep neural network, Scaffold occlusion, Semantic segmentation, Image inpainting


## Dataset
<div align="center">
      <img src="https://github.com/user-attachments/assets/842f9070-6462-4566-8cd4-efe22e048412" width=300 alt="scaffold_png" />
      <img src="https://github.com/user-attachments/assets/7e3ef9af-a6b9-4901-8d06-dccb15b6a2a4" width=300 alt="construction-activities" />
      <img src="https://github.com/user-attachments/assets/8a85ad42-7d75-4f2d-8c46-9c4e7d40c581" width=300 alt="scaffolding-activities" />
</div>
<br>



The dataset can be accessed:
- at the [TeraBox](https://terabox.com/s/1Hx4K6hRUuoYf596lOZDOGw).
- or, at the [Baidu Netdisk](https://pan.baidu.com/s/1WjF_Mijy0A5f9y6KqXDBbQ) using the code: **id1q**


## Citation
Please cite our work if you find the dataset useful.
```
@article{DING2025109983,
      title = {Removing visual occlusion of construction scaffolds via a two-step method combining semantic segmentation and image inpainting},
      journal = {Engineering Applications of Artificial Intelligence},
      volume = {142},
      pages = {109983},
      year = {2025},
      issn = {0952-1976},
      doi = {https://doi.org/10.1016/j.engappai.2024.109983},
      url = {https://www.sciencedirect.com/science/article/pii/S0952197624021420},
      author = {Yuexiong Ding and Muyang Liu and Ming Zhang and Xiaowei Luo},
}
```
