# MODEL1006230065: Aslanidi2009_caninePVJ

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1006230065.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1006230065.git@20140916`

## Usage

Importing the model package.

`import MODEL1006230065 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
**Optimal velocity and safety of discontinuous conduction through the heterogeneous Purkinje-ventricular junction.**   
Aslanidi OV, Stewart P, Boyett MR, Zhang H. _Biophys J_ 2009 Jul 8;97(1):20-39
[19580741](http://www.ncbi.nlm.nih.gov/pubmed/19580741) ,  
**Abstract:**   
Slow and discontinuous wave conduction through nonuniform junctions in cardiac
tissues is generally considered unsafe and proarrythmogenic. However, the
relationships between tissue structure, wave conduction velocity, and safety
at such junctions are unknown. We have developed a structurally and
electrophysiologically detailed model of the canine Purkinje-ventricular
junction (PVJ) and varied its heterogeneity parameters to determine such
relationships. We show that neither very fast nor very slow conduction is
safe, and there exists an optimal velocity that provides the maximum safety
factor for conduction through the junction. The resultant conduction time
delay across the PVJ is a natural consequence of the electrophysiological and
morphological differences between the Purkinje fiber and ventricular tissue.
The delay allows the PVJ to accumulate and pass sufficient charge to excite
the adjacent ventricular tissue, but is not long enough for the source-to-load
mismatch at the junction to be enhanced over time. The observed relationships
between the conduction velocity and safety factor can provide new insights
into optimal conditions for wave propagation through nonuniform junctions
between various cardiac tissues.

This model was taken from the [CellML
repository](http://www.cellml.org/models) and automatically converted to SBML.  
The original model was: [ **Aslanidi OV, Stewart P, Boyett MR, Zhang H. (2009)
- version=1.0**
](http://models.cellml.org/exposure/bb75b3021730966e2827967a66188cb2)  
The original CellML model was created by:  
**Catherine Lloyd**   
c.lloyd@auckland.ac.nz  
The University of Auckland  

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not..  
  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


