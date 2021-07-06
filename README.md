# 9th Patatrack Hackathon

## Required Packages
The notebook requires three python packages: `notebook`, `uproot` and `numpy`.

You can install them in different ways based on your environment.

## Getting Started on SWAN

Login to SWAN `http://swan.cern.ch`.

Please consider that the default configuration should suffice.

Use the `Download project from git` button to clone the base repository `https://github.com/cms-patatrack/tue-hackathon-2021.git`.

You can run the `hackaton-demo` notebook from here.

Do not forget to uncomment the first line when executing the notebook for the first time to install the needed python packages.

## Getting Started on your Machine

### PIP

```
pip install numpy notebook uproot
```

### Anaconda

```
conda config --add channels conda-forge
conda update --all

conda install numpy
conda install notebook
conda install uproot
```

### Anaconda using the provided environment files
Another option is to use the [`environment.yml` file](environment.yml) provided by us.

Download the file describing the environment (you can dowload the file manually as well):
```
wget https://patatrack.web.cern.ch/patatrack/wiki/environment.yml
```

Create the environment:

```
conda env create -f environment.yml
```

Activate the environment:

```
conda activate cern-hackaton
```

You can execute jupyter using `jupyter notebook`.