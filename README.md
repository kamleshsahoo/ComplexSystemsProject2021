## Required Python dependencies
Besides the standard python data analysis (*numpy, pandas, scipy*) and plotting libraries (*matplotlib*), please install the following: 
- *Rise* extension for Jupyter sildeshow  
https://rise.readthedocs.io/en/stable/installation.html  
- *NetworkX* extension for analysing network structures.  
https://networkx.org/documentation/stable/install.html  
- *SALib* package for sensitivity analysis.  
https://salib.readthedocs.io/en/latest/getting-started.html#installing-salib  
- *seaborn* package.  
https://seaborn.pydata.org/installing.html
- *tqdm* package.  
https://anaconda.org/conda-forge/tqdm
- Though animation is included in *matplotlib*, one may require to install the *ffmpeg* extension.  
https://pypi.org/project/ffmpeg-python/  

## Netlogo Model  
- Install Netlogo from https://ccl.northwestern.edu/netlogo/ 

- Our final model can also be run from a web browser at http://www.netlogoweb.org/launch?#https://kamleshsahoo.github.io./Depression.nlogo. However, for efficieny reasons we recommend installing Netlogo.

- The sensitivity analysis is based on the Netlogo model. To avoid the long execution times we have included the sensitivity analysis results as 'ouput.txt' file which is based on 7200 parameter combinations each running for 5000 time points. To do the analysis again, run the 'sobol_analysis.nlogo' file. Additional comments are included in the file and Appendix. 

## Gephi
- Install Gephi from https://gephi.org/  

## Note  
- 'Extract-Here' (on *Windows Machine*) the 'data-files.zip' so that the data files are extracted in the same folder where the jupyter notebook files are running. This will avoid any conflicts when running the presentation slides and sensitivity analysis.
