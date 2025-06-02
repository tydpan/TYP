# Transfer Your Perspective: Controllable 3D Generation from Any Viewpoint in a Driving Scene
**CVPR 2025**

[Tai-Yu Pan](https://tydpan.github.io/), [Sooyoung Jeon](https://jeonso0907.github.io/), [Mengdi Fan](https://www.linkedin.com/in/mengdifan/), [Jinsu Yoo](https://jinsuyoo.info/), [Zhenyang Feng](https://github.com/DeFisch), [Mark Campbell](https://campbell.mae.cornell.edu/), [Kilian Q Weinberger](https://www.cs.cornell.edu/~kilian/), [Bharath Hariharan](https://www.cs.cornell.edu/~bharathh/), [Wei-Lun Chao](https://sites.google.com/view/wei-lun-harry-chao/home)

[[arXiv]](https://arxiv.org/abs/2502.06682) [[`BibTeX`](#citing-typ)]

![](feature.gif)

## Introduction
Self-driving cars relying solely on ego-centric perception face limitations in sensing, often failing to detect occluded, faraway objects. Collaborative autonomous driving (CAV) seems like a promising direction, but collecting data for development is non-trivial. It requires placing multiple sensor-equipped agents in a real-world driving scene, simultaneously! As such, existing datasets are limited in locations and agents. We introduce a novel surrogate to the rescue, which is to generate realistic perception from different viewpoints in a driving scene, conditioned on a real-world sample - the ego-car's sensory data. This surrogate has huge potential: it could potentially turn any ego-car dataset into a collaborative driving one to scale up the development of CAV. We present the very first solution, using a combination of simulated collaborative data and real ego-car data. Our method, Transfer Your Perspective (TYP), learns a conditioned diffusion model whose output samples are not only realistic but also consistent in both semantics and layouts with the given ego-car data. Empirical results demonstrate TYP's effectiveness in aiding in a CAV setting. In particular, TYP enables us to (pre-)train collaborative perception algorithms like early and late fusion with little or no real-world collaborative data, greatly facilitating downstream CAV applications.

## ColWaymo
[Download Link](https://buckeyemailosu-my.sharepoint.com/:f:/g/personal/jeon_193_buckeyemail_osu_edu/Eh41G80WCnFKs_yIINv1MoUBBvijCuzwZ_Aqwz6FdWV23w?e=Pl5T3n). 

Please follow [OpenCOOD](https://github.com/DerrickXuNu/OpenCOOD?tab=readme-ov-file) and [V2V4Real](https://github.com/ucla-mobility/V2V4Real) to organize the folder structure for training and visualization.

## Code Release Soon...

## <a name="CitingTYP"></a>Citing TYP

If you use TYP in your research, please cite with the following BibTeX entry.

```BibTeX
@inproceedings{pan2025typ,
  title={Transfer Your Perspective: Controllable 3D Generation from Any Viewpoint in a Driving Scene},
  author={Pan, Tai-Yu and Jeon, Sooyoung and Fan, Mengdi and Yoo, Jinsu and Feng, Zhenyang and Campbell, Mark and Weinberger, Kilian Q and Hariharan, Bharath and Chao, Wei-Lun},
  journal={CVPR},
  year={2025}
}
```
