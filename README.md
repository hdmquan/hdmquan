<h1 align="center">Hi 👋, I'm Alan Huynh</h1>
<h3 align="center">Machine Learning Engineer</h3>

<p>📫 How to reach me <strong>hdmquan@outlook.com</strong></p>
<p>📄 Know about my experiences <a href="https://drive.google.com/file/d/1GISOfYvoKFmbeK9PdHXdraugFqgg4SGW/view?usp=sharing" target="_blank">resume</a></p>

<h3 align="left">Connect with me:</h3>
<p align="left">
    <a href="https://linkedin.com/in/hdmquan" target="_blank">
        <img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn" height="30" width="40" />
    </a>
    <a href="https://kaggle.com/hdmquan" target="_blank">
        <img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/kaggle.svg" alt="Kaggle" height="30" width="40" />
    </a>
</p>

<h2>Project Setup</h2>
<p>Cuz I'm too lazy to set up cookiecutter than write HTML</p>

<pre>
<code>
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
</code>
</pre>

<pre>
<code>
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
</code>
</pre>

