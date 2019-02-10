# Real-Time Joint Semantic Segmentation, Depth and Surface Normals Estimation (in PyTorch)

This repository provides official models from the paper `Real-Time Joint Semantic Segmentation and Depth Estimation Using Asymmetric Annotations`, available [here](https://arxiv.org/abs/1809.04766)

```
Real-Time Joint Semantic Segmentation and Depth Estimation Using Asymmetric Annotations
Vladimir Nekrasov, Thanuja Dharmasiri, Andrew Spek, Tom Drummond, Chunhua Shen, Ian Reid
In ICRA 2019
```

## Getting Started

For flawless reproduction of our results, the Ubuntu OS is recommended. The models have been tested using Python 2.7.

### Dependencies

```
pip
torch>=0.4.0
```
To install required Python packages, please run `pip install -r requirements.txt` (Python2) - use the flag `-u` for local installation.
The given examples can be run with, or without GPU.

## Running examples

For the ease of reproduction, we have embedded all our examples inside Jupyter notebooks.

### Jupyter Notebooks [Local]

If all the installation steps have been smoothly executed, you can proceed with running any of the notebooks provided in the `src/notebooks/` folder.
To start the Jupyter Notebook server, on your local machine run `jupyter notebook`. This will open a web page inside your browser. If it did not open automatically, find the port number from the command's output and paste it into your browser manually.
After that, navigate to the repository folder and choose any of the examples given.

## More to come

Once time permits, more things will be added to this repository:

* Training and evaluation examples

## More projects to check out

1. This project heavily relies on [Light-Weight RefineNet](https://github.com/DrSleep/light-weight-refinenet)

## License

For academic usage, this project is licensed under the 2-clause BSD License - see the [LICENSE](LICENSE.md) file for details. For commercial usage, please contact the authors.

## Acknowledgments

* University of Adelaide and Australian Centre for Robotic Vision (ACRV) for making this project happen
* HPC Phoenix cluster at the University of Adelaide for making the training of the models possible
* PyTorch developers
* Yerba mate tea
