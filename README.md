# BachGAN_2020
Orignaly proposed as BachGAN: High-Resolution Image Synthesis from Salient Object Layout by Yandong Li, Yu Cheng, Zhe Gan, Licheng Yu, Liqiang Wang, and Jingjing Liu In CVPR 2020.(https://github.com/Cold-Winter/BachGAN)
We worked on this as a Turm Project while attending BITS-F464 Machine Learning Course at BITS Pilani.
## 1. Liturature Review 
Youtube Link for our Liturature Review presentation
https://youtu.be/6NnPPC7ZoC8

## 2. Our Implementation using google Colab
Youtube Link for our Implementation presentation
https://youtu.be/yVuTqFrwnoI

Our Results

![result](https://user-images.githubusercontent.com/51713877/100012379-325d1600-2df9-11eb-8299-c91449620141.PNG)

### Requirements
torch>=1.0.0
torchvision
dominate>=2.3.1
dill
scikit-image

### Datastes
1. ADE20K 
2. Cityscapes
## 3.Proposals from innovations
1. Improving the resolution further:- Can be done using SRCNNs. this will incerese the resalution of the image to 512x512.

our results for increseing the resulation

![srcnn](https://user-images.githubusercontent.com/51713877/100012871-faa29e00-2df9-11eb-8f64-8ff3a6c9f296.PNG)

2.Disentanglement of foreground from background.
3.Using alternate loss function.
4.Generating animated characters.
5.Incorporating text to object layout converter in the existing model.

### Citation
@inproceedings{li2020BachGAN,
  title={BachGAN: High-Resolution Image Synthesis from Salient Object Layout},
  author={Li, Yandong and Cheng, Yu and Gan, Zhe and Yu, Licheng and Wang, Liqiang and Liu, Jingjing},
  booktitle={Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition},
  year={2020}
}
