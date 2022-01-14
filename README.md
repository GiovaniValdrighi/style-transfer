# Neural Style Transfer

Project on the discipline of Neural Networks of the Master Course in Mathematical Modeling at EMAp FGV. In this work, I reproduce the work in the article _A Neural Algorithm of Artistic Style_, by Leon A. Gays, Alexander S. Ecker and Matthis Bethge. Some tests are made in how to adapt the style transfer for videos. It was made use of Pytorch for the implementation. There is a web-page with the explanation of the [implementation](https://giovanivaldrighi.github.io/style-transfer/). You can make few changes on the code to run the style transfer on your own images.

![Style and Content](https://raw.githubusercontent.com/GiovaniValdrighi/style-transfer/main/docs/output_23_0.png)

![Style transfer](https://raw.githubusercontent.com/GiovaniValdrighi/style-transfer/main/docs/output_25_0.png)

# Files organization

The files of the project are separated in the following folders:

- `docs/`: documentation of the project, files for the web-age.

- `notebooks/`: two Jupyter Notebooks with the implementation of the algorithm and some tests on videos.

- `scripts/`: file for the implementation as a Python script.

# Requirements

The implementation made use of the language [Python](https://www.python.org/) and Jupyter Notebooks avaiable at [Anaconda](https://www.anaconda.com/). The necessary libraries are:

- [torch](https://pytorch.org/)
- urllib
- PIL
- pickle
- matplotlib
- tqdm
- cv2

# How to run

1. All the work was made in Jupyter Notebooks, so to run my examples, just run all cells.
2. To run a example with one image of yours, on the Notebook `neural_style_transfer.ipynb`, in the last cells, just change the path of the content and the style images for you desired.

# Reference

- A Neural Algorithm of Artistic Style, by Leon A. Gays, Alexander S. Ecker and Matthis Bethge.