# CNN + KAN
Single epoch CNN+KAN trial on MNIST with 96% accuracy. You could give it a shot with the Notebook or via the [Colab](https://colab.research.google.com/drive/1eMnGUOYeoShR7n1KkLgTt985qtursDY6#scrollTo=QaUPxiJleN-D) link. 

## Remarks
* Loss is very unstable. 
  Maybe its related to parameter settings, however whenever I try few epochs (3+) weights kept exploding.

```
Train Epoch: 0 [0000/6000 (00%)]	Loss: 1.662824
Train Epoch: 0 [0640/6000 (11%)]	Loss: 0.500479
Train Epoch: 0 [1280/6000 (21%)]	Loss: 0.287909
Train Epoch: 0 [1920/6000 (32%)]	Loss: 0.221105
Train Epoch: 0 [2560/6000 (43%)]	Loss: 0.107704
Train Epoch: 0 [3200/6000 (53%)]	Loss: 0.146229
Train Epoch: 0 [3840/6000 (64%)]	Loss: 0.077108
Train Epoch: 0 [4480/6000 (74%)]	Loss: 0.157832
Train Epoch: 0 [5120/6000 (85%)]	Loss: 0.075530
Train Epoch: 0 [5760/6000 (96%)]	Loss: 0.064992

Test set: Average loss: 0.0007, Accuracy: 9620/10000 (96%)
```

* Other backprops algorithms I tried do not work.

## Acknowledgement
Original work: [pyKAN](https://github.com/KindXiaoming/pykan)

Fourier coef:  [FourierKAN](https://github.com/GistNoesis/FourierKAN/)
