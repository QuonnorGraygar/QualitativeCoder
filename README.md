# Jupyter Qualitative Coder

This repository contains a set of Jupyter notebooks that enable one to qualitatively code text responses in a Jupyter environment. This notebook presumes that the text data being coded is stored in a dataframe where each row contains one document of a larger corpus. The rows also contain identifying information and a column for coding completion status. To perform the actual qualitative coding: use `Qual_Coder.ipynb`. If you wish to collaborate with other coders, use `Code_Merger.ipynb`. When you are done coding, use `Tag2Flag.ipynb` to convert the codes into a more concise theme.

***NOTE: The `Code_Merge.ipynb` notebook is not nearly as well tested as I would like and so I recommend saving backups before using it.***
