# music recommendation system tutorial #
This project implements a Graph Neural Network (GNN) for the task of recommendations, specifically focusing on the MAGNN
(Metapath Aggregated Graph Neural Network) architecture. The model is applied to the LastFM dataset for music
recommendations using a link prediction task. Use it as a tutorial for understanding how to use GNNs for RecSys
problems.

---

## Requirements ##
You would need Python 3.6 or later and some libraries to work with this repo:
- PyTorch
- Torch Geometric
- Matplotlib
- NetworkX
- NumPy
- Pandas
- Requests
- tqdm
- scikit-learn

Install the required packages using:
```bash
pip install -r requirements.txt
```

## Getting Started ##
Clone the repository:

```bash
git clone https://github.com/Zener085/music-recommendation-system-tutorial.git
cd music-recommendation-system-tutorial
```
Run the Jupyter notebook containing the code. You also can use
[online version](https://colab.research.google.com/drive/1hVaZUr2U3-yGvV6Rk5KQ3L85iYY8D1dz?usp=sharing#scrollTo=R2L01VOuWeeS)
of the notebook using colab.

## Dataset ##
The LastFM dataset is used for training and evaluation. It can be obtained from the
[LastFM PyTorch Geometric dataset](https://pytorch-geometric.readthedocs.io/en/latest/generated/torch_geometric.datasets.LastFM.html).
Additionally, features extracted from the dataset are utilized to enhance model accuracy.

## Model Architecture ##
The MAGNN architecture is employed for this recommendation task. The model comprises three major components: node
content transformation, intra-metapath aggregation, and inter-metapath aggregation. The workflow involves metapath-based
attention mechanisms to capture structural and semantic information from the heterogeneous graph.

## References ##
- [MAGNN Paper](https://arxiv.org/pdf/2002.01680.pdf)
- [LastFM PyTorch Geometric Dataset](https://pytorch-geometric.readthedocs.io/en/latest/generated/torch_geometric.datasets.LastFM.html)

## Contributors ##
- [Danil Kuchukov](https://github.com/xFonzie)
- [Artyom Makarov](https://github.com/Smulemun)
- [Timofey Didenko](https://github.com/Zener085)

Contributions are welcome! If you find any issues or have suggestions, please open an
[issue](https://github.com/your-username/your-repository/issues) or create a
[pull request](https://github.com/your-username/your-repository/pulls).
