# fold3Dplot_jupyter
graphical viewer of the alphafold results in jupyter notebook
This is a jupyter notebook that draws the same figure as colabfold(https://colab.research.google.com/github/sokrypton/ColabFold/blob/main/AlphaFold2.ipynb) from the result of alphafold run on the local machine.

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

### Save graphs
If you want to save the plddt and pae graphs,
```
python3 save_foldplot.py alphafold_results_directory
```
saved coverage_lDDT.png and PAE.png


#### These were created using the colabfold code as a reference. Thank you very much.
