# ChemGAN challenge

* Code for the paper: Benhenda, M. 2017. [ChemGAN challenge for drug discovery: can AI reproduce natural chemical diversity? arXiv preprint arXiv:1708.08227.](https://arxiv.org/abs/1708.08227)

* Related blog post: [https://medium.com/the-ai-lab/chemgan-challenge-for-drug-discovery-can-ai-reproduce-natural-chemical-diversity-8f1f2528ee22](https://medium.com/the-ai-lab/chemgan-challenge-for-drug-discovery-can-ai-reproduce-natural-chemical-diversity-8f1f2528ee22)

* Chat room: [https://gitter.im/Startcrowd/drugdiscovery](https://gitter.im/Startcrowd/drugdiscovery) 

* Requirements: Rdkit version 2017.03.3 from Anaconda, Tensorflow 1.0.1

* The code has not been cleaned, don't hesitate to post an issue if you don't find what you are looking for.

* To make the DRD2 case work, take clf.pkl [here](  https://github.com/MarcusOlivecrona/REINVENT/releases), rename it clf_drd2.pkl, and put it in the appropriate folder. It's the SVM activity model of DRD2 by Marcus Olivecrona.

* To make the QED case work, you need [Silicos-it](http://silicos-it.be.s3-website-eu-west-1.amazonaws.com/software/biscu-it/qed/1.0.1/qed.html).

* In order to train the model, cd into `model` and run

```python train_ogan.py exp.json```

where `exp.json` is a experiment configuration file.

* This code is otherwise based on [ORGAN](https://github.com/gablg1/ORGAN). Many thanks to the ORGAN team.
