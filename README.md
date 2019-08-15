# ssd-notebook-playground
Jupyter notebooks for playing around with SSD model.

## Setting up
```bash
# Clone repo and submodules
git clone https://github.com/xsible/ssd-notebook-playground.git
cd ssd-notebook-playground
git submodule update --init --recursive

# Setup environment
python3 -m venv env
source env/bin/activate
pip3 install -r ssd.pytorch/requirements.txt -f https://download.pytorch.org/whl/torch_stable.html

# Setup juypter
pip install jupyter # not part of requirements.txt since it's only needed for notebook functionality
jupyter notebook
```
