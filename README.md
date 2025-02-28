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
<p>Cuz I'm too lazy to set up cookiecutter than write HTML. And it convenience.</p>

<pre>
<code>
git init
poetry init
touch .gitignore
touch README.md
mkdir data src results weights figures
cd src
mkdir models datasets utils notebooks
touch __init__.py
touch models/__init__.py 
touch dataset/__init__.py 
touch utils/__init__.py
cd ..
touch data/raw/.gitkeep 
touch data/processed/.gitkeep
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

