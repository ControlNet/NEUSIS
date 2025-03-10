# NEUSIS: A Compositional Neuro-Symbolic Framework for Autonomous Perception, Reasoning, and Planning in Complex UAV Search Missions

<div align="center">
    <img src="assets/teaser.svg">
    <p></p>
</div>

<div align="center">
    <a href="https://github.com/ControlNet/NEUSIS/issues">
        <img src="https://img.shields.io/github/issues/ControlNet/NEUSIS?style=flat-square">
    </a>
    <a href="https://github.com/ControlNet/NEUSIS/network/members">
        <img src="https://img.shields.io/github/forks/ControlNet/NEUSIS?style=flat-square">
    </a>
    <a href="https://github.com/ControlNet/NEUSIS/stargazers">
        <img src="https://img.shields.io/github/stars/ControlNet/NEUSIS?style=flat-square">
    </a>
    <a href="https://arxiv.org/abs/2409.10196">
        <img src="https://img.shields.io/badge/arXiv-2409.10196-b31b1b.svg?style=flat-square">
    </a>
</div>


**This repo is the official repository for the paper [NEUSIS: A Compositional Neuro-Symbolic Framework for Autonomous Perception, Reasoning, and Planning in Complex UAV Search Missions](https://arxiv.org/abs/2409.10196).**

## Abstract

This paper addresses the problem of autonomous UAV search missions, where a UAV must locate specific Entities of Interest (EOIs) within a time limit, based on brief descriptions in large, hazard-prone environments with keep-out zones. The UAV must perceive, reason, and make decisions with limited and uncertain information. We propose NEUSIS, a compositional neuro-symbolic system designed for interpretable UAV search and navigation in realistic scenarios. NEUSIS integrates neuro-symbolic visual perception, reasoning, and grounding (GRiD) to process raw sensory inputs, maintains a probabilistic world model for environment representation, and uses a hierarchical planning component (SNaC) for efficient path planning. Experimental results from simulated urban search missions using AirSim and Unreal Engine show that NEUSIS outperforms a state-of-the-art (SOTA) vision-language model and a SOTA search planning model in success rate, search efficiency, and 3D localization. These results demonstrate the effectiveness of our compositional neuro-symbolic approach in handling complex, real-world scenarios, making it a promising solution for autonomous UAV systems in search missions.

## References
If you find this work useful for your research, please consider citing it.

```bibtex
@article{cai2024neusis,
  title={NEUSIS: A Compositional Neuro-Symbolic Framework for Autonomous Perception, Reasoning, and Planning in Complex UAV Search Missions},
  author={Cai, Zhixi and Cardenas, Cristian Rojas and Leo, Kevin and Zhang, Chenyuan and Backman, Kal and Li, Hanbing and Li, Boying and Ghorbanali, Mahsa and Datta, Stavya and Qu, Lizhen and Santiago, Julian Gutierrez and Ignatiev, Alexey and Li, Yuan-Fang and Vered, Mor and Stuckey, Peter J. and Garcia de la Banda, Maria and Rezatofighi, Hamid},
  journal={arXiv preprint arXiv:2409.10196},
  year={2024}
}
```
