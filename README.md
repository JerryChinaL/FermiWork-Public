# FermiWork-Public
Improve resolution with LightGBM

The 200 and 2000 notebooks contain some early data explorations and visualizations.

data-prep generates clustered data, and saves them into files that are needed for LGB training. You don't need to run this again, as it takes 1-2 hours. The generated data files are stored in this Google Drive: https://drive.google.com/drive/folders/1w64OjJA48x3GsoZZP3_q90-wtlhHLh9e?usp=sharing

LGB training is done in valset.ipynb. Essentially, only this file needs to be run to generate most results in the slides.