# Differential and Sympletic Geometry


## What I want to get from this topic
- Deeper understand the topic and its connection to more applied system such as physical system, as well its more generic formulation
- Acquire a higher command of branch of mathematics that is relevant for my lont term deep understanding of learning system
- Be comfortable designing model that incorporate notions from differential geometry and information geometry
- Entry-point to understand sympletic geometry / optimization and hamiltonian systems
   - This has a sub-goal of understanding how some nesterov acceleration methods in ML can be generalized
- Entry-point to start understanding differential forms and exterior derivative
- Be able to better formulate what I mean with the geometric aspects of a dataset or latent-space of a method
- Understand well riemmanian geometry
- Have a better mental model of curvature, flatness, geodesics and it is connection to different measures of variation of a high-dimensional function. Ultimately this should be useful when thinking about learning system both in the learning phase and inference phase.
- Understand better the computational trade-off of using different types of integrators, for example why the lie group integrators, or symplectic integrators are preferred under certain circumstances where we want to preserve certain quantities or not (this is connected to using differential equation integrators being used in neural network training)
   - Related to this goal, ability to embedd neural network / learning system or bayesian models with differential training integrators that allow them to have some symmetries? maybe a way to embed knowledge into learning system


## Resources

### Main learning sources
- [Functional Differential Geometry, Gerald Jay Sussman, Jack Wisdom](https://mitpress.mit.edu/books/functional-differential-geometry)
- [Lectures on Sympletic Geometry, Ana Cannas da Silva](https://people.math.ethz.ch/~acannas/Papers/lsg.pdf)
- A Course of Differential Geometry and Topology, Mishchenko and Fomenko
- [Learning roadmap for Differential Geometry for Machine Learning. Roger Grosse](https://metacademy.org/roadmaps/rgrosse/dgml)
#### Background material
- [Linear Methods course, Mats Ehrnström., NTNU](https://wiki.math.ntnu.no/linearmethods/start)
- [Differential Geometry of Curves & Surfaces, Manfredo do Carmo](http://www2.ing.unipi.it/griff/files/dC.pdf)
- [A Geometric Approach to Differential Forms, David Bachman](https://arxiv.org/pdf/math/0306194v1.pdf)

### Lie groups and geometric integrators
- Differential Geometry and Lie Groups - A Computational Perspective by Jean Gallier, Jocelyn Quaintance
- [My notebook about geometric integrators](https://colab.research.google.com/drive/1Hywtnf9VIytS9UZlmUfl_dmJh3enHF6Y?usp=sharing)
- [Brynjulf Owren (2016), Lie group integrators](https://arxiv.org/pdf/1601.04664.pdf)
- [Ernst Hairer (2001), Geometric Integration of Ordinary Differential Equations on Manifolds](https://www.researchgate.net/publication/226065999_Geometric_Integration_of_Ordinary_Differential_Equations_on_Manifolds)
- [Ernst Hairer (2011), Solving Differential Equations on Manifolds (lecture notes)](https://www.unige.ch/~hairer/poly-sde-mani.pdf)
- [Hans Munthe-Kaas (2008). Coordinate Free Numerics, an abstract approach to Scientific Computing (lecture notes)](http://hans.munthe-kaas.no/work/Seminar08_files/LectureNotes.pdf)
- [Kenth Engø et al. (2001). DiffMan: An object-oriented MATLAB toolbox for solving differential equations on manifolds](http://hans.munthe-kaas.no/work/Blog/Entries/2001/1/1_Article__DiffMan__An_object-oriented_MATLAB_toolbox_for_solving_differential_equations_on_manifolds_files/engo01dao.pdf)
- [Alexander Lundervold (2011), Lie–Butcher series and geometric numerical integration on manifolds (PhD Thesis)](https://alexander.lundervold.com/assets/files/phdthesis.pdf)

### Complementary learning material
- Visual Geometry and Topology, Anatolij Fomenko
- [Excelente lists of books with commentary](https://math.stackexchange.com/questions/13575/teaching-myself-differential-topology-and-differential-geometry)
- [Discrete Differential Geometry (youtube playlist), Keenan Crane](https://www.youtube.com/watch?v=FRvhgkGKfSM&list=PL9_jI1bdZmz0hIrNCMQW1YmZysAiIYSSS)
- [Discrete Differential Geometry (lectures notes), Keenan Crane](http://www.cs.cmu.edu/~kmcrane/Projects/DDG/paper.pdf)
- Structure and Interpretation of Classical Mechanics, Susskind and Wisdom: to learn some of the physical motivation, Hamiltonian system, generalized coordinates and such, as well as more of the way they use their functional language. Also I am more or less comfortable with this book since my bachelor, and having previous memories exploring it might make it easier to explore some of the more advanced material. 
- [Sympletic integrators, Ernst Hairer](https://www.unige.ch/~hairer/poly_geoint/week2.pdf)


### Advanced and research material that I eventually want to cover
- [Lie group and exponential integrators: Theory, implementation, and applications. Håvard Berland - PhD Thesis](http://hdl.handle.net/11250/258127)
- [Conformal Symplectic and Relativistic Optimization, França et al](https://arxiv.org/pdf/1903.04100.pdf)
- [Dynamic, symplectic and stochastic perspectives on gradient-based optimization - Michael I. Jordan](https://people.eecs.berkeley.edu/~jordan/papers/jordan-icm.pdf)  
- [On Dissipative Symplectic Integration with Applications to Gradient-Based Optimization. Guilherme França, Michael I. Jordan, René Vidal](https://arxiv.org/pdf/2004.06840.pdf)
- [Symplectic Recurrent Neural Networks. Chen et al](https://openreview.net/forum?id=BkgYPREtPr)
- [Symplectic ODE-NEt: learning hamiltonian dynamics with control. Zhong et al](https://openreview.net/forum?id=ryxmb1rKDS)
- [Principles of Riemannian Geometry in Neural Networks. Michael Hauser, Asok Ray](https://proceedings.neurips.cc/paper/2017/hash/0ebcc77dc72360d0eb8e9504c78d38bd-Abstract.html)
- [Differential Geometry meets Deep Learning workshop](https://sites.google.com/view/diffgeo4dl/)
- [Only Bayes Should Learn a Manifold. Søren Hauberg](http://www2.compute.dtu.dk/~sohau/papers/onlybayes2018/paper.pdf)
- [Fast and robust shortest path on riemmanian manifolds learned from data. Arvanitidis et al ](http://proceedings.mlr.press/v89/arvanitidis19a/arvanitidis19a.pdf)
- [Manifold stochastic dynamics for bayesian learning. Mark Zlochin, Yaram Baram](https://proceedings.neurips.cc/paper/1999/file/d2cdf047a6674cef251d56544a3cf029-Paper.pdf)
- [Geometrically enriched latent spaces. Arvanitidis, Hauberg and Scholkopf](https://arxiv.org/pdf/2008.00565.pdf)
- [Variational Autoencoders with Riemmanian Brownian Motion Priors. Kalatzis et al](https://arxiv.org/pdf/2002.05227.pdf)
- [Variational Bayes on Manifold. Tran et al](https://arxiv.org/pdf/1908.03097.pdf)
- [Latent space oddity: on the curvature of deep generative models. Arvanitidis et al](https://arxiv.org/pdf/1710.11379.pdf)
- [The geometric foundations of hamiltonian monte carlo. Betancourt, Byrne, Livingstone, Girolami](https://arxiv.org/pdf/1410.5110.pdf)
- [Incomplete reparameterizations and equivalent metric. Betancourt](https://arxiv.org/pdf/1910.09407.pdf) 
- [A geometric theory of higher-order automatic differentiation. Betancourt](https://arxiv.org/pdf/1812.11592.pdf)
- [Generalizing the No-U-Turn sampler to riemannian manifolds. Betancourt](https://arxiv.org/pdf/1304.1920.pdf)
- [Normalizing Flows on Tori and Spheres, Rezende et al](http://proceedings.mlr.press/v119/rezende20a/rezende20a.pdf)
- [Introduction to normalizing flows for lattice field theory. Albergo et al](https://arxiv.org/pdf/2101.08176.pdf)
