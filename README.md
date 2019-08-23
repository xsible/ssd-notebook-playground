# ssd-notebook-playground
Jupyter notebooks for playing around with SSD model.

## Setting up
```bash
# Clone repo and submodules
git clone --recursive https://github.com/xsible/official-website.git
cd ssd-notebook-playground

# Setup environment (regular)
python3 -m venv env
source env/bin/activate
pip3 install -r ssd.pytorch/requirements.txt

# Setup juypter
pip install jupyter # not part of requirements.txt since it's only needed for notebook functionality
jupyter notebook
```