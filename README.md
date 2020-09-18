# RVAgene : Recurrent Variational Auto gene encoder
## Software demonstration for the paper "Generative modeling of gene expression time series data with RVAgene"

`data` : contains example synthetic gene expression time series data with 6 inherent clusters
`rvagene` : contains code for recurrent variational autoencoder
`train_and_gen.py` : code demonstrating training RVAgene, unsupervised clustering on latent space using K-means and Generating new gene expression data by sampling and decoding points from latent space. 
`figs` : contains figures generated by the demo code.



![alt text](https://github.com/maclean-lab/RVAgene/blob/master/figs/demo.png?raw=true)

### Requirements:
1. Python 3
2. numpy, matplotlib, pytorch
3. GPU (optional).

### Acknowledgments

1. Thanks to open source implementation of recurrent VAE  at https://github.com/tejaslodaya/timeseries-clustering-vae
2. Relevant research works as cited in the work.

### Contributors
<a href="https://github.com/maclean-lab/RVAgene/graphs/contributors">
  <img src="https://con-img.web.app/image?repo=maclean-lab/RVAgene" />
</>
