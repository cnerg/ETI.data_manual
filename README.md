# ETI Thrust Area 1: Data Access and Collaboration

***

![ETI logo](https://eti.gatech.edu/wp-content/uploads/sites/1003/2019/03/ETI-full_black-768x293.png)

## Introduction

The purpose of this manual is to provide members, particularly those from
university institutions, of the [Consortium for Enabling Technologies and
Innovation (ETI)](https://eti.gatech.edu) details for access to NA-22
relevant data from national laboratories.
Data that has been gathered with potential interest to ETI collaborators is
introduced, and instructions for accessing that data are provided.
Hopefully this will serve as a catalyst for university members, like graduate
students and their PIs, to partner with ventures at national labs that can
benefit from academic research.

This manual has been categorized in two ways. For those interested in specific
ventures or projects, the table of contents below directs to each respective
project page. In some instances, a user might be interested in a specific form
of data (imaging, audio, E&M readings, etc.) but might not be sure which venture
or project best fits those needs. To facilitate this search, a table has been
organized below that attempts to match certain forms of data with each project.
Note that this table is not exhaustive. In the event that a user finds a data
type that is not listed but should be, please create an issue or pull request
on the manual's GitHub page. To explore something in the table, each
cell forwards to a brief description of that data type and information on the
venture or project.

## Table of Contents

1. [Data Streams](#data-tools)
2. [Misc. Data Sources](#miscellaneous-data-sources)
3. [Data Modes](#data-modes)
4. [Data Tools](#data-tools)

## Data Modes

|                                                 |audo           |biota          |EM             |imaging        |infrasound     |radiation      |seismo-acoustic|video          |
|:-----------------------------------------------:|:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|
|[MINOS](#minos)                                  |               |       x       |       x       |       x       |       x       |       x       |       x       |               |
|[WAGGLE](#waggle)                                |       x       |               |       x       |       x       |               |               |       x       |       x       |
|[MUSE](#modeling-urban-scenarios-and-experiments)|               |               |               |               |               |       x       |               |               |
|[Topcoder](#topcoder-data-science-competition)   |               |               |               |               |               |       x       |               |               |
|[VAST](#vast-challenge-2020)                     |               |               |               |               |               |               |               |               |
|[FMotW](#functional-map-of-the-world)            |               |               |               |       x       |               |               |               |               |
|[xView](#xview-detection-challenge)              |               |               |               |       x       |               |               |               |               |
|[SpaceNet](#spacenet)                            |               |               |               |       x       |               |               |               |               |
|[COWC](#cars-overhead-with-context)              |               |               |               |       x       |               |               |               |               |

### [MINOS](MINOS.md)

Multi-Informatics for Nuclear Operations Scenarios is an NA-22 venture that
collects several data modalities for use in nuclear nonproliferation. These
data streams are centralized for use by the MINOS team and collaborators. Please
see the MINOS page in this manual for more information.

### Waggle

This is an Argonne National Laboratory project that uses a system of nodes dispersed
throughout an urban area to collect various data streams and develop methods for edge
computing and threat detection.

### Modeling Urban Scenarios and Experiments

MUSE is an ORNL nuclear dataset designed to help in nuclear nonproliferation
research aimed at detecting and assessing threats in an urban environment.
DOI: [10.13139/ORNLNCCS/1597414](https://doi.ccs.ornl.gov/ui/doi/74)

### Topcoder Data Science Competition

This dataset was used for a
[topcoder data science competition](https://www.topcoder.com/lp/detect-radiation)
in association with several national laboratories. The aim in using this dataset
was to develop algorithms that identify and characterize nuclear threats in urban
areas. The datasets and an explanation of the competition can be found
[here](https://www.topcoder.com/challenges/30085346).

### VAST Challenge 2020

[The VAST Challenge](https://vast-challenge.github.io/2020/) is an annual
competition utilizing data visualization and analytics. While the aim of the
competition may be driven by data visualization, the datasets provided can be
scientifically valuable as an alternative open data source.

### Functional Map of the World

fMoW was an IARPA challenge to develop classification algorithms for imagery
data. The data is still available in TIFF and JPEG formats
[here](https://github.com/fMoW/dataset). The challenge
[website](https://www.iarpa.gov/challenges/fmow.html) provides some context on
goals and additional resources for using imagery data. A paper describing the dataset
in detail can be found on [arXiv](https://arxiv.org/abs/1711.07846).

### xView Detection Challenge

This is a publicly available dataset of satellite imagery provided by the Defense
Innovation Unit Experimental (DIUx) and the National Geospatial-Intelligence Agency
(NGA). [XView](http://xviewdataset.org/) builds on the work of other imagery challenges
in developing classification and detection algorithms. A pre-trained model is already
provided using TensorFlow and PyTorch.

### SpaceNet

[SpaceNet](https://spacenetchallenge.github.io/) is a commercial satellite imagery
dataset with existing labels for developing machine learning classification algorithms.
The dataset is publicly available on [AWS](https://registry.opendata.aws/spacenet/).

### Cars Overhead with Context

[COWC](https://gdo152.llnl.gov/cowc/) is a training dataset with value to machine learning
and deep neural networks for classification and detection of cars in overhead imagery. A paper
describing the dataset can be found
[here](https://gdo152.llnl.gov/cowc/mundhenk_et_al_eccv_2016.pdf).

***

## Miscellaneous Data Sources

Several other organizations maintain databases of varying public availability. The
Incorporated Research Institutions for Seismology
([IRIS](http://ds.iris.edu/ds/nodes/dmc/data/)) provides several raw datasets in
different formats (time series, event, etc.). The U.S. Energy Information Administration
([EIA](https://www.eia.gov/opendata/)) compiles significant amounts of data on economics
and energy generation both nationally and internationally.
[OpenEI](https://openei.org/datasets/dataset) collects data pertaining to different
energy generation methods. They also maintain a Geothermal Data Repository
([GDR](https://gdr.openei.org/submissions/all)) with data collected across the United
States. Finally, [data.gov](https://catalog.data.gov/dataset) provides environmental
datasets divided by the level of constituency (city, county, state, federal, etc.).

***

## Data Tools

Several advanced computing software packages have been developed that may be useful to
ETI research efforts. These machine learning packages are written for use with Python 3:

1. "[Shadow](https://shadow-ssml.readthedocs.io/en/latest/) is a PyTorch based library
for semi-supervised machine learning." It contains several training algorithms and can
be installed via `pip`. Online documentation includes several examples of using the
package and API information.

2. "[MIMOSAS](https://github.com/nonproliferation/mimosas) (Multimodal Input Model Output
Security Analysis Suite) is a supervised machine learning pipeline developed for
classification of multimodal data to inform nuclear security and proliferation detection
scenarios." It has a modular framework with the ability to pre-process data as well as train
and test models. MIMOSAS is compatible with [MINOS](MINOS.md) data and can be installed from
source. Additional information can be found [here](https://complexity.berkeley.edu/mimosas/).
