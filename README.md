# StackGAN Inception Evaluation model
- [StackGAN-pytorch](https://github.com/hanzhanggit/StackGAN-Pytorch)
- [StackGAN-tensorflow](https://github.com/hanzhanggit/StackGAN)

Inception evaluation model for reproducing main results in the paper [StackGAN: Text to Photo-realistic Image Synthesis with Stacked Generative Adversarial Networks](https://arxiv.org/pdf/1612.03242v2.pdf) by Han Zhang, Tao Xu, Hongsheng Li, Shaoting Zhang, Xiaogang Wang,   Xiaolei Huang, Dimitris Metaxas.


### Dependencies
- python 2.7
- TensorFlow

### Inception Model

- [StackGAN inception model for birds and flowers evaluation](https://drive.google.com/open?id=0B3y_msrWZaXLMzNMNWhWdW0zVWs). Download and save it in the current folder
- StackGAN for COCO. We use the model pretrained on the ImageNet. Same as the one used in [Improved GAN](https://github.com/openai/improved-gan/tree/master/inception_score).



###To get the inception score
python inception_score.py --image_folder IMAGE_FOLDER_PATH




### Citing StackGAN
If you find StackGAN useful in your research, please consider citing:

```
@inproceedings{han2017stackgan,
Author = {Han Zhang and Tao Xu and Hongsheng Li and Shaoting Zhang and Xiaogang Wang and Xiaolei Huang and Dimitris Metaxas},
Title = {StackGAN: Text to Photo-realistic Image Synthesis with Stacked Generative Adversarial Networks},
Year = {2017},
booktitle = {{ICCV}},
}
```

**References**

- Generative Adversarial Text-to-Image Synthesis [Paper](https://arxiv.org/abs/1605.05396) [Code](https://github.com/reedscot/icml2016)
- Learning Deep Representations of Fine-grained Visual Descriptions [Paper](https://arxiv.org/abs/1605.05395) [Code](https://github.com/reedscot/cvpr2016)
- Improved Techniques for Training GANs[ Paper](https://arxiv.org/abs/1606.03498)  [Code](https://github.com/openai/improved-gan)

