Question of Restraint analysis
=======================

By [Christian McDonald](https://github.com/critmcdonald), data editor

Analysis related to the [Question of Restraint](https://apps.statesman.com/question-of-restraint/) series by the Austin American-Statesman.

There are a series of folders:

- `notebooks` has the various Jupyter Notebooks that contain the analysis.
- `data_raw` is unprocessed data. These are typically downloaded from our django-based Data Warehouse, where the database of records was managed. That repo is not public.
- `exports` are results coming out of the notebooks. Might be data sets to use with graphics, interactives or between notebooks.
- `charts` are just that, as a result of notebook analysis. 

## Virtual environments

I use the [conda](https://conda.rtfd.org) python environment system. I used the [agate](https://agate.rtfd.org) and [jupyter](http://jupyter.org/) packages.

If you use conda, you can load the environment with this command:

``` bash
conda env create -f custody.yml
```

Then load the environment:

`source activate custody`

Then start jupyter:

`jupyter notebook`

Or you can use the `requirements.txt` file to load into your virtual environment of choice.

## Just looking?

You can browse the analysis in this github repo by going into the `notebooks` folder and viewing each file there. That will load the Jupyter Notebook with their results. Be sure to check out [the series](https://apps.statesman.com/question-of-restraint/) and the [database of cases](http://apps.statesman.com/question-of-restraint/data/).