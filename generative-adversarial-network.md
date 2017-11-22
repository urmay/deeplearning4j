---
title: Generative Adversarial Networks
layout: default
redirect_from: gan
---

# Generative Adversarial Networks (GANs)

Generative adversarial networks (GANs) are two-part neural networks capable of unsupervised learning that pit one net against the other, thus the "adversarial." 

One neural network called the generator generates data instances and the other, called the discriminator, evaluates them for authenticity; i.e. the discriminator decides whether they belong to the unlabeled training dataset or not. 

For example, the generative network might create images and the evaluating network would accept or reject them, in what is essentially an [actor-critic model](https://arxiv.org/abs/1610.01945). Both nets are trying to optimize a different and opposing objective, or loss, function. 

[GANs were introduced in a paper](https://arxiv.org/abs/1406.2661) by Ian Goodfellow and other researchers at the University of Montreal, including Yoshua Bengio, in 2014. Goodfellow, Bengio and Aaron Courville co-authored [a well-known deep learning textbook](http://www.deeplearningbook.org/). 

While difficult to tune and therefore to use, GANs have stimulated a lot of [interesting research and writing](https://blog.openai.com/generative-models/). 

## GAN Use Cases

* [Text to Image Generation](https://arxiv.org/abs/1605.05396)
* [Image to Image Translation](https://arxiv.org/abs/1611.07004)
* [Increasing Image Resolution](https://arxiv.org/abs/1609.04802)
* [Predicting Next Video Frame]( https://arxiv.org/abs/1511.06380)

## Notable Papers on GANs

* [Generative Adversarial Nets] [[Paper]](https://arxiv.org/abs/1406.2661)
[[Code]](https://github.com/goodfeli/adversarial)(Ian Goodfellow's breakthrough paper)

### Unclassified Papers

* Deep Generative Image Models using a Laplacian Pyramid of Adversarial Networks] [[Paper]](https://arxiv.org/abs/1506.05751)[[Code]](https://github.com/facebook/eyescream)

* [Adversarial Autoencoders] [[Paper]](http://arxiv.org/abs/1511.05644)[[Code]](https://github.com/musyoku/adversarial-autoencoder)

* [Generating Images with Perceptual Similarity Metrics based on Deep Networks] [[Paper]](https://arxiv.org/pdf/1602.02644v2.pdf)

* [Generating images with recurrent adversarial networks] [[Paper]](https://arxiv.org/abs/1602.05110)[[Code]](https://github.com/ofirnachum/sequence_gan)

* [Generative Visual Manipulation on the Natural Image Manifold] [[Paper]](https://people.eecs.berkeley.edu/~junyanz/projects/gvm/eccv16_gvm.pdf)[[Code]](https://github.com/junyanz/iGAN)

* [Learning What and Where to Draw] [[Paper]](http://www.scottreed.info/files/nips2016.pdf)[[Code]](https://github.com/reedscot/nips2016)

* [Adversarial Training for Sketch Retrieval] [[Paper]](http://link.springer.com/chapter/10.1007/978-3-319-46604-0_55)

* [Generative Image Modeling using Style and Structure Adversarial Networks] [[Paper]](https://arxiv.org/pdf/1603.05631.pdf)[[Code]](https://github.com/xiaolonw/ss-gan)

* [Generative Adversarial Networks as Variational Training of Energy Based Models] [[Paper]](http://www.mathpubs.com/detail/1611.01799v1/Generative-Adversarial-Networks-as-Variational-Training-of-Energy-Based-Models)(ICLR 2017)

* [Synthesizing the preferred inputs for neurons in neural networks via deep generator networks] [[Paper]](https://arxiv.org/pdf/1605.09304v5.pdf)[[Code]](https://github.com/Evolving-AI-Lab/synthesizing)

* [SalGAN: Visual Saliency Prediction with Generative Adversarial Networks] [[Paper]](https://arxiv.org/abs/1701.01081)[[Code]](https://github.com/imatge-upc/saliency-salgan-2017)

* [Adversarial Feature Learning] [[Paper]](https://arxiv.org/abs/1605.09782)

### Generating High-Quality Images

* [Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks] [[Paper]](https://arxiv.org/abs/1511.06434)[[Code]](https://github.com/jacobgil/keras-dcgan)(Gan with convolutional networks)(ICLR)

* [Generative Adversarial Text to Image Synthesis] [[Paper]](https://arxiv.org/abs/1605.05396)[[Code]](https://github.com/reedscot/icml2016)[[Code]](https://github.com/paarthneekhara/text-to-image)

* [Improved Techniques for Training GANs] [[Paper]](https://arxiv.org/abs/1606.03498)[[Code]](https://github.com/openai/improved-gan)(Goodfellow's paper)

* [Plug & Play Generative Networks: Conditional Iterative Generation of Images in Latent Space] [[Paper]](https://arxiv.org/abs/1612.00005v1)[[Code]](https://github.com/Evolving-AI-Lab/ppgn)

* [StackGAN: Text to Photo-realistic Image Synthesis with Stacked Generative Adversarial Networks] [[Paper]](https://arxiv.org/pdf/1612.03242v1.pdf)[[Code]](https://github.com/hanzhanggit/StackGAN)

* [Improved Training of Wasserstein GANs] [[Paper]](https://arxiv.org/abs/1704.00028)[[Code]](https://github.com/igul222/improved_wgan_training)

* [Boundary Equibilibrium Generative Adversarial Networks Implementation in Tensorflow] [[Paper]](https://arxiv.org/abs/1703.10717)[[Code]](https://github.com/artcg/BEGAN)

* [Progressive Growing of GANs for Improved Quality, Stability, and Variation ] [[Paper]](http://research.nvidia.com/publication/2017-10_Progressive-Growing-of)[[Code]](https://github.com/tkarras/progressive_growing_of_gans)

### Semi-supervised learning

* [Adversarial Training Methods for Semi-Supervised Text Classification] [[Paper]](https://arxiv.org/abs/1605.07725)[[Note]](https://github.com/dennybritz/deeplearning-papernotes/blob/master/notes/adversarial-text-classification.md)( Ian Goodfellow Paper)

* [Improved Techniques for Training GANs] [[Paper]](https://arxiv.org/abs/1606.03498)[[Code]](https://github.com/openai/improved-gan)(Goodfellow's paper)

* [Unsupervised and Semi-supervised Learning with Categorical Generative Adversarial Networks] [[Paper]](https://arxiv.org/abs/1511.06390)(ICLR)

* [Semi-Supervised QA with Generative Domain-Adaptive Nets] [[Paper]](https://arxiv.org/abs/1702.02206)(ACL 2017)

### Ensembles

* [AdaGAN: Boosting Generative Models] [[Paper]](https://arxiv.org/abs/1701.02386)[[Code]]（Google Brain）

### Clustering

* [Unsupervised and Semi-supervised Learning with Categorical Generative Adversarial Networks] [[Paper]](https://arxiv.org/abs/1511.06390)(ICLR)

### Image blending

* [GP-GAN: Towards Realistic High-Resolution Image Blending] [[Paper]](https://arxiv.org/abs/1703.07195)[[Code]](https://github.com/wuhuikai/GP-GAN)

### Image Inpainting

* [Semantic Image Inpainting with Perceptual and Contextual Losses] [[Paper]](https://arxiv.org/abs/1607.07539)[[Code]](https://github.com/bamos/dcgan-completion.tensorflow)(CVPR 2017)

* [Context Encoders: Feature Learning by Inpainting] [[Paper]](https://arxiv.org/abs/1604.07379)[[Code]](https://github.com/jazzsaxmafia/Inpainting)

* [Semi-Supervised Learning with Context-Conditional Generative Adversarial Networks] [[Paper]](https://arxiv.org/abs/1611.06430v1)

* [Generative face completion] [[Paper]](https://drive.google.com/file/d/0B8_MZ8a8aoSeenVrYkpCdnFRVms/edit)[[Code]](https://github.com/Yijunmaverick/GenerativeFaceCompletion)(CVPR2017)

* [Globally and Locally Consistent Image Completion] [[MainPAGE]](http://hi.cs.waseda.ac.jp/~iizuka/projects/completion/en/)(SIGGRAPH 2017)

### Joint Probability

* [Adversarially Learned Inference][[Paper]](https://arxiv.org/abs/1606.00704)[[Code]](https://github.com/IshmaelBelghazi/ALI)

### Super-Resolution

* [Image super-resolution through deep learning ][[Code]](https://github.com/david-gpu/srez)(Just for face dataset)

* [Photo-Realistic Single Image Super-Resolution Using a Generative Adversarial Network] [[Paper]](https://arxiv.org/abs/1609.04802)[[Code]](https://github.com/leehomyc/Photo-Realistic-Super-Resoluton)（Using Deep residual network）

* [EnhanceGAN] [Docs](https://medium.com/@richardherbert/faces-from-noise-super-enhancing-8x8-images-with-enhancegan-ebda015bb5e0#.io6pskvin)[[Code]]

### De-occlusion

* [Robust LSTM-Autoencoders for Face De-Occlusion in the Wild] [[Paper]](https://arxiv.org/abs/1612.08534)

### Semantic Segmentation

* [Adversarial Deep Structural Networks for Mammographic Mass Segmentation] [[Paper]](https://arxiv.org/abs/1612.05970)[[Code]](https://github.com/wentaozhu/adversarial-deep-structural-networks)

* [Semantic Segmentation using Adversarial Networks] [[Paper]](https://arxiv.org/abs/1611.08408)（Soumith's paper）

### Object Detection

* [Perceptual generative adversarial networks for small object detection] [[Paper]](https://arxiv.org/abs/1706.05274v2)(CVPR 2017)

* [A-Fast-RCNN: Hard Positive Generation via Adversary for Object Detection] [[Paper]](http://abhinavsh.info/papers/pdfs/adversarial_object_detection.pdf)[[Code]](https://github.com/xiaolonw/adversarial-frcnn)(CVPR2017)

### RNN-GANs

* [C-RNN-GAN: Continuous recurrent neural networks with adversarial training] [[Paper]](https://arxiv.org/abs/1611.09904)[[Code]](https://github.com/olofmogren/c-rnn-gan)

### Conditional Adversarial Nets

* [Conditional Generative Adversarial Nets] [[Paper]](https://arxiv.org/abs/1411.1784)[[Code]](https://github.com/zhangqianhui/Conditional-Gans)

* [InfoGAN: Interpretable Representation Learning by Information Maximizing Generative Adversarial Nets] [[Paper]](https://arxiv.org/abs/1606.03657)[[Code]](https://github.com/buriburisuri/supervised_infogan)[[Code]](https://github.com/openai/InfoGAN)

* [Conditional Image Synthesis With Auxiliary Classifier GANs] [[Paper]](https://arxiv.org/abs/1610.09585)[[Code]](https://github.com/buriburisuri/ac-gan)(GoogleBrain ICLR 2017)

* [Pixel-Level Domain Transfer] [[Paper]](https://arxiv.org/pdf/1603.07442v2.pdf)[[Code]](https://github.com/fxia22/pldtgan)

* [Invertible Conditional GANs for image editing] [[Paper]](https://arxiv.org/abs/1611.06355)[[Code]](https://github.com/Guim3/IcGAN)

* [Plug & Play Generative Networks: Conditional Iterative Generation of Images in Latent Space] [[Paper]](https://arxiv.org/abs/1612.00005v1)[[Code]](https://github.com/Evolving-AI-Lab/ppgn)

* [StackGAN: Text to Photo-realistic Image Synthesis with Stacked Generative Adversarial Networks] [[Paper]](https://arxiv.org/pdf/1612.03242v1.pdf)[[Code]](https://github.com/hanzhanggit/StackGAN)

### Video Prediction & Generation

* [Deep multi-scale video prediction beyond mean square error] [[Paper]](https://arxiv.org/abs/1511.05440)[[Code]](https://github.com/dyelax/Adversarial_Video_Generation)(Yann LeCun's paper)

* [Generating Videos with Scene Dynamics] [[Paper]](https://arxiv.org/abs/1609.02612)[[Web]](http://web.mit.edu/vondrick/tinyvideo/)[[Code]](https://github.com/cvondrick/videogan)

* [MoCoGAN: Decomposing Motion and Content for Video Generation] [[Paper]](https://arxiv.org/abs/1707.04993)

### Texture Synthesis & Style Transfer

* [Precomputed real-time texture synthesis with markovian generative adversarial networks] [[Paper]](https://arxiv.org/abs/1604.04382)[[Code]](https://github.com/chuanli11/MGANs)(ECCV 2016)

### Image Translation 

* [UNSUPERVISED CROSS-DOMAIN IMAGE GENERATION] [[Paper]](https://arxiv.org/abs/1611.02200)[[Code]](https://github.com/yunjey/domain-transfer-network)

* [Image-to-image translation using conditional adversarial nets] [[Paper]](https://arxiv.org/pdf/1611.07004v1.pdf)[[Code]](https://github.com/phillipi/pix2pix)[[Code]](https://github.com/yenchenlin/pix2pix-tensorflow)

* [Learning to Discover Cross-Domain Relations with Generative Adversarial Networks] [[Paper]](https://arxiv.org/abs/1703.05192)[[Code]](https://github.com/carpedm20/DiscoGAN-pytorch)

* [Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks] [[Paper]](https://junyanz.github.io/CycleGAN/)[[Code]](https://github.com/junyanz/CycleGAN)

* [CoGAN: Coupled Generative Adversarial Networks] [[Paper]](https://arxiv.org/abs/1606.07536)[[Code]](https://github.com/andrewliao11/CoGAN-tensorflow)(NIPS 2016)

* [Unsupervised Image-to-Image Translation with Generative Adversarial Networks] [[Paper]](https://arxiv.org/pdf/1701.02676.pdf)

* [Unsupervised Image-to-Image Translation Networks] [[Paper]](https://arxiv.org/abs/1703.00848)

* [Triangle Generative Adversarial Networks] [[Paper]](https://arxiv.org/abs/1709.06548)


### GAN Theory

* [Energy-based generative adversarial network] [[Paper]](https://arxiv.org/pdf/1609.03126v2.pdf)[[Code]](https://github.com/buriburisuri/ebgan)(Lecun paper)

* [Improved Techniques for Training GANs] [[Paper]](https://arxiv.org/abs/1606.03498)[[Code]](https://github.com/openai/improved-gan)(Goodfellow's paper)

* [Mode Regularized Generative Adversarial Networks] [[Paper]](https://openreview.net/pdf?id=HJKkY35le)(Yoshua Bengio , ICLR 2017)

* [Improving Generative Adversarial Networks with Denoising Feature Matching] [[Paper]](https://openreview.net/pdf?id=S1X7nhsxl)[[Code]](https://github.com/hvy/chainer-gan-denoising-feature-matching)(Yoshua Bengio , ICLR 2017)

* [Sampling Generative Networks] [[Paper]](https://arxiv.org/abs/1609.04468)[[Code]](https://github.com/dribnet/plat)

* [How to train Gans] [[Docu]](https://github.com/soumith/ganhacks#authors)

* [Towards Principled Methods for Training Generative Adversarial Networks] [[Paper]](http://openreview.net/forum?id=Hk4_qw5xe)(ICLR 2017)

* [Unrolled Generative Adversarial Networks] [[Paper]](https://arxiv.org/abs/1611.02163)[[Code]](https://github.com/poolio/unrolled_gan)(ICLR 2017)

* [Least Squares Generative Adversarial Networks] [[Paper]](https://arxiv.org/abs/1611.04076)[[Code]](https://github.com/pfnet-research/chainer-LSGAN)(ICCV 2017)

* [Wasserstein GAN] [[Paper]](https://arxiv.org/abs/1701.07875)[[Code]](https://github.com/martinarjovsky/WassersteinGAN)

* [Improved Training of Wasserstein GANs] [[Paper]](https://arxiv.org/abs/1704.00028)[[Code]](https://github.com/igul222/improved_wgan_training)(The improve of wgan)

* [Towards Principled Methods for Training Generative Adversarial Networks] [[Paper]](https://arxiv.org/abs/1701.04862)

* [Generalization and Equilibrium in Generative Adversarial Nets] [[Paper]](https://arxiv.org/abs/1703.00573)（ICML 2017）


### 3-Dimensional GANs

* [Learning a Probabilistic Latent Space of Object Shapes via 3D Generative-Adversarial Modeling] [[Paper]](https://arxiv.org/abs/1610.07584)[[Web]](http://3dgan.csail.mit.edu/)[[Code]](https://github.com/zck119/3dgan-release)(2016 NIPS)

* [Transformation-Grounded Image Generation Network for Novel 3D View Synthesis] [[Web]](http://www.cs.unc.edu/%7Eeunbyung/tvsn/)(CVPR 2017)

### Music

* [MidiNet: A Convolutional Generative Adversarial Network for Symbolic-domain Music Generation using 1D and 2D Conditions] [[Paper]](https://arxiv.org/abs/1703.10847)[[HOMEPAGE]](https://richardyang40148.github.io/TheBlog/midinet_arxiv_demo.html)

### Face Generation & Editing

* [Autoencoding beyond pixels using a learned similarity metric] [[Paper]](https://arxiv.org/abs/1512.09300)[[Code]](https://github.com/andersbll/autoencoding_beyond_pixels)[[Tensorflow code]](https://github.com/zhangqianhui/vae-gan-tensorflow)

* [Coupled Generative Adversarial Networks] [[Paper]](http://mingyuliu.net/)[[Caffe Code]](https://github.com/mingyuliutw/CoGAN)[[Tensorflow Code]](https://github.com/andrewliao11/CoGAN-tensorflow)（NIPS）

* [Invertible Conditional GANs for image editing] [[Paper]](https://drive.google.com/file/d/0B48XS5sLi1OlRkRIbkZWUmdoQmM/view)[[Code]](https://github.com/Guim3/IcGAN)

* [Learning Residual Images for Face Attribute Manipulation] [[Paper]](https://arxiv.org/abs/1612.05363)[[Code]](https://github.com/Zhongdao/FaceAttributeManipulation)(CVPR 2017)

* [Neural Photo Editing with Introspective Adversarial Networks] [[Paper]](https://arxiv.org/abs/1609.07093)[[Code]](https://github.com/ajbrock/Neural-Photo-Editor)(ICLR 2017)

* [Neural Face Editing with Intrinsic Image Disentangling] [[Paper]](https://arxiv.org/abs/1704.04131)(CVPR 2017)

* [GeneGAN: Learning Object Transfiguration and Attribute Subspace from Unpaired Data ] [[Paper]](https://arxiv.org/abs/1705.04932)(BMVC 2017)[[Code]](https://github.com/Prinsphield/GeneGAN)

* [Beyond Face Rotation: Global and Local Perception GAN for Photorealistic and Identity Preserving Frontal View Synthesis] [[Paper]](https://arxiv.org/abs/1704.04086)(ICCV 2017)


### For Discrete Distributions

* [Maximum-Likelihood Augmented Discrete Generative Adversarial Networks] [[Paper]](https://arxiv.org/abs/1702.07983v1)

* [Boundary-Seeking Generative Adversarial Networks] [[Paper]](https://arxiv.org/abs/1702.08431)

* [GANS for Sequences of Discrete Elements with the Gumbel-softmax Distribution] [[Paper]](https://arxiv.org/abs/1611.04051)

### Improving Classification & Recognition

* [Generative OpenMax for Multi-Class Open Set Classification] [[Paper]](https://arxiv.org/pdf/1707.07418.pdf)(BMVC 2017)

* [Controllable Invariance through Adversarial Feature Learning] [[Paper]](https://arxiv.org/abs/1705.11122)[[Code]](https://github.com/github-pengge/adversarial_invariance_feature_learning)(NIPS 2017)

* [Unlabeled Samples Generated by GAN Improve the Person Re-identification Baseline in vitro] [[Paper]](https://arxiv.org/abs/1701.07717)[[Code]](https://github.com/layumi/Person-reID_GAN) (ICCV2017)

* [Learning from Simulated and Unsupervised Images through Adversarial Training] [[Paper]](https://arxiv.org/abs/1612.07828)[[Code]](https://github.com/carpedm20/simulated-unsupervised-tensorflow)（Apple paper, CVPR 2017 Best Paper）

### Projects

* [cleverhans] [[Code]](https://github.com/openai/cleverhans)(A library for benchmarking vulnerability to adversarial examples)

* [reset-cppn-gan-tensorflow] [[Code]](https://github.com/hardmaru/resnet-cppn-gan-tensorflow)(Using Residual Generative Adversarial Networks and Variational Auto-encoder techniques to produce high-resolution images)

* [HyperGAN] [[Code]](https://github.com/255bits/HyperGAN)(Open source GAN focused on scale and usability)

### Tutorials

* [1] [Ian Goodfellow's GAN Slides](http://www.iangoodfellow.com/slides/2016-12-04-NIPS.pdf) (NIPS Goodfellow Slides)[[Chinese Trans]](http://c.m.163.com/news/a/C7UE2MLT0511AQHO.html?spss=newsapp&spsw=1)[details](https://arxiv.org/pdf/1701.00160v1.pdf)

* [2] [PDF](https://drive.google.com/file/d/0BxKBnD5y2M8NbzBUbXRwUDBZOVU/view)(NIPS Lecun Slides)

* [3] [ICCV 2017 Tutorial About GANS](https://sites.google.com/view/iccv-2017-gans/schedule)