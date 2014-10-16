# MODEL4992089662: banaji

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL4992089662.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL4992089662.git@20140916`

## Usage

Importing the model package.

`import MODEL4992089662 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This is a part of the model described in:  
**A physiological model of cerebral blood flow control**   
Murad Banaji, Ilias Tachtsidis, David Delpy, Stephen Baigent, _Mathematical
biosciences_ 2005 194:125-173; PMID:
[15854674](http://www.ncbi.nlm.nih.gov/pubmed/15854674) , doi:
[10.1016/j.mbs.2004.10.005](http://dx.doi.org/10.1016/j.mbs.2004.10.005)  
Abstract:  
The construction of a computational model of the human brain circulation is
described. We combine an existing model of the biophysics of the circulatory
system, a basic model of brain metabolic biochemistry, and a model of the
functioning of vascular smooth muscle (VSM) into a single model. This
represents a first attempt to understand how the numerous different feedback
pathways by which cerebral blood flow is controlled interact with each other.
The present work comprises the following: Descriptions of the physiology
underlying the model; general comments on the processes by which this
physiology is translated into mathematics; comments on parameter setting; and
some simulation results. The simulations presented are preliminary, but show
qualitative agreement between model behaviour and experimental results.

The model represents the intracellular component of the model, and is
translated from the implementation available with the
[braincirc](http://braincirc.sourceforge.net/) package.

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
or not. .  
  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


