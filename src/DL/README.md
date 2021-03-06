Deep Learning for Optimal Energy-Efficient Power Control in Wireless Interference Networks
==================

This code package is related to the following scientific article:

Bho Matthiesen, Alessio Zappone, Eduard A. Jorswieck, and Merouane Debbah, "[Deep Learning for Optimal Energy-Efficient Power Control in Wireless Interference Networks](https://arxiv.org/abs/1812.06920)," submitted to IEEE Journal on Selected Areas in Communication.

## Contents

The deep artificial neural network proposed in the paper cited above. Short description of files:


* `prepareDset.py`: Generates the dataset for training from the global Optimization results
* `dl.py`: The network
* `run.py`: Call this file to train the network and generate the models in `../../results/`
* `run_val_loss.py`, `val_loss.py`: The validation loss computed by Keras was not expected. We calculate it manually with these scripts
* `evaluate.py`: Evaluate the model against the test set
* `generalization.py`: Evaluate the model against the Hata-COST231 channel model

## Requirements

This code was compiled and tested with Python 3.6.6, [Keras](http://keras.io) 2.2.4, and [TensorFlow](https://www.tensorflow.org/) 1.12.0.


## Acknowledgements

The research of Bho Matthiesen and Eduard A. Jorswieck was supported in part by the Deutsche Forschungsgemeinschaft (DFG) in the [Collaborative Research Center 912 "Highly Adaptive Energy-Efficient Computing."](https://tu-dresden.de/ing/forschung/sfb912)

The work of A. Zappone and M. Debbah was funded by the European Commission through the H2020-MSCA IF-BESMART project under Grant Agreement 749336.

We thank the Center for Information Services and High Performance Computing (ZIH) at TU Dresden for generous allocations of computer time.


## License and Referencing

This program is licensed under the GPLv2 license. If you in any way use this code for research that results in publications, please cite our original article listed above.

