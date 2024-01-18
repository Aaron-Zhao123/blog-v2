---
layout: default
permalink: /teaching/adls/
---

# Advanced Deep Learning Systems (ADLS)

Course code: ELEC70109/EE9-AML3-10/EE9-AO25

## Important dates

- 5th Feb, Practical 1 (Lab 1 and 2) and Practical 2 (Lab 3 and 4) submission
- 9th Feb, Team project sign-up ends
- TBC, but around 5th Feb, Midterm lab oral for both practicals
- TBC, but around 18th Mar, Show me your code session
- 28th Mar, Report submission and pull request finalization

## Full dates

| Week Number | Date      | Schedule    |
|------------|-----------|-------------|
| 2          | 15th Jan   | Lecture 1, 2, 3 and 4, Team Signup starts|
| 3          | 22nd Jan 	| Practical 1 lab |
| 4          | 29th Jan 	| Practical 2 lab |
| 5          | 5th Feb  	| Lecture 5, 6, 7 and 8|
| 6          | 12th Feb 	| Lecture 9, 10, 11 and 12|
| 7          | 19th Feb 	| Lecture 13, 14, 15 and 16|
| 8          | 26th Feb 	| Team Project Lab 1|
| 9          | 4th Mar 	  | Team Project Lab 2|
| 10         | 11th Mar 	| Team Project Lab 3|
| 11         | 18th Mar 	| Show me your code |
| End of term| 28th Mar 	| Final Report 	and Pull Request Finalization		|


#### Lecture 1: An Introduction to Modern Deep Learning Systems and Frameworks

- <a href="../../assets/pdf/adls/lecture1.pdf">Slides</a>
- [Git tutorial](https://jianyicheng-research.notion.site/Git-Tutorial-516864ab8fa04242ad520652744b931f)
- [Dark Silicon and the End of Multicore Scaling](https://research.cs.wisc.edu/vertical/papers/2011/isca11-darksilicon.pdf)
- [Managing Wire Delay in Large Chip-Multiprocessor Caches](https://ieeexplore.ieee.org/abstract/document/1551004?casa_token=P5sarPuvBZ4AAAAA:eh8TDWxx89Z04mkFw2KdFrvWhD2raDe_u66ES8e5ZEpxq276zQ0wfs2uE6tWVdQhodRf9lSmAQ)

#### Lecture 2: MASE: Abstractions, Optimizations and Implementations

- <a href="../../assets/pdf/adls/lecture2.pdf">Slides</a>
- [Troch FX](https://pytorch.org/docs/stable/fx.html)
- [MASE](https://github.com/DeepWok/mase)

#### Lecture 3: An Introduction to Practical 1

- <a href="../../assets/pdf/adls/lecture3.pdf">Slides</a>

#### Lecture 4: An Introduction to Practical 2

- <a href="../../assets/pdf/adls/lecture4.pdf">Slides</a>


#### Lecture 5: Understanding the Workloads: Part 1

<!-- - <a href="../../assets/pdf/ie/lecture3.pdf">Slides</a> -->
- [Convolution and DeConvolution animation](https://github.com/vdumoulin/conv_arithmetic/blob/master/README.md)
- [Convolution padding and striding animation](https://hannibunny.github.io/mlbook/neuralnetworks/convolutionDemos.html)
- [Deep Residual Learning for Image Recognition](https://arxiv.org/abs/1512.03385)
- [U-Net: Convolutional Networks for Biomedical Image Segmentation](https://arxiv.org/abs/1505.04597)
- [Deconvolutional Networks](https://ieeexplore.ieee.org/document/5539957)
- [The amazing power of word vectors](https://blog.acolyer.org/2016/04/21/the-amazing-power-of-word-vectors/)
- [Attention Is All You Need](<https://arxiv.org/abs/1706.03762>)
- [BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](<https://arxiv.org/abs/1810.04805>)
- [Exploring the Limits of Transfer Learning with a Unified Text-to-Text Transformer](<https://arxiv.org/abs/1910.10683>)
- [LLaMA: Open and Efficient Foundation Language Models](<https://arxiv.org/abs/2302.13971>)

## Labs

Labs are hosted on [Github](https://github.com/DeepWok/mase/tree/main/docs/labs)

- [Lab1](https://github.com/DeepWok/mase/blob/main/docs/labs/lab1.md)
- [Lab2](https://github.com/DeepWok/mase/blob/main/docs/labs/lab2.md)
- [Lab3](https://github.com/DeepWok/mase/blob/main/docs/labs/lab3.md)
- [Lab4 (Software Stream)](https://github.com/DeepWok/mase/blob/main/docs/labs/lab4-software.md)
- [Lab4 (Hardware Stream)](https://github.com/DeepWok/mase/blob/main/docs/labs/lab4-hardware.md)

## Assessment Information

The assessment contains two practicals (15% each), and a team project with two people (70%).
If you used Colab Pro, we are wiling to reimburse that cost, please keep a copy of your receipt.

##### Practical 1 Submission (15%)

 - Deadline (5th Feb, submission on BlackBoard): **A Markdown file**: with all answers (plots, tables ...) of the questions and optional questions in Lab 1 and Lab2. The file should be named as `practical1_your_college_short_code.md` (eg. `practical1_yz10513.md`). 
 - Corresponding code in your forked repository (will be checked in the lab oral, no submission needed). But you can include code snippets in the submitted markdown file.
 - Deadline (TBC, but around 5th Feb) **Lab Oral**.

##### Practical 2 Submission (15%)

 - Deadline (5th Feb, submission on BlackBoard): **A Markdown file**: with all answers (plots, tables ...) of the questions and optional questions in Lab 3 and Lab4. The file should be named as `practical2_your_college_short_code.md` (eg. `practical2_yz10513.md`). 
 - Corresponding code in your forked repository (will be checked in the lab oral, no submission needed). But you can include code snippets in the submitted markdown file.
 - Deadline (TBC, but around 5th Feb) **Lab Oral**.

##### Team Project (70%)

- [Signup link](https://docs.google.com/spreadsheets/d/1atlb43T8x6Gv5idg0eupLlW1REFDdblw3pBgsSWci7E/edit?usp=sharing)
- A roadmap meeting with a GTA (not assessed).
- Deadline (18th March): **A show me your code lab oral** (assessed).  
- Deadline (28th March): **Coursework code submission** as a pull request on Github (assessed). The PR should also have a clear documentation of the functionality that you have implemented and its corresponding tests. The tests should be integrated into the existing testing framework.
- Deadline (28th March, PDF attached in the PR): **8-page Report** (assessed). The report should mainly focus on an evaluation of your implementation. The description of functionality and testing has being described in the PR already, so this 8-page report should include the experiments you have designed to explore certain trade-offs and properties of your optimization.