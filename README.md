# AlloLib

AlloLib allows to perform protein binding/mutation perturbations aimed at studing their allosteric effect according to the Structure Based Statistical Mechanical Model of Allostery (SBSMMA), which is based on the publications:

Guarnera and Berezovsky, Structure-Based Statistical Mechanical Model Accounts for the Causality and Energetics of Allosteric Communication. PLoS Comput Biol 12, e1004678 (2016), https://doi.org/10.1371/journal.pcbi.1004678


Guarnera and Berezovsky, Toward Comprehensive Allosteric Control over Protein Activity, Structure (2019), https://doi.org/10.1016/j.str.2019.01.014

The models have also been implemented in the AlloSigma server which is a platform for the analysis of allosteric effects in proteins (https://allosigma.bii.a-star.edu.sg). See for instance

Guarnera , Tan, Zheng, and Berezovsky, AlloSigMA: allosteric signaling and mutation analysis server. Bioinformatics 33, 3996–3998 (2017). https://doi.org/10.1093/bioinformatics/btx430
AlloLib makes exstensive use of MMTK packages (http://dirac.cnrs-orleans.fr/MMTK.html), which works only with numpy up to version 1.8.2, it is therefore recommended to set up an anaconda virtual enviroment with MMTK installed (see for instance https://anaconda.org/ngraymon/mmtk) along with all other packages compatible with version 1.8.2.

Check below the output of the "pip list" command with the versions of some of the packages installed in the enviroment where this notebook was compiled.

idisplay 0.1.2
ipykernel 4.8.2
ipython 5.8.0
ipython-genutils 0.2.0
ipywidgets 7.4.2
Jinja2 2.10
jsonschema 2.6.0
jupyter 1.0.0
jupyter-client 5.2.4
jupyter-console 5.2.0
jupyter-core 4.4.0
jupyterlab 0.33.12
jupyterlab-launcher 0.11.2
kiwisolver 1.0.1
MarkupSafe 1.1.0
matplotlib 1.4.3
MMTK 2.7.9
nbconvert 5.4.0
nbformat 4.4.0
nodejs 0.1.1
nose 1.3.7
notebook 5.7.4
npm 0.1.1
numpy 1.8.2
pandas 0.18.0
pip 18.1
py3Dmol 0.8.0
ScientificPython 2.8.1
scikit-learn 0.20.0
scipy 0.16.1
seaborn 0.7.1
widgetsnbextension 3.4.2
