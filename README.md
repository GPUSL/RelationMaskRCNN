# Relation Mask R-CNN
This is an implementation of a Relation Mask R-CNN based on [3]. In this repository, we use a special version of Graph Networks implemented inside [Mask R-CNN](https://arxiv.org/abs/1703.06870/)[2], which called GPI ([Graph Permutation Invariant](https://arxiv.org/abs/1802.05451)[1]), that use the structure of graphs for a detection task on [Berkeley Deep Drive](http://bdd-data.berkeley.edu/) dataset.

## Introduction

## Qualitative Results
<img src="qualitive_results.png" width="750">

<img src="scene_interpretability.jpg" width="750">
<img src="scene_interpretability2.png" width="750">

## References
[1] Roei Herzig, Moshiko Raboh, Gal Chechik, Jonathan Berant, Amir Globerson, [Mapping Images to Scene Graphs with Permutation-Invariant Structured Prediction](https://arxiv.org/abs/1802.05451), NIPS, 2018.

[2] Kaiming He, Georgia Gkioxari, Piotr Dollár, Ross Girshick, [Mask R-CNN](https://arxiv.org/abs/1703.06870/), ICCV, 2017.

[3] Abdulla Waleed, [Mask R-CNN for object detection and instance segmentation on Keras and TensorFlow](https://github.com/matterport/Mask_RCNN), 2017.

## Citation
Please cite our git repo if you use this code in your own work:
```
@misc{herzig_relation_maskrcnn,
  title={Relation Mask R-CNN for object detection based on Graph Permutation Invariant},
  author={Herzig, Roei},
  year={2018},
  publisher={Github},
  journal={GitHub repository},
  howpublished={\url{https://github.com/roeiherz/RelationMaskRCNN}},
}
```
