Run the `bluesky_hkl` notebook in this repository with binder:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/bluesky/hkl-notebooks/main)

Or install the repository and run it locally. This method of installing hklpy works only on Linux at this time.
```bash
conda create -n hkl python=3.8
conda activate hkl
conda install hklpy -c nsls2forge
git clone https://github.com/bluesky/hkl-notebooks.git
cd hkl-notebooks
pip install .
cd notebooks
jupyter notebook
```
