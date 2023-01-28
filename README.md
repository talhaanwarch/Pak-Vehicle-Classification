# Pak-Vehicle-Classification
Pakstan Vehicle Classification using different augmentation techniques

## Abstract

Vehicle identification based on make and model is an integral part of an intelligent transport system that helps traffic monitoring and crime control. Much research has been performed in this regard, but most of them used manual feature extraction or ensemble convolution neural networks that result in increased execution time during inference. This paper compared three deep learning models and utilized different augmentation techniques to achieve state-of-the-art performance without ensembling or fusing the models. Experimentations are made without any augmentation, with standard augmentation, and by mixed sample data augmentation techniques. Gradient accumulation and stochastic weighted averaging with mixed precision are used to have a large batch size that helped to reduce training time. The dataset comprised 48 vehicles’ models running on the road of Pakistan. The highest accuracy and F1 score of 97% and 95% using the FMix augmentation technique with EfficientNetV2-S architecture gave the confidence that the proposed solution can be implemented in production. 



## Paper Citation 
```
@article{anwar2023vehicle,
  title={Vehicle make and model recognition using mixed sample data augmentation techniques},
  author={Anwar, Talha and Zakir, Seemab},
  journal={IAES International Journal of Artificial Intelligence},
  volume={12},
  number={1},
  pages={137},
  year={2023},
  publisher={IAES Institute of Advanced Engineering and Science},
  doi={http://doi.org/10.11591/ijai.v12.i1.pp137-145}
}

```
