# autumncast-modeling
This repository contains jupyter notebooks used to assemble, clean, and process the data for the autumncast app (https://github.com/espriggs/autumncast-app).


### Prerequisites
To create a conda environment with all of the necessary packages do:

```
conda env create --file autumncast-model.yml
```

Activate the environment through:
```
conda activate autumncast-modeling
```

Notebooks can then be read and modified using 
```
jupyter-notebook
```

If you want to download the PRISM (daily or monthly) climate data. A really good package is available at:
git://github.com/sdtaylor/pyPRISMClimate. To install it, run:
```
pip install git+git://github.com/sdtaylor/pyPRISMClimate
```

## Authors

Elizabeth Spriggs

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments
