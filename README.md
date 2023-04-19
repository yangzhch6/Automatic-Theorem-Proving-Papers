# Automatic Theorem Proving Papers 

## Proof Assistant
1. [MetaMath](https://us.metamath.org/mpeuni/mmset.html)
2. [Lean](https://leanprover-community.github.io/)
3. [Isabelle](https://isabelle.in.tum.de/)

## Proof Procedural
A proof step in proof assistant can be formalized as:
> goal -> tatic -> [subgoals]

Here, the **goal** can be a theorem or just an intermediate step in the proof process. The **tatic** is a step/mechanism that, with the help of proof assistant, the current goal will be decomposed into subgoal(s). If there is no subgoal to be generated, then the current goal is successfully proven. 

For a theorem, it self will be considered as a root goal in the proof assistant, our ultimate destination is to repeat the above proof step until all decomposed subgoals to be proven.

For Automatic Theorem Proving (ATP), we need to achieve an AI to automatically generate tatics for each given goal, and design an efficient search algorithm to quickly reach the end of the proof.

## Paper List
1. Generative Language Modeling For Automated Theorem Proving [[paper]](https://arxiv.org/pdf/2009.03393.pdf)
2. Proof Artifact Co-Training For Theorem Proving With Language Models [[paper]](https://openreview.net/pdf?id=rpxJc9j04U)
3. HyperTree Proof Search for Neural Theorem Proving [[paper]](https://proceedings.neurips.cc/paper_files/paper/2022/hash/a8901c5e85fb8e1823bbf0f755053672-Abstract-Conference.html)