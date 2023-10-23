# CanonCommentsQmd
Quarto output of all canon comments

This repository contains the code to generate an overview of all elaborations on questions from the 2022 [Canonenquête survey](https://ctb.kantl.be/projecten/wetenschappelijke-ondersteuning-literaire-canon-en-canonfestival). The aim of the overview is to provide an accessible means of accessing the wealth of free comments found in the dataset. I also saw this as an exercise in using [Quarto](https://quarto.org/) for data dissemination purposes.

## How to access the overview?

The online overview is available at [here](https://anthesevenants.github.io/CanonCommentsQmd/).

## Can I download the overview?

Yes. Word output is available from the [Releases](https://github.com/AntheSevenants/CanonCommentsQmd/releases) tab.

## How do I render the overview myself?

You can render the overview using [Quarto](https://quarto.org/) and Python. Make sure to install the necessary dependencies from `requirements.txt`. Then, you can render `index.qmd` found in this repository.

Also, make sure you have downloaded the [dataset](https://zenodo.org/records/10033489). Place it inside the repository directory as `data_anon.csv`.