

> Cloned from https://codebase.helmholtz.cloud/nils.brinckmann/sta-demo/ to test repo2docker github build integration


# Demo for STA usage with python

## Install the dependencies

```
python3 -m venv venv
source venv/bin/activate
python3 -m pip install -r requirements.txt
```


## Start the notebook

```
jupyter notebook
```

Then open `STA-Demo`.

## What will be shown?

The code fetches a complete datastream via the SensorThings API standard from
one of the data providing servers.

It will then plot the data with matplotlib.


## Run the demo with binder

You can run this notebook directly from your browser with [binder](https://mybinder.org/) using the following link:

https://mybinder.org/v2/git/https%3A%2F%2Fcodebase.helmholtz.cloud%2Fnils.brinckmann%2Fsta-demo.git/main?labpath=STA-Demo.ipynb
