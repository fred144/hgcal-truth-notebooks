# HGCAL truth tutorial notebooks

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
