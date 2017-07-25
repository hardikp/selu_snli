# selu_snli

This repo contains a simple Bag of Words model implemented in keras. The code was originally taken from [here](https://github.com/Smerity/keras_snli).

```bash
(h) [ hardik@Hardiks-MacBook-Pro ~/selu_snli ] python3 snli_rnn.py --activation selu --optimizer adam
```

### SELU vs RELU with BatchNormalization
<img src="selu_vs_relu_with_batchnorm.png">

### SELU vs RELU without BatchNormalization
<img src="selu_vs_relu_without_batchnorm.png">

A blog post about this experiment is [here](https://hardikp.github.io/2017/07/24/SELU-vs-RELU/).
