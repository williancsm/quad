# quad

## clone submodules

git submodule update --init --recursive
git submodule init SUBMODULE
git submodule update

## install

python3 -m venv ./quad-venv
source quad-venv/bin/activate
pip install -U setuptools setuptools_scm wheel pip
pip install -r fprime/requirements.txt
