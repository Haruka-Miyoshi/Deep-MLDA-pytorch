# **Deep-MLDA**
The MLDA is a topic model that extends Latent Dirichlet Allocation for multimodal learning, developed primarily as a multimodal model to address the symbol grounding problem in robotics [nakamura2011grounding].<br>
In recent years, models that extend MLDA to a deep learning-based framework have been proposed [Tatsuya AOKI2019].<br>
This repository provides a program implementing Deep MLDA in PyTorch.<br>
In `main.ipynb`, the repository also includes training on the MNIST dataset using the DeepMLDA module, along with evaluations of reconstructed images and assessments of the latent variable space.

## **Reference**
```
@article{nakamura2011grounding,
  title={Grounding of word meanings in latent dirichlet allocation-based multimodal concepts},
  author={Nakamura, Tomoaki and Araki, Takaya and Nagai, Takayuki and Iwahashi, Naoto},
  journal={Advanced Robotics},
  volume={25},
  number={17},
  pages={2189--2206},
  year={2011},
  publisher={Taylor \& Francis}
}
```
```
@article{Tatsuya AOKI2019,
  title={Hierarchical Neural Topic Model for Multimodal Learning},
  author={Tatsuya AOKI and Masato MINAMISAKA and Takayuki NAGAI},
  journal={Proceedings of the Annual Conference of JSAI},
  volume={JSAI2019},
  number={ },
  pages={1I4J204-1I4J204},
  year={2019},
  doi={10.11517/pjsai.JSAI2019.0_1I4J204}
}
```