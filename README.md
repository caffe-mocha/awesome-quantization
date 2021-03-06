# Awesome Quantization Paper lists with Codes
Awesome Quantization Paper lists with Codes.



<h2>Quantization categories</h2>

- Quantized weights + activation, during training and test (Training aware Quantization)  
  - LSQ  
  - QIL  
  - LQ-Nets  
- Quantized weights + activation, during test (Post training Quantization)  
  - ZeroQ  
  - OCS  
  - ACIQ  



<br>



<h2>Papers with codes</h2>


| Quantize method |                            Tiitle                            | conference |                             code                             | Train / Inference |
| :-------------: | :----------------------------------------------------------: | :--------: | :----------------------------------------------------------: | :---------------: |
|       LSQ       | [Learned Step Size Quantization](https://arxiv.org/abs/1902.08153) | ICLR 2020  | [Unofficial, Pytorch](https://github.com/hustzxd/LSQuantization) |  Training aware   |
|       QIL       | [Learning to Quantize Deep Networks by Optimizing Quantization Intervals with Task Loss](https://arxiv.org/abs/1808.05779) | CVPR 2019  | [Unofficial, Pytorch](https://github.com/csyhhu/Awesome-Deep-Neural-Network-Compression/tree/master/Codes) |  Training aware   |
|     LQ-Nets     | [Learned Quantization for Highly Accurate and Compact Deep Neural Networks](https://arxiv.org/pdf/1807.10029.pdf) | ECCV 2018  | [Official, Tensorflow](https://github.com/microsoft/LQ-Nets) |  Training aware   |
|      PACT       | [PACT: Parameterized Clipping Activation for Quantized Neural Networks](https://arxiv.org/abs/1805.06085) |            |                                                              |  Training aware   |
|      ZeroQ      | [ZeroQ: A Novel Zero Shot Quantization Framework](https://arxiv.org/abs/2001.00281) | CVPR 2020  |  [Official, Pytorch](https://github.com/amirgholami/ZeroQ)   |   Post training   |
|       OCS       | [Improving Neural Network Quantization without Retraining using Outlier Channel Splitting](https://arxiv.org/abs/1901.09504) | ICML 2019  | [Official, Pytorch](https://github.com/cornell-zhang/dnn-quant-ocs) |   Post training   |
|      ACIQ       | [Post-training 4-bit quantization of convolution networks for rapid-deployment](https://arxiv.org/abs/1810.05723) | NIPS 2019  | [Official, Pytorch](https://github.com/submission2019/cnn-quantization) |   Post training   |



<br>

- Code reference: pytorch-quant  [[github, Pytorch]](https://github.com/wjc852456/pytorch-quant)

| Quantize method |                            Tiitle                            | conference | Train / Inference |   scale    |
| :-------------: | :----------------------------------------------------------: | :--------: | :---------------: | :--------: |
|     Minmax      | [Quantization and Training of Neural Networks for Efficient Integer-Arithmetic-Only Inference](https://arxiv.org/abs/1712.05877) | CVPR 2018  |  Training aware   |   minmax   |
|   Log Minmax    | [Convolutional Neural Networks using Logarithmic Data Representation](https://arxiv.org/abs/1603.01025) | arXiv 2016 |  Training aware   | log minmax |
|      Tanh       | [Quantized Neural Networks: Training Neural Networks with Low Precision Weights and Activations](https://arxiv.org/abs/1609.07061) | arXiv 2016 |  Training aware   |    tanh    |





<h2>Other papers</h2>
Earlier paper lists.

- Deep Compression
  - Deep Compression: Compressing Deep Neural Networks with Pruning, Trained Quantization and Huffman Coding, Song Han et al, ICLR2016(oral)  [[paper]](https://arxiv.org/abs/1510.00149)  [[code]](https://github.com/synxlin/nn-compression)
- DoReFa-Net
  - DoReFa-Net: Training Low Bitwidth Convolutional Neural Networks with Low Bitwidth Gradients, Shuchang Zhou et al  [[paper]](https://arxiv.org/abs/1606.06160)  [[code]](https://github.com/tensorpack/tensorpack/tree/master/examples/DoReFa-Net)
- BNN
  - Binarized Neural Networks, Itay Hubara et al, NIPS 2016  [[paper]](https://papers.nips.cc/paper/6573-binarized-neural-networks)  [[code]](https://github.com/itayhubara/BinaryNet.pytorch)
- XNOR-Net
  - XNOR-Net: ImageNet Classification Using Binary Convolutional Neural Networks, Mohammad Rastegari et al  [[paper]](https://arxiv.org/abs/1603.05279)  [[code]](https://github.com/jiecaoyu/XNOR-Net-PyTorch)



<h2>Awesome lists</h2>
Awesome lists which is good for reference.

- Awesome Deep Neural Network Compression  [[github]](https://github.com/csyhhu/Awesome-Deep-Neural-Network-Compression)

<br>



```
# Author
- Subin Yang
- ysb8049@gmail.com
```

