# BIOMD0000000204: MODEL7957942740

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000204.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000204.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000204 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


Chickarmane2006 - Stem cell switch irreversible

Kinetic modeling approach of the transcriptional dynamics of the embryonic
stem cell switch.

This model is described in the article:

[Transcriptional dynamics of the embryonic stem cell
switch.](http://identifiers.org/pubmed/16978048)

Chickarmane V, Troein C, Nuber UA, Sauro HM, Peterson C

PLoS Computational Biology. 2006; 2(9):e123

Abstract:

Recent ChIP experiments of human and mouse embryonic stem cells have
elucidated the architecture of the transcriptional regulatory circuitry
responsible for cell determination, which involves the transcription factors
OCT4, SOX2, and NANOG. In addition to regulating each other through feedback
loops, these genes also regulate downstream target genes involved in the
maintenance and differentiation of embryonic stem cells. A search for the
OCT4-SOX2-NANOG network motif in other species reveals that it is unique to
mammals. With a kinetic modeling approach, we ascribe function to the observed
OCT4-SOX2-NANOG network by making plausible assumptions about the interactions
between the transcription factors at the gene promoter binding sites and RNA
polymerase (RNAP), at each of the three genes as well as at the target genes.
We identify a bistable switch in the network, which arises due to several
positive feedback loops, and is switched on/off by input environmental
signals. The switch stabilizes the expression levels of the three genes, and
through their regulatory roles on the downstream target genes, leads to a
binary decision: when OCT4, SOX2, and NANOG are expressed and the switch is
on, the self-renewal genes are on and the differentiation genes are off. The
opposite holds when the switch is off. The model is extremely robust to
parameter changes. In addition to providing a self-consistent picture of the
transcriptional circuit, the model generates several predictions. Increasing
the binding strength of NANOG to OCT4 and SOX2, or increasing its basal
transcriptional rate, leads to an irreversible bistable switch: the switch
remains on even when the activating signal is removed. Hence, the stem cell
can be manipulated to be self-renewing without the requirement of input
signals. We also suggest tests that could discriminate between a variety of
feedforward regulation architectures of the target genes by OCT4, SOX2, and
NANOG.

This model is hosted on [BioModels Database](http://www.ebi.ac.uk/biomodels/)
and identified by:
[MODEL7957942740](http://identifiers.org/biomodels.db/MODEL7957942740) .

To cite BioModels Database, please use: [BioModels Database: An enhanced,
curated and annotated resource for published quantitative kinetic
models](http://identifiers.org/pubmed/20587024) .

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.


