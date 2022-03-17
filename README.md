# Accessing and Analyzing Danish Asylum Case Summaries

This repository contains jupyter (notebooks)[https://jupyter.org/] that can be run to scrape and analyze the publicly available dataset 
of asylum case summaries provided by the Danish Refugee Appeals Board (Flygtningenævnet).
The dataset is **NOT** part of this repo, but can be accessed (here)[https://fln.dk/da/Praksis].
The notebooks contain the code that corresponds to the data analysis that has been carried out for the ECSCW 2022 Note (link).

## Before you run the notebooks

The `requirements.txt` file lists list all Python libraries that your notebooks
depend on, and they will be installed using:

```
pip install -r requirements.txt
```

To scrape the data, you have to also install adrive to interface with the chosen browser. In this repo, Firefox is used.
Find a guide on how to install drivers for selenium (here)[https://selenium-python.readthedocs.io/installation.html].

## Plans for this repo

This repo will be extended with further data analysis. Feel free to contribute yourself.
