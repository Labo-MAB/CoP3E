# CoP3E

__Authors__: Xavier Lapointe ([@Xavier919](https://github.com/Xavier919))

## Running CoP3E

### Requirements

All requirements to run CoP3E can be found in *requirements.txt*.

For conda users, all the required packages can be installed by creating an environment from *environmnent.yml*.

```{bash}
conda env create -n cop3e --file environmnent.yml
```

### Input files

All input files needed to run CoP3E are included in *data/*. However, due to github's file size limit, two were compressed into .xz and thus will need to be decompressed before running the notebooks.

### Steps to follow

1. Build the dataset with *CoP3E_EDA.ipynb*;
2. Extract the features with *CoP3E_features.ipynb*;
3. Train and evaluate the model's performance with *CoP3E_train_model.ipynb*.
