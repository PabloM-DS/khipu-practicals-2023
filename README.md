# Khipu 2022 Practicals

Derived from **Deep Learning Indaba Practicals 2022** with permission from the authors.

## Contents
| Topic 💥 | Description 📘 |
|:--- |----------------------------------------------------------|
[Introduction to ML using JAX](https://github.com/deep-learning-indaba/indaba-pracs-2022/blob/main/practicals/Introduction_to_ML_using_JAX.ipynb) <br /> <br /> [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/deep-learning-indaba/indaba-pracs-2022/blob/main/practicals/Introduction_to_ML_using_JAX.ipynb) | In this tutorial, we will learn about JAX, a new machine learning framework that has taken deep learning research by storm! JAX is praised for its speed, and we will learn how to achieve these speedups, using core concepts in JAX, such as automatic differentiation (`grad`), parallelization (`pmap`), vectorization (`vmap`), just-in-time compilation (`jit`), and more. We will then use what we have learned to implement Linear Regression effectively while learning some of the fundamentals of optimization.  | 
[Bayesian Deep Learning](https://github.com/deep-learning-indaba/indaba-pracs-2022/blob/main/practicals/Bayesian_Deep_Learning_Prac.ipynb) <br /> <br /> [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/deep-learning-indaba/indaba-pracs-2022/blob/main/practicals/Bayesian_Deep_Learning_Prac.ipynb) | Bayesian inference provides us with the tools to update our beliefs consistently when we observe data. Compared to the, more common, loss minimisation approach to learning, Bayesian methods offer us calibrated uncertainty estimates, resistance to overfitting, and even approaches to select hyper-parameters without a validation set. 🚀In this prac we will learn to do all of these things!🚀 | 
[Transformers and Attention](https://github.com/deep-learning-indaba/indaba-pracs-2022/blob/main/practicals/attention_and_transformers.ipynb) <br /> <br /> [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/deep-learning-indaba/indaba-pracs-2022/blob/main/practicals/attention_and_transformers.ipynb) | The transformer architecture, introduced in Vaswani et al. 2017's paper [Attention is All You Need](https://arxiv.org/abs/1706.03762?amp=1), has significantly impacted the deep learning field. It has arguably become the de-facto architecture for complex Natural Language Processing (NLP) tasks. It can also be applied in various domains reaching state-of-the-art performance, including computer vision and reinforcement learning. Transformers, as the title of the original paper implies, are almost entirely based on a concept known as attention. Attention allows models to "focus" on different parts of an input; while considering the entire context of the input versus an RNN, that operates on the data sequentially. In this practical, we will introduce attention in greater detail and build the entire transformer architecture block by block to see why it is such a robust and powerful architecture | 
[Graph Neural Networks](https://github.com/deep-learning-indaba/indaba-pracs-2022/blob/main/practicals/GNN_practical.ipynb) <br /> <br /> [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/deep-learning-indaba/indaba-pracs-2022/blob/main/practicals/GNN_practical.ipynb) | In this tutorial, we will be learning about Graph Neural Networks (GNNs), a topic which has exploded in popularity in both research and industry. We will start with a refresher on graph theory, then dive into how GNNs work from a high level. Next we will cover some popular GNN implementations and see how they work in practice. | 
[Deep Generative Models](https://github.com/deep-learning-indaba/indaba-pracs-2022/blob/main/practicals/deep_generative_models.ipynb) <br /> <br /> [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/deep-learning-indaba/indaba-pracs-2022/blob/main/practicals/deep_generative_models.ipynb) | In this practical, we will investigate the fundamentals of generative modelling – a machine learning framework that allows us to learn how to sample new unseen data points that match the distribution of our training dataset. Generative modelling, though a powerful and flexible framework–which has provided many exciting advances in ML–has its own challenges and limitations. This practical will walk you through such challenges and will illustrate how to solve them by implementing a Denoising Diffusion Model (a.k.a. a Score-Based Generative Model), which is the backbone of the recent and exciting [Dalle-2](https://openai.com/dall-e-2/) and [Imagen](https://imagen.research.google/) models that we’ve all seen on [Twitter](https://twitter.com/search?q=%23dalle2%20%23imagen&src=typed_query). |
[Intro to Reinforcement Learning](https://github.com/deep-learning-indaba/indaba-pracs-2022/blob/main/practicals/introduction_to_reinforcement_learning.ipynb) <br /> <br /> [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/deep-learning-indaba/indaba-pracs-2022/blob/main/practicals/introduction_to_reinforcement_learning.ipynb) | In this tutorial, we will be learning about Reinforcement Learning, a type of Machine Learning where an agent learns to choose actions in an environment that lead to maximal reward in the long run. RL has seen tremendous success on a wide range of challenging problems such as learning to play complex video games like [Atari](https://www.deepmind.com/blog/agent57-outperforming-the-human-atari-benchmark), [StarCraft II](https://www.deepmind.com/blog/alphastar-mastering-the-real-time-strategy-game-starcraft-ii) and [Dota II](https://openai.com/five/). In this introductory tutorial we will solve the classic [CartPole](https://www.gymlibrary.ml/environments/classic_control/cart_pole/) environment, where an agent must learn to balance a pole on a cart, using several different RL approaches. Along the way you will be introduced to some of the most important concepts and terminology in RL. | 
[Array Algebra](https://colab.research.google.com/github/deep-learning-indaba/indaba-pracs-2022/blob/prac-array-algebra/practicals/array_algebra.ipynb) <br /> <br /> [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/deep-learning-indaba/indaba-pracs-2022/blob/prac-array-algebra/practicals/array_algebra.ipynb) | In this tutorial, we’ll look at one of the cornerstones of modern deep learning: array programming. Think of this tutorial as a gym or obstacle course for working with arrays. We’ll help you gain intuition about multidimensional arrays (“tensors”), so you can better understand transposing, broadcasting, contraction, and the other “algebraic moves” that make array programming both frustrating and rewarding. They’ll be practical examples as well as theoretical exercises to help you develop your understanding. | 

This repository contains the practical notebooks for the Deep Learning Indaba
2022, held at SUP’COM University in Tunis, Tunisia.

See [www.deeplearningindaba.com](http://www.deeplearningindaba.com) for more details.
