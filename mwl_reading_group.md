---
layout: page
title: MWL Reading Group
---

We're reading research papers about various topics in machine learning and
artificial intelligence. Meetings will be informal, reading-group style; likely
there will be one or two people assigned to lead a "discussion" about the
readings, and we will talk about things that we found interesting or did not
quite understand in the papers.

**We're planning on meeting for 1.5-2 hours on Tuesdays at 6:30 PM in CSE 503**

## Suggested Prerequisites

In order to get a lot out of this, participants probably will want to have taken
a course in either natural language processing, machine learning, artificial
intelligence, or computer vision; most concepts should be comprehensible to
people with a solid probability and mathematics background, however.

## Winter Quarter 2017 (Very Tentative) Schedule

| Week | Date | Time | Place | Summary of Contents |
|------|------|------|-------|-----------------------------------------------------|
| 1 | Jan 3 | 6:30 PM | CSE 503 | [[a-z]* and how to search<br>Search in machine learning](#january-3rd-search) |
| 2 | Jan 10 | 6:30 PM | CSE 503 | [80's Deep Learning](#january-10th-80s-deep-learning-or-deep-learning-then-and-now) |
| 3 | Jan 17 | 6:30 PM | CSE 303 | [Deep Neural Nets as Data Structures](#january-17th-dnns-as-data-structures) |
| 4 | **Jan 25** | 6:30 PM | CSE 303 | [Deep Computer Vision Tricks](#january-25th-deep-computer-vision-tricks) |
| 5 | Jan 31 | 6:30 PM | CSE 303 | Attention / Memory |
| 6 | Feb 7 | 6:30 PM | CSE 303 | Very Distant Supervision |
| 7 | Feb 14 | 6:30 PM | CSE 303 | Graphical Models |
| 8 | Feb 21 | 6:30 PM | CSE 303 | Variational Inference |
| 9 | Feb 28 | 6:30 PM | CSE 303 | Structured Prediction |
| 10 | Mar 7 | 6:30 PM | CSE 303 | Structured Prediction |

## What We're Reading

### January 3rd: Search
  - [P. E. Hart, N. J. Nilsson and B. Raphael, "A Formal Basis for the Heuristic Determination of Minimum Cost Paths"](http://ai.stanford.edu/~nilsson/OnlinePubs-Nils/PublishedPapers/astar.pdf)
  - [S. Koenig and M. Likhachev, "Fast replanning for navigation in unknown terrain"](https://pdfs.semanticscholar.org/e782/3d7c5fdf7145e241fc70b13958815231eee8.pdf)
  - [M. Likhachev and A. Stentz, "R* Search"](https://pdfs.semanticscholar.org/8807/f78517dbe60acb44434bfd901ce14b24b01b.pdf)
  - [Ferguson, Dave and Anthony Stentz. "Anytime RRTs."](https://pdfs.semanticscholar.org/0978/cf6a89df6b6146c93550621d39f95c838175.pdf)
  
### January 10th: 80's Deep Learning (or: Deep Learning Then and Now)
  - [Hochreiter, Sepp and Jürgen Schmidhuber. "Long Short-Term Memory"](https://pdfs.semanticscholar.org/744d/cb85b8a36a7cf6b382ba100965de717ebe91.pdf)
    - Original LSTM Paper, only the first 11 pages should be relevant, so you're
      not required to read beyond that
    - [This blog post (by Christopher Olah)](http://colah.github.io/posts/2015-08-Understanding-LSTMs/)
      is great for understanding how recurrent neural nets (RNNs) and LSTMs
      work, would highly recommend reading!
  - [Cho, Kyunghyun et al. "Learning Phrase Representations using RNN Encoder-Decoder for Statistical Machine Translation"](https://pdfs.semanticscholar.org/e2ce/a79e832e0fe999efba16fd621f84cd322371.pdf)
    - Introduces a modern variant of the LSTM called the Gated Recurrent Unit
      (GRU)
  - [Lecun, Yann et al. "Gradient-based Learning Applied to Document Recognition."](https://pdfs.semanticscholar.org/d1cf/aea6c9b1d42aa823137bb33cea3d01c6536e.pdf)
    - Original Convolutional Neural network paper beyond theory - only the first
      12-15 pages should be relevant, so you're not required to read beyond
      that.
    - [This blog post (by Andrej Karpathy)](http://karpathy.github.io/2015/10/25/selfie/)
      is great for getting an intuition on convolutional neural networks.
  - [Krizhevsky, Alex et al. "ImageNet Classification with Deep Convolutional Neural Networks."](https://pdfs.semanticscholar.org/2315/fc6c2c0c4abd2443e26a26e7bb86df8e24cc.pdf)
    - Seminal paper on classifying images with deep learning, generally agreed
      to be the paper that kickstarted the modern deep learning era
  - [extra credit paper if you're interested: Józefowicz, Rafal et al. "An Empirical Exploration of Recurrent Network Architectures."](https://pdfs.semanticscholar.org/324f/c9c732116fa81624faad07524039f193cede.pdf)
  - [Entertaining (?) article about Jürgen Schmidhuber's thoughts on his lack of recognition in modern deep learning, with commentary by Yann LeCun and others.](http://www.nytimes.com/2016/11/27/technology/artificial-intelligence-pioneer-jurgen-schmidhuber-overlooked.html)
  
### January 17th: DNNs as Data Structures
  - [Dyer, Chris et al. “Transition-Based Dependency Parsing with Stack Long Short-Term Memory.” ACL (2015).](https://pdfs.semanticscholar.org/aa8d/3cb91d00aa7e981d9686e07c99505aba4fd8.pdf)
    - "StackLSTM", might require some knowledge of how shift-reduce parsing works.
  - [Tai, Kai Sheng et al. “Improved Semantic Representations From Tree-Structured Long Short-Term Memory Networks.” ACL (2015).](https://pdfs.semanticscholar.org/b251/b79996e475d22dd7081387c435e67e087043.pdf)
    - "TreeLSTM"
    
### January 25th: Deep Computer Vision Tricks
  - [He, Kaiming et al. "Deep Residual Learning for Image Recognition."](https://pdfs.semanticscholar.org/c30d/63fe81f4ef461277ed69c4f1ac61d1d8c817.pdf)
    - "ResNets"
  - [Ioffe, Sergey and Christian Szegedy. "Batch Normalization: Accelerating Deep Network Training by Reducing Internal Covariate Shift."](https://pdfs.semanticscholar.org/298e/77753a499c28a2220dc5924f55f8a6468be5.pdf)
  - [Bonus (very) cool paper: Zoph, Barret and Quoc V. Le. "Neural Architecture Search with Reinforcement Learning."](https://www.semanticscholar.org/paper/Neural-Architecture-Search-with-Reinforcement-Zoph-Le/cc75a5324180677866c19d0429ae3f8f5a568ed6)

## Resources

Resources to come soon!

## Notes

Notes to come soon!
