# fold3Dplot_jupyter
Graphical viewer of the alphafold results in jupyter notebook.

This is a jupyter notebook that draws the same figure as ColabFold (https://colab.research.google.com/github/sokrypton/ColabFold/blob/main/AlphaFold2.ipynb) from the result of AlphaFold (https://github.com/deepmind/alphafold) run on the local machine.

### Requirements
+ numpy
+ pickle
+ py3Dmol
+ matplotlib.pyplot
+ ipywidgets
+ alphafold (for save graphs (coverage_lDDT.png and PAE.png) only)
+ jupyter-notebook

### 3D plot on jupyter notebook
put `fold3Dplot.ipynb` in the result directory of alphafold.
```
{mv,cp} fold3Dplot.ipynb alphafold_results_directory/
```

Start jupyter
```
jupyter-notebook
```

Open fold3Dplot.ipynb on jupyter and run.
The display changes interactively when the parameters are changed.

![af](https://user-images.githubusercontent.com/1720098/130024182-d9659b44-00a9-4c5d-9947-00bdf02c5280.png)



### Save graphs
If you want to save the plddt and pae graphs,
```
python3 save_foldplot.py alphafold_results_directory
```
saved coverage_lDDT.png and PAE.png


#### These were created using the ColabFold code as a reference. I would like to thank the ColabFold.
