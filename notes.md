## Splitting audio into different tracks

Full product: https://splitter.ai/ 

Model idea 1: https://github.com/sigsep/open-unmix-pytorch/blob/master/openunmix/model.py

[Model diagram](https://pytorch.org/assets/images/sigsep_umx-diagram.png)

Model idea 2: (simple) https://sigsep.github.io/ismir2018_tutorial/#/39

More model ideas: 
https://sigsep.github.io/tutorials/#aes-virtual-symposium-2020-current-trends-in-audio-source-separation

dataset: https://sigsep.github.io/datasets/

How to load musedb dataset: https://github.com/sigsep/sigsep-mus-db

Example notebook:
https://colab.research.google.com/drive/1Zo6iSPIi6SjOAL7wg8yzVWkS9mjLgjI-#scrollTo=GzxqV0HgcK3n

Ideas: 
Start with 2 stem separation (vocals + accompaniment), maybe one layer LSTM and one layer fully connected

Final Project Deliverable:
Research, Theory, or Ethics needs to be done
Github, Jupyter notebook

Should likely convert to time-frequency domain, you can use edges of harmonics that don't overlap to back out of the overlapping frequencies


