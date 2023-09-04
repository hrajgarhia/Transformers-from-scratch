# Transformers-from-scratch
Repository for writing code of transformers from scratch for Machine translation task in PyTorch. The code
is designed for educational purpose and to understand the different components involved in the transformers architecture.


### Running on your machine

To run the scripts on your own machine, first clone the repository and navigate to it:

```bash
$ git clone https://github.com/hrajgarhia/Transformers-from-scratch.git
$ cd Transformers-from-scratch
```

Next, run the following command to create a `conda` virtual environment that contains all the libraries needed to run the notebooks:

```bash
$ conda env create -f environment.yml
```


Once you've installed the dependencies, you can activate the `conda` environment as follows:

```bash
$ conda activate tfs
```


Once you've activated the `tfs conda` environment, you can start training the transformers for machine translation tasks as follows:

```bash
$ python train.py
```