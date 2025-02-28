<h1 align="center">Hi 👋, I'm Alan Huynh</h1>
<h3 align="center">Machine Learning Engineer</h3>

- 📫 How to reach me **hdmquan@outlook.com**

- 📄 Know about my experiences [resume](https://drive.google.com/drive/folders/1A6dnkn7wuBs7CVXrILJjEz3_Y-O86hCF?usp=sharing)

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://linkedin.com/in//alan-huynh-64b357194" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="/alan-huynh-64b357194" height="30" width="40" /></a>
<a href="https://kaggle.com/hdmquan" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/kaggle.svg" alt="hdmquan" height="30" width="40" /></a>
</p>

git init
poetry init
mkdir data src results weights figures
cd src
mkdir models datasets utils notebooks
cd ..
touch data/raw/.gitkeep 
touch data/processed/.gitkeep
touch src/__init__.py 
touch src/utils/__init__.py
poetry add torch holoviews pandas numpy loguru

"""
from pathlib import Path
# packages = [{include = "src", from = "."}]

class Paths:
    ROOT = Path(__file__).parents[2]
    SRC = ROOT / "src"
    DATA = ROOT / "data"
    RESULTS = ROOT / "results"
    FIGURES = ROOT / "figures"
    WEIGHTS = ROOT / "weights"

    MODELS = SRC / "models"
    DATASETS = SRC / "datasets"
    UTILS = SRC / "utils"

    RAW_DATA = DATA / "raw"
    PROCESSED_DATA = DATA / "processed"
"""
