This repository contains supplementary material for the article "[Prescriptive Process Monitoring for Cost-Aware Cycle Time Reduction](https://arxiv.org/abs/2105.07111)" by [Zahra Dasht Bozorgi] (https://scholar.google.com/citations?user=XFsTnkgAAAAJ&hl=en), [Irene Teinemaa](https://irhete.github.io/), [Marlon Dumas](http://kodu.ut.ee/~dumas/), [Marcello La Rosa](http://www.marcellolarosa.com/), and [Artem Polyvyanyy](https://scholar.google.com.au/citations?user=CTF5-1EAAAAJ&hl=en).

## Reference
If you use the code from this repository, please cite the original paper:
```
@article{bozorgi2021prescriptive,
  title={Prescriptive Process Monitoring for Cost-Aware Cycle Time Reduction},
  author={Bozorgi, Zahra Dasht and Teinemaa, Irene and Dumas, Marlon and La Rosa, Marcello},
  journal={arXiv preprint arXiv:2105.07111},
  year={2021}
}
```

## Dependencies

* python 3.7
* [NumPy](http://www.numpy.org/)
* [pandas](http://pandas.pydata.org/)
* [scikit-learn](http://scikit-learn.org/stable/index.html)
* [EconML](https://github.com/microsoft/EconML) (for causal models construction)



## Preprocessing

For ease of use, the preprocessed datasets for BPIC17 and BPIC19 can be found [here] () and [here] () respectively. These datasets include the cycle time, treatment indicator and the potentially confounding features as discussed in the paper. 



## Experiments
The results of our experiments can be reproduced by running all the cells of bpi2017_experiments.ipynb and bpi2019_experiments.ipynb.