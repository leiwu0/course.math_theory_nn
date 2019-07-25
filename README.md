
## Mathematical Theory of Neural Network Models

### Announcements
- **7/25**: The report of paper review is due on 8/2, 12 pm. 
- **7/19**: The [schedule](pre_schedule.txt) of presentations is out.
- 7/18: A draft of Lecture [4](note/lec4.pdf) is out. 
- 7/17: Drafts of Lecture [3](note/lec3.pdf), [5](note/lec5.pdf) and [6](note/lec6.pdf) are out. 
- 7/12: A draft of [Lecture 2](note/lec2.pdf) is out.
- 7/12: Some references for random feature models, Barron spaces and regularization theory of two-layer nets are added.
- 7/9: A draft of [Lecture 1](note/lec1.pdf) is out.
- 7/9: [Homework 2](homework/homework2.pdf) is out. It is due on Tuesday, 7/16, 12pm.
- 7/6: [Homework 1](homework/homework1.pdf) is out. It is due on Friday, 7/12, 12pm.


### Administrative information

- **Instructor:**   
    - [Weinan E](https://web.math.princeton.edu/~weinan/) 
    - [Lei Wu](https://scholar.google.com/citations?user=CMweeYcAAAAJ&hl=en),     leiwu@princeton.edu 
    - Chao Ma,   chaom@princeton.edu

- **Time:** Tue: 2:00-5:00 pm; Thu: 2:00-5:00 pm; Fri: 3:00-5:00 pm. 

- **Location:**  Room 515, [Teaching Building 2](https://maps.baidu.com/poi/%E5%8C%97%E4%BA%AC%E5%A4%A7%E5%AD%A6(%E7%87%95%E5%9B%AD%E6%A0%A1%E5%8C%BA)%E7%AC%AC%E4%BA%8C%E6%95%99%E5%AD%A6%E6%A5%BC(%E6%9D%8E%E5%85%86%E5%9F%BA%E6%A5%BC)/@12948834.869857343,4837581.844142513,19.6z?uid=82548a63754afc91735e80e4&primaryUid=10472254985355704340&ugc_type=3&ugc_ver=1&device_ratio=1&compat=1&querytype=detailConInfo&da_src=shareurl)




### Course Content
**Description:**

This course introduces the basic models for supervised learning,  including kernel method, two-layer neural network and residual network. We then provide a unified approach to analyze these models.


**Topic:**

- Supverised learning, generalization/approximation/estimation error, a priroi/posteriori estimates
- Kernel method, two-layer nerual network, residual network 
- Reproducing kernel Hilbert space, Barron space, compositional function space
- Rademacher complexity, margin, gradient descent, implicit regularization

**Prerequisite:**

- A solid background in linear algebra, real analysis and probability/measure theory
- Basic knowledge in (convex) optimization and statistics 


### Grading
**Coursework:**
- **Homework** (45%)
- **Paper review** (45%): You are asked to choose a paper from this [ paper list](paper_list.md) and write a review. The review should not only summarize the paper, but also identify the novelty and limitation of the result.  A good paper review at least attempts to answer the following four questions:
    - What is the main result of the paper?
    - Why is the result important and significant compared with other papers?
    - What is the limitation of the result?
    - What is the potential research direction inspired by the paper?
    
 You are required to give a presentation (15%) and submit a report of 3 pages (30%).

- **Scribe notes** (10%): You are asked to scribe a note in LaTeX. The scribe notes can be done in pairs. Please use this [template](template/):  

**Collaboration policy:** We encourage you to form study groups and discuss courseworks.  However, you must write up all the coureworks from scrach independently without refering to any notes from  others. 



### Texts and References
 - [Peter Bartlett's course: Statistical Learning Theory](https://www.stat.berkeley.edu/~bartlett/courses/2014spring-cs281bstat241b/)
 - [MIT's course: Statistical Learning Theory](http://www.mit.edu/~9.520/fall18/)
 - [Mohri's book: Foundations of Machine Learning](https://cs.nyu.edu/~mohri/mlbook/)
 - [Shai Shalev-Shwartz's book: Understanding Machine Learning: From Theory to Algorithms](https://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/copy.html)

---
### Schedule (subject to change)

#### Week 1
- Tue 7/2: Introduction to supervised learning methods 
    - [Lecture 1](note/lec1.pdf)
    -  [Random Features for Large-Scale Kernel Machines](https://papers.nips.cc/paper/3182-random-features-for-large-scale-kernel-machines)
- Thu 7/4: Overview of mathematical theory for neural network models 
    - [Lecture 2](note/lec2.pdf)
    - [Slide of Prof. E](slide/overview.pdf)
    - [A priori estimates](https://en.wikipedia.org/wiki/A_priori_estimate)
- Fri 7/5: Rademacher complexity, covering number, metric entropy and uniform bound 
    - [Lecture 3](note/lec3.pdf)
    - [Concentration inequalities](https://www.stat.berkeley.edu/~mjwain/stat210b/Chap2_TailBounds_Jan22_2015.pdf)

#### Week 2
- Reproducing kernel Hilbert space and random feature model
    - [Lecture 4](note/lec4.pdf)
    - [What is an RKHS?](http://www.stats.ox.ac.uk/~sejdinov/teaching/atml14/Theory_2014.pdf) 
    - [Uniform Approximation of Functions with Random Bases](https://people.eecs.berkeley.edu/~brecht/papers/08.Rah.Rec.Allerton.pdf)
- Error estimates for random feature model with explict and implicit regularizations
    - [Lecture 5](note/lec5.pdf)
    - The analysis of implicit regularization for the random feature model can be found in this [paper](https://arxiv.org/abs/1904.04326)
    - [Learning with SGD and Random Features](https://arxiv.org/abs/1807.06343)
    - [Optimal Rates for the Regularized Least-Squares Algorithm](https://link.springer.com/article/10.1007/s10208-006-0196-8)
- Barron space and regularization theory of two-layer neural networks
    - [Lecture 6](note/lec6.pdf)
    - Properties of Barron space can found in Section 2 of this [paper](https://arxiv.org/abs/1906.08039)
    - The a priori estimates of regularized two-layer neural networks can be found in this [paper](https://arxiv.org/abs/1810.06397)
    - [The must-read classic paper of Andrew Barron](http://www.stat.yale.edu/~arb4/publications_files/UniversalApproximationBoundsForSuperpositionsOfASigmoidalFunction.pdf) (This is the first paper that provides an approximation rate without the course of dimensionality.)

#### Week 3
- Tue 7/16: Explicit and implicit regularization for two-layer neural networks 
- Thu 7/18: Residual network and compositional function spaces 
- Fri 7/19: Regularization theory of residual networks 
    - [A priori estimates of the population risk for residual networks](https://arxiv.org/abs/1903.02154)

#### Week 4
- Tue 7/23: Margin theory
- Thu 7/25: Recent progress on deep learning theory: approximation 
- Fri 7/26: Recent progress on deep learning theory: generalization











