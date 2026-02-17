# Galaxy Classification Project

## Goal

- Classify galaxies from [Sloan digitial Sky Survery](https://www.sdss.org/) or [Galaxy Zoo](https://galaxyzoo.org)
- Use Tensorflow, Sci-Kit Learn and PYMC to take different approaches to the data.

1. Clone repo
2. Run ( using [uv](https://docs.astral.sh/uv/) for package management.
```{bash}
# grab dependencies
uv sync
# run classification script
uv run python main.py
```

or with pip in your virtual environment (Python 3.12 used. Results may vary):

```{bash}
pip install -r requirements.txt
```

# Ideas to do

- [] **Data Preprocessing**: Applying image filters with `tf.image`, `scipy.ndimage` `ImageFilter`
- [ ] **Live SDSS Data Fetching**: Implement [`astroquery`](https://astroquery.readthedocs.io/) integration to pull spectra and images directly from [Sloan Digital Sky Survey (SDSS)](https://www.sdss.org/) SkyServer in real-time rather than using local files
- [ ] **CNN Development**: Develop and mprove CNN architecture
- [ ] **PyMC Development**: Enhance [PyMC](https://www.pymc.io/) Bayesian models for improved uncertainty quantification
- [ ] **PyMC DAG Visualization**: Create directed acyclic graphs for galaxy emulation models
- [ ] **Optimization**: Improve architecture and training for better performance and accuracy
- [ ] **Alternative Classification Approaches**: Explore other ML methods
