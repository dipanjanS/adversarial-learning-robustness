# Adversarial Robustness in Deep Learning
Contains materials for workshops pertaining to adversarial robustness in deep learning. The following things are covered -

* Deep learning essentials
* Introduction to adversarial perturbations
	* Natural
	* Synthetic [1, 2]
		* Simple Projected Gradient Descent-based attacks
		* Targeted Projected Gradient Descent-based attacks
		* Fast Gradient Sign Method (FGSM) attacks
* Optimizer susceptibility w.r.t to different attacks
* Adversarial learning
	* Training on a dataset pertubed with FGSM
	* Training with Neural Structured Learning [3]
* Improving adversarial performance with EfficientNet [4] and its variants like Noisy Student Training [5] and AdvProp [6]

**Note** that this repository is still in its nascent stage. Over time we will be adding more materials on improving performance with Smooth Adversarial Training [7], text-based attacks, and some notes on the intepretability aspects of adversarial robustness. Also, the materials presented here are solely meant for educational purposes and aren't meant to be used otherwise. 

We provide Jupyter Notebooks to demonstrate the topics mentioned above. These notebook are fully runnable on Google Colab without any non-trivial configurations. 

## How to run the notebooks?

The notebooks are fully runnable on Google Colab. Here are the steps - 
* First, get the [Open in Colab](https://chrome.google.com/webstore/detail/open-in-colab/iogfkhleblhcpcekbiedikdehleodpjo?hl=en) Google Chrome extension. 
* Follow [this screencast](https://www.loom.com/share/602f3d0823ae40e3b6d5a8187d421a37) that shows how to navigate to a particular notebook inside this repository and open it in Google Colab. 

## Major libraries used

* TensorFlow (2.3)
* Neural Structured Learning

## References

1. I. Goodfellow, J. Shlens, C. Szegedy, “Explaining and Harnessing Adversarial Examples,” ICLR 2015.
2. T. Miyato, S. Maeda, M. Koyama and S. Ishii, “Virtual Adversarial Training: A Regularization Method for Supervised and Semi-Supervised Learning,” IEEE Transactions on Pattern Analysis and Machine Intelligence 2019.
3. “Neural Structured Learning.” TensorFlow, https://www.tensorflow.org/neural_structured_learning.
4. Tan, Mingxing, and Quoc V. Le. “EfficientNet: Rethinking Model Scaling for Convolutional Neural Networks.” ArXiv:1905.11946 [Cs, Stat], Sept. 2020. arXiv.org, http://arxiv.org/abs/1905.11946.
5. Xie, Qizhe, et al. “Self-Training with Noisy Student Improves ImageNet Classification.” ArXiv:1911.04252 [Cs, Stat], June 2020. arXiv.org, http://arxiv.org/abs/1911.04252.
6. Xie, Cihang, et al. “Adversarial Examples Improve Image Recognition.” ArXiv:1911.09665 [Cs], Apr. 2020. arXiv.org, http://arxiv.org/abs/1911.09665.
7. Xie, Cihang, et al. “Smooth Adversarial Training.” ArXiv:2006.14536 [Cs], June 2020. arXiv.org, http://arxiv.org/abs/2006.14536.
