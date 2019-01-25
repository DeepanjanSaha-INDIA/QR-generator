# Project: QR-generator

The following project generates QR (Quick Response) code for a corresponding to user input provided.

## Getting Started

Algorithm of how QR gets generated is provided in website link https://www.thonky.com/qr-code-tutorial/ , this project just
implements the algorithm in Jupyter notebook, using python programming langueage.

### Prerequisites

This project is done on Jupyter notebook, so basic understanding of Python programming is required. Also, 
[main file](https://github.com/DeepanjanSaha-INDIA/QR-generator/blob/master/qr_gen.ipynb) has dependencies on `pandas`,
`numpy`, `re` and `matplotlib` library, so make sure thses libraries are present ( although thses libraries gets installed
by default while installing Anaconda ).

## Running the tests

Just run the main file [qr_gen.ipynb](https://github.com/DeepanjanSaha-INDIA/QR-generator/blob/master/qr_gen.ipynb)
and it will prompt for only 2 inputs from the user, which are:

1. Data to be encoded
2. Error correction level involved.

And at the end of code it will generate corresponding QR code. This notebook also has theory well explained in Markdown cells,
and corresponding to it, appropriate code and its output is also displayed.
