# BIOMD0000000439: MODEL1212040001

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000439.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000439.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000439 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


Smith2009 - RGS mediated GTP hydrolysis

This model is described in the article:

[Dual positive and negative regulation of GPCR signaling by GTP
hydrolysis.](http://identifiers.org/pubmed/19285552)

Smith B, Hill C, Godfrey EL, Rand D, van den Berg H, Thornton S, Hodgkin M,
Davey J, Ladds G.

Cell Signal. 2009 Jul;21(7):1151-60.

Abstract:

G protein-coupled receptors (GPCRs) regulate a variety of intracellular
pathways through their ability to promote the binding of GTP to heterotrimeric
G proteins. Regulator of G protein signaling (RGS) proteins increases the
intrinsic GTPase activity of Galpha-subunits and are widely regarded as
negative regulators of G protein signaling. Using yeast we demonstrate that
GTP hydrolysis is not only required for desensitization, but is essential for
achieving a high maximal (saturated level) response. Thus RGS-mediated GTP
hydrolysis acts as both a negative (low stimulation) and positive (high
stimulation) regulator of signaling. To account for this we generated a new
kinetic model of the G protein cycle where Galpha(GTP) enters an inactive GTP-
bound state following effector activation. Furthermore, in vivo and in silico
experimentation demonstrates that maximum signaling output first increases and
then decreases with RGS concentration. This unimodal, non-monotone dependence
on RGS concentration is novel. Analysis of the kinetic model has revealed a
dynamic network motif that shows precisely how inclusion of the inactive GTP-
bound state for the Galpha produces this unimodal relationship.

To reproduce dose-response plots in the publication, the model is simulated
with 12 different concentrations (see parameter Ligand_conc). For each
concentration, a single value must be obtained from the integral of the
trajectory of species z3 from time=0 to time=30. These values are then used to
build a dose-response plot (authors used GraphPad Prism). Mutant strains are
simulated with alternative parameter values or initial conditions in Table S3.

This model is hosted on [BioModels Database](http://www.ebi.ac.uk/biomodels)
and identified by:
[MODEL1212040001](http://www.ebi.ac.uk/biomodels/MODEL1212040001) .

To cite BioModels Database, please use: BioModels Database: An enhanced,
curated and annotated resource for published quantitative kinetic models.
PMID: [20587024](http://identifiers.org/pubmed/20587024) .

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.


