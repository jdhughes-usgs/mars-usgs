# mars-usgs
AGU24 resources for P12A-05


# Getting started

1. Clone the repository using `git clone https://github.com/jdhughes-usgs/mars-usgs.git`.
2. Open a terminal in the root repository folder.
2. Install the conda environment using `mamba env create -f environment.yml`.
2. Activate the `agu2024mars` environmnent.
3. Install MODFLOW using `get-modflow --repo modflow6-nightly-build :python`.
4. Update the flopy MODFLOW 6 classes using `python -m flopy.mf6.utils.generate_classes --ref develop`.
5. Start jupyter lab.
6. Run the `step2-base-model` jupyter notebook.

