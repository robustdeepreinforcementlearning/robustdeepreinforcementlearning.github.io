<div align="center">
  Ezgi Korkmaz  <br />
  Conference on Uncertainty in Artificial Intelligence (UAI) 2021 <br />
  Published in Proceedings of Machine Learning Research (PMLR) 2021
  </div>


### Abstract



Reinforcement learning policies based on deep neural networks are vulnerable to imperceptible adversarial perturbations to their inputs, in much the same way as neural network image classifiers. Recent work has proposed several methods to improve the robustness of deep reinforcement learning agents to adversarial perturbations based on training in the presence of these imperceptible perturbations (i.e. adversarial training). In this paper, we study the effects of adversarial training on the neural policy learned by the agent. In particular, we follow two distinct parallel approaches to investigate the outcomes of adversarial training on deep neural policies based on worst-case distributional shift and feature sensitivity. For the first approach, we compare the Fourier spectrum of minimal perturbations computed for both adversarially trained and vanilla trained neural policies. Via experiments in the OpenAI Atari environments we show that minimal perturbations computed for adversarially trained policies are more focused on lower frequencies in the Fourier domain, indicating a higher sensitivity of these policies to low frequency perturbations. For the second approach, we propose a novel method to measure the feature sensitivities of deep neural policies and we compare these feature sensitivity differences in state-of-the-art adversarially trained deep neural policies and vanilla trained deep neural policies. We believe our results can be an initial step towards understanding the relationship between adversarial training and different notions of robustness for neural policies.


[[Paper]](https://proceedings.mlr.press/v161/korkmaz21a/korkmaz21a.pdf)   [[PMLR]](https://proceedings.mlr.press/v161/korkmaz21a.html)  [[Cite]](ekuaibibtex.html)


Versions of this work presented in ICLR and ICML workshops and received Spotlight Presentation from NeurIPS workshop.


<span style="color: white;"> Key words: reinforcement learning, deep reinforcement learning, adversarial, adversarial attack, robustness, policy, DeepRL, DRL, robust, adversarial policies </span>



