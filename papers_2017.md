# Learning a Probabilistic Latent Space of Object Shapes via 3D Generative-Adversarial Modeling. NIPS 2017

[Access link](http://3dgan.csail.mit.edu/)

*Presented by Pooran Singh Negi*

**Summary:** Papers propose **3D- Generative Adversial Network(3D-GAN)**
for 3D object creation (using sample from a probablistic space) and
classification task. This latent space can also be inferred as shown in 2D image to 3D image generation( **3D-VAE-GAN section**). A VAE is used along with
3D-VAN for this setup. Proposed method shows state of the art and above
performance against supervised and unsupervied method. Another interesting
work done in paper is showing latent space arithmetics where objects can
be manipulated in latent space to build new novel and realistic objects.
This is simialr to word to vector of  Mikolov but is more impressive
as manipuation is done in latent space not the actual learned representation space.

- **Main architecture**

credit:: All the figure realted to this papers are from ppt and paper from
Jiajun Wu*, Chengkai Zhang*, Tianfan Xue, William T. Freeman, and Joshua B. Tenenbaum

Network: 
![alt text](./papers_figures/figures_2017/3d_gan_main_figure.jpeg "3D-GAN architecture")

- Loss functions
  + 3D-GAN
  ![alt text](./papers_figures/figures_2017/3d_gan_loss_fn.jpeg "3D-GAN loss function")
  + 3D-VAE-GAN
  ![alt text](./papers_figures/figures_2017/3d_vae_gan_loss_fn.jpeg "3D-VAE-GAN loss function")


# Deep Neural Decision Forests. ICCV 2015
[Access link](http://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Kontschieder_Deep_Neural_Decision_ICCV_2015_paper.pdf)

[Slides](http://www.robots.ox.ac.uk/~tvg/publications/talks/deepNeuralDecisionForests.pdf)

*Presented by Ali Mollahosseini*

**Summary:** 
This paper proposes a Deep Neural Decision Forests
that unifies classification trees with the representation
learning functionality known from deep convolutional
networks, by training them in an end-to-end manner. 
Experimental result on benchmark machine
learning datasets like MNIST and ImageNet shows superior results when compared to state-of-the-art
deep models. Top5-Errors of only 7.84%/6.38% on ImageNet validation data when integrating
our forests in a single-crop, single/seven model
GoogLeNet architecture, respectively. Thus, even without
any form of training data set augmentation we are improving
on the 6.67% error obtained by the best GoogLeNet architecture
(7 models, 144 crops)

Random forests  has been empirically
demonstrated to outperform most state-of-the-art
learners when it comes to handling high dimensional data
problems, they are inherently able to deal with multiclass
problems, are easily distributable on parallel hardware
architectures while being considered to be close to an ideal
learner

[Slides on Random Forest](http://www.cs.ubc.ca/~nando/540-2013/lectures/l9.pdf)

[Video on Random Forest](https://www.youtube.com/watch?v=3kYujfDgmNk)


Deep learning approaches is can learn feature representations together with
their classifiers. This paper introduces  a stochastic, differentiable, and therefore backpropagation
compatible version of decision trees, guiding
the representation learning in lower layers of deep convolutional
networks.

![alt text](./papers_figures/figures_2017/Decision_Trees_with_Stochastic_Routing.jpg "Decision Trees with Stochastic Routing")

![alt text](./papers_figures/figures_2017/Learning_Trees_by_Back_Propagation.jpg "Learning Trees by Back-Propagation")
![alt text](./papers_figures/figures_2017/Learning_Trees_by_Back_Propagation2.jpg)


![alt text](./papers_figures/figures_2017/Learning_forests.jpg "Learning forests")

