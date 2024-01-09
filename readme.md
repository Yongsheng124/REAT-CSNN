## GAF-CSNN

### Install

It's recommended to set up a virtual Python environment with conda

`conda create -n gafcsnn python=3.8`
`conda activate gcfcsnn`

Install Python dependencies

`python install -r requirements.txt`

### Train

Firstly, you should create right folder to data based on your requirements  through :

`python setup.py`

To transform Time Series into Gramian Angular Fieldrun,you can run  with

`python im_fr_pr.py`

Then ,in order for the network to handle your data correctly,you should run with:

`python SNN/sort.py`

In the end ,you can train your model through :

`python SNN/M_mainC_C.py`