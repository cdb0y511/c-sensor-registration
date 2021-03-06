# c-sensor-registration
* <a href="https://arxiv.org/pdf/2001.04286.pdf" target="_blank">Nonparametric Continuous Sensor Registration.</a>

This repository contains examples of sensor registration using different manifolds and Lie groups. For the RGB-D visual odometry case, i.e., R^3 and SE(3), see:
<a href="https://github.com/MaaniGhaffari/cvo-rgbd" target="_blank">Continuous Direct Sparse Visual Odometry from RGB-D Images.</a>

**Continuous sensor registration** is a new mathematical framework that enables nonparametric joint semantic/appearance and geometric representation of continuous functions using data. The joint semantic and geometric embedding is modeled by representing the processes in a reproducing kernel Hilbert space. The framework allows the functions to be defined on arbitrary smooth manifolds where the action of a Lie group is used to align them. The continuous functions allow the registration to be independent of a specific signal resolution and the framework is fully analytical with a closed-form derivation of the Riemannian gradient and Hessian.

## Citations
* William Clark, Maani Ghaffari, Anthony Bloch. "Nonparametric Continuous Sensor Registration." arXiv preprint arXiv:2001.04286, 2020. https://arxiv.org/abs/2001.04286
```
@article{clark2020nonparametric,
  title={Nonparametric Continuous Sensor Registration},
  author={Clark, William and Ghaffari, Maani and Bloch, Anthony},
  journal={arXiv preprint arXiv:2001.04286},
  year={2020}
}
```
