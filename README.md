# DCGAN-based-Image-synthesis

This is an experimental tensorflow implementation of synthesizing images. The images are synthesized using the GAN-CLS Algorithm from the paper [Generative Adversarial Network ImageSynthesis][1]. This implementation is built on top of the excellent.



## Requirements
- [TensorFlow] 1.0+
- [Imageio]

## Datasets
- The model is currently trained on the famous Fashion-MNIST.

**N.B**  You can downloads all data files needed manually or simply run the downloads.py and put the correct files to the right directories.
```python 
python downloads.py
```

## Codes
- `DCGAN.pynb` training the model.
- `plot_utils.py` helper functions for plotting Images.


## Results

<div align="center">
	<img src="dcgan_demo.gif" width="70%" height="70%"/>
</div>
</a>

[1]:https://www.diva-portal.org/smash/get/diva2:1180839/FULLTEXT02
