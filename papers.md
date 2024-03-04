---
layout: default
---

# Accepted Papers

We will provide a list of all accepted papers here. You can find more information
about each submission by following either the *Forum* link or by visiting
our [OpenReview Workshop Website](https://openreview.net/group?id=ICLR.cc/2024/Workshop/AI4DiffEqtnsInSci).

# Statistics
We received 102 submissions in total, of which we accepted 4 spotlights (contributed talks) and 83 poster presentations. All submissions received at least one review and one meta-review.

Congratulations to all authors!

# Spotlights
**Data-driven Higher Order Differential Equations Inspired Graph Neural Networks** <br />
Moshe Eliasof &bull; Eldad Haber &bull; Eran Treister &bull; Carola-Bibiane Schönlieb <br />
<abstract>A recent innovation in Graph Neural Networks (GNNs) is the family of Differential Equation-Inspired Graph Neural Networks (DE-GNNs), which leverage principles from continuous dynamical systems to model information flow on graphs with built-in properties. However, existing DE-GNNs rely on first or second-order temporal orders. In this paper, we propose a neural extension to those pre-defined temporal dependencies. We show that our model, called TDE-GNN, can capture a wide range of temporal dynamics that go beyond typical first or second-order methods, and provide use cases where existing temporal models are challenged. We demonstrate the benefit of learning the temporal dependencies using our method rather than using pre-defined temporal dynamics on several graph benchmarks.</abstract>

[PDF](https://openreview.net/pdf?id=rJReXWFByt) &bull;
[Forum](https://openreview.net/forum?id=rJReXWFByt)

**A Multi-Grained Symmetric Differential Equation Model for Learning Protein-Ligand Binding Dynamics** <br />
Shengchao Liu &bull; Weitao Du &bull; Yanjing Li &bull; Zhuoxinran Li &bull; Vignesh C. Bhethanabotla &bull; Nakul Rampal &bull;  Omar M. Yaghi &bull; Christian Borgs &bull; Anima Anandkumar &bull; Hongyu Guo &bull; Jennifer T. Chayes<br />
<abstract>In drug discovery, molecular dynamics (MD) simulation for protein-ligand binding provides a powerful tool for predicting binding affinities, estimating transport properties, and exploring pocket sites. There has been a long history of improving the efficiency of MD simulations through better numerical methods and, more recently, by augmenting them with machine learning (ML) methods. Yet, challenges remain, such as accurate modeling of extended-timescale simulations. To address this issue, we propose NeuralMD, the first ML surrogate that can facilitate numerical MD and provide accurate simulations of protein-ligand binding dynamics. We propose a principled approach that incorporates a novel physics-informed multi-grained group symmetric framework. Specifically, we propose (1) a BindingNet model that satisfies group symmetry using vector frames and captures the multi-level protein-ligand interactions, and (2) an augmented neural ordinary differential equation solver that learns the trajectory under Newtonian mechanics. For the experiment, we design ten single-trajectory and three multi-trajectory binding simulation tasks. We show the efficiency and effectiveness of NeuralMD, with a 2000 speedup over standard numerical MD simulation and outperforming all other ML approaches by up to ~80% under the stability metric. We further qualitatively show that NeuralMD reaches more stable binding predictions.</abstract>

[PDF](https://openreview.net/pdf?id=4sHc6X6ZEh) &bull;
[Forum](https://openreview.net/forum?id=4sHc6X6ZEh)

**Neural operators with localized integral and differential kernels** <br />
Miguel Liu-Schiaffini &bull; Julis Berner &bull; Boris Bonev &bull; Thorsten Kurth &bull; Kamyar Azizzadenesheli &bull; Anima Anandkumar<br />
<abstract>Neural operators learn mappings between function spaces, which is applicable for learning solution operators of PDEs and other scientific modeling applications. Among them, the Fourier neural operator (FNO) is a popular architecture that performs global convolutions in the Fourier space. However, such global operations are often prone to over-smoothing and may fail to capture local details. In contrast, convolutional neural networks (CNN) can capture local features but are limited to training and inference at a single resolution. In this work, we present a principled approach to operator learning that can capture local features under two frameworks by learning differential operators and integral operators with locally supported kernels. Specifically, inspired by stencil methods, we prove that under an appropriate scaling of the kernel values of CNNs, we obtain differential operators. To obtain integral local operators, we utilize suitable basis representations for the kernels based on discrete-continuous convolutions. Both these principled approaches preserve the properties of operator learning and, hence, the ability to predict at any resolution. Adding our layers to FNOs significantly improves their performance, reducing the relative L2-error by 34-72% in our experiments on turbulent 2D Navier-Stokes fluid flow and the spherical shallow water equations.</abstract>

[PDF](https://openreview.net/pdf?id=fTOeB5L4PP) &bull;
[Forum](https://openreview.net/forum?id=fTOeB5L4PP)

**Generative PDE Control** <br />
Long Wei &bull; Peiyan Hu &bull; Ruiqi Feng &bull; Yixuan Du &bull; Tao Zhang &bull; Rui Wang &bull; Yue Wang &bull; Zhi-Ming Ma &bull; Tailin Wu<br />
<abstract>Controlling Partial Differential Equations (PDE) is a fundamental task across science and engineering. Classical techniques for PDE control tend to be computationally demanding and recent deep learning-based approaches often struggle to optimize long-term control sequences. In this work, we introduce Diffusion generative PDE Control (DiffConPDE), a new class of method to address the PDE control problem. DiffConPDE excels by simultaneously minimizing both the learned generative energy function and the predefined control objectives across the entire trajectory and control sequence. Moreover, we enhance DiffConPDE with prior reweighting, enabling the discovery of control sequences that significantly deviate from the training distribution. We test our method in 2D Jellyfish flapping in a fluid environment and 1D Burgers' equation control. Our method consistently outperforms baselines. Notably, DiffConPDE unveils an intriguing fast-close-slow-open pattern observed in the jellyfish, aligning with established findings in the field of fluid dynamics.</abstract>

[PDF](https://openreview.net/pdf?id=vaKnCahjdj) &bull;
[Forum](https://openreview.net/forum?id=vaKnCahjdj)
