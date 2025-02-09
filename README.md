# HGCAL truth tutorial notebooks

### PHYS 165 Final Project, Fall 2021

This package and some of its features were used for this project.
Credit to https://github.com/tklijnsma.

### Update 
Project has changed and migrated to.
https://github.com/fred144/hgcal-py-analysis


__________________________________________________________
This repo requires python 3.

First setup a virtual environment:

```
python3 -m venv myhgcalenv
source myhgcalenv/bin/activate
```

Then install a few packages:

```
pip install devhgcaltruth
pip install notebook
pip install plotly
```

Clone this repository:

```
git clone https://github.com/tklijnsma/hgcal-truth-notebooks.git
cd hgcal-truth-notebooks
```

Download the data:

```
wget https://cernbox.cern.ch/index.php/s/lYNghQUwb4htXhL/download -O hgcalntups.tar
mkdir ntups
tar xvf hgcalntups.tar -C ntups/
rm hgcalntups.tar
```

And run a jupyter notebook:

```
jupyter-notebook
```
