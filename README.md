# Towards Attack to the Adversarial Example Based Privacy Protection Schemes
We use the three methods to launch the adversarial example based privacy protection schemes. The methods includes initial transformation of image data, adversarial training and the detection of the adversarial noise. Through our attack, we can give more information to the researchers to develop more robust defenses against the inference attack equipped with the advanced machine learning in the future. The datasets we use include two parts, the first one is the public dataset [MNIST](http://yann.lecun.com/exdb/mnist/). The second one is the dataset used in [AttriGuard](https://arxiv.org/abs/1805.04810), we call the dataset ["Att"](https://github.com/jjy1994/AttriGuard).
## Experimental  Environment
We mainly use the popular machine learn framwork pytorch (1.9.0) to establish the neural network and train the neural network and a Python library [Adversarial Robustness Toolbox](https://arxiv.org/abs/1807.01069) (ART, 1.8.1) to help us produce the adversarial noise. For hardware, CPU Model is Intel Xeon Gold 6142, GPU is NVIDIA GeForce RTX 3080 (10 GB), RAM is 28 GB. We list our experimental environment because we measure the time delay to produce the adversarial noises.
## Code usage
The code mainly include two parts, including MNIST and Att. For MNIST, the code is included in the folder "MNIST", for Att, the code is include in the folder "Att". We use all three different methods to attack for the dataset MNIST, and we use two methods to attack for Att, the one is adversarial training and the another is the detection method.
## Citation
If you use this code or dataset, please cite following paper:
```python
@inproceedings{jia2018attriguard,
  title={{AttriGuard}: A Practical Defense Against Attribute Inference Attacks via Adversarial Machine Learning},
  author={Guangxu Xie},
  booktitle={Towards Attack to the Adversarial Example Based Privacy Protection Schemes},
  year={2021}
}
```
