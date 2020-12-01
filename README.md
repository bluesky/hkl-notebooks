[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/bluesky/hkl-notebooks/main)

I had to install PyGObject dependencies as described at https://pygobject.readthedocs.io/en/latest/getting_started.html.

I created a conda environment and installed hklpy from nsls2forge:

conda create -n hkl

conda activate hkl

conda install hklpy -c nsls2forge

pip install -e .
