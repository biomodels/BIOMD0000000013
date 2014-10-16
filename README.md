# BIOMD0000000013: untitled

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000013.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000013.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000013 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
**Applications of metabolic modelling to plant metabolism.**   
Poolman MG ,Assmus HE, Fell DA _J. Exp. Bot._ [2004 May; Volume: 55 (Issue:
400 )]: 1177-86 [15073223](http://www.ncbi.nlm.nih.gov/pubmed/15073223) ,  
**Abstract:**   
In this paper some of the general concepts underpinning the computer modelling
of metabolic systems are introduced. The difference between kinetic and
structural modelling is emphasized, and the more important techniques from
both, along with the physiological implications, are described. These
approaches are then illustrated by descriptions of other work, in which they
have been applied to models of the Calvin cycle, sucrose metabolism in sugar
cane, and starch metabolism in potatoes.

  
  

This model describes the non oxidative Calvin cycle as depicted in Poolman et
al; J Exp Bot (2004) 55:1177-1186, fig 2. Reaction E20: E4P + F6P ↔ S7P + GAP,
is depicted in the figure, but not included in the model. The light reaction:
ADP + P i → ATP, is included in the model, but only mentioned in the figure
caption. The parameters and initial concentrations are the same as in Poolman,
1999, Computer Modelling Applied to the Calvin Cycle, PhD Thesis, Oxford
Brookes University, Appendix A (available at at
<http://mudshark.brookes.ac.uk/index.php/Publications/Theses/Mark> )

© Mark Poolman (mgpoolman@brookes.ac.uk) 1995-2002  
Based on a description by Pettersson 1988, Eur. J. Biochem. 175, 661-672  
Differences are:  
1 - Reactions assumed by Pettersson to be in equilibrium have fast mass action
kinetics.  
2 - Introduction of the parameter PGAxpMult to modulate PGA export through
TPT.  
3 - Introduction of Starch phosphorylase reaction.  
This file may be freely copied or translated into other formats provided:  
1 - This notice is reproduced in its entirety  
2 - Published material making use of (information gained from) this model
cites at least:  
(a) Poolman, 1999, Computer Modelling Applied to the Calvin Cycle, PhD Thesis,
Oxford Brookes University  
(b) Poolman, Fell, and Thomas. 2000, Modelling Photosynthesis and its control,
J. Exp. Bot. 51, 319-328  
or  
(c) Poolman et al. 2001, Computer modelling and experimental evidence for two
steady states in the photosynthetic Calvin cycle. Eur. J. Biochem. 268,
2810-2816  
Further related information may be found at <http://mudshark.brookes.ac.uk> .

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2012 The BioModels.net Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html) .  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


