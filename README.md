# Text Independant Speaker Verification
Implementation of Google's [__GE2E__](https://arxiv.org/pdf/1710.10467.pdf) 

### Dataset
Get _VoxCeleb1_ Dataset from [__here__](http://www.robots.ox.ac.uk/~vgg/data/voxceleb/vox1.html)

Get _QUT-NOISE_ Database from [__here__](https://research.qut.edu.au/saivt/databases/qut-noise-databases-and-protocols/)

#### Tensorboard visualization
```bash
tensorboard --logdir runs
```
#### Results
```bash
EER = 0.4735
```

### TODO
* ~~Implement gradient scaling and gradient clipping~~
* ~~Tensorboard Integration~~
* ~~Comments/Documentation~~
~~* Upload weights~~
* Implement Evaluation
* Implement EER
* Unknown Noise & SNR Analysis


