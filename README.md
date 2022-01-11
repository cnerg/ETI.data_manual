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
cell forwards to information on the venture or project.

Contribution to this document is encouraged as data streams are identified.
The process of adding content is detailed in the [contributing page](CONTRIBUTING.md).

## Table of Contents

1. [Data Streams](#data-streams)
2. [Misc. Data Sources](#miscellaneous-data-sources)
3. [Data Modes](#data-modes)
4. [Data Tools](#data-tools)

## Data Streams
|     |[audio](#data-modes)|[biota](#data-modes)|[EM](#data-modes)|[imaging](#data-modes)|[infrasound](#data-modes)|[radiation](#data-modes)|[seismo-acoustic](#data-modes)|[video](#data-modes)|[hyperspectral](#data-modes)|
|:---:|:-----------------:|:------------------:|:---------------:|:--------------------:|:-----------------------:|:----------------------:|:----------------------------:|:------------------:|:---------------:|
|[MINOS](#minos)                                  |               |       x       |       x       |       x       |       x       |       x       |       x       |               |               |
|[WAGGLE](#waggle)                                |       x       |               |       x       |       x       |               |               |       x       |       x       |               |
|[MUSE](#modeling-urban-scenarios-and-experiments)|               |               |               |               |               |       x       |               |               |               |
|[Topcoder](#topcoder-data-science-competition)   |               |               |               |               |               |       x       |               |               |               |
|[GRDC/BDC](#gamma-ray-data-cloud-berkeley-nuclear-data-cloud)                |               |               |               |       x       |               |       x       |               |       x       |       x       |
|[VAST](#vast-challenge-2020)                     |               |               |               |               |               |               |               |               |               |
|[FMotW](#functional-map-of-the-world)            |               |               |               |       x       |               |               |               |               |               |
|[xView](#xview-detection-challenge)              |               |               |               |       x       |               |               |               |               |               |
|[SpaceNet](#spacenet)                            |               |               |               |       x       |               |               |               |               |               |
|[COWC](#cars-overhead-with-context)              |               |               |               |       x       |               |               |               |               |               |

### [MINOS](MINOS.md)

Multi-Informatics for Nuclear Operations Scenarios is an NA-22 venture that
collects several data modalities for use in nuclear nonproliferation. These
data streams are centralized for use by the MINOS team and collaborators. Please
see the MINOS page in this manual for more information.

### [Waggle](WAGGLE.md)

This is an Argonne National Laboratory project that uses a system of nodes dispersed
throughout an urban area to collect various data streams and develop methods for edge
computing and threat detection.

### [Modeling Urban Scenarios and Experiments](https://doi.ccs.ornl.gov/ui/doi/74)

MUSE is an ORNL nuclear dataset designed to help in nuclear nonproliferation
research aimed at detecting and assessing threats in an urban environment.
DOI: [10.13139/ORNLNCCS/1597414](https://doi.ccs.ornl.gov/ui/doi/74)

### [Topcoder Data Science Competition](https://www.topcoder.com/lp/detect-radiation)

This dataset was used for a topcoder data science competition in association
with several national laboratories. The aim in using this dataset was to develop
algorithms that identify and characterize nuclear threats in urban areas.
The datasets and an explanation of the competition can be found
[here](https://www.topcoder.com/challenges/30085346).

### [Gamma-ray Data Cloud](https://grdc.nersc.gov) /[Berkeley nuclear Data Cloud](https://bdc.lbl.gov)

GRDC and BDC are LBNL-hosted websites developed to enable access to radiological data and associated contextual data.  
GRDC primarily hosts the RadMAP dataset.  RadMAP was a truck-borne detector system carrying NaI, HPGe and Liquid Scintillator radiation detectors, LiDAR, 4pi cameras, hyperspectral camera, a weather station, and a GPS/IMU. [RadMAP Publication here](https://doi.org/10.1016/j.nima.2016.09.040) Some Helicopter-borne NaI data is also available.  [Request GRDC access here](https://docs.google.com/forms/d/1tAyc7ivwPjCkteU5qgu9vyxDcVuXwuYYXiKEWgBzFCU/edit?usp=sharing).

BDC was developed to improve upon the GRDC data management model, with a goal of facilitating users to be able to add their own data.  
BDC is will host similar datasets to RadMAP (and possibly the RadMAP dataset one day), but for now, it continues to be subject to active developement and the first hosted dataset is the Northern Virginia Array (NoVArray), which is a set of 18 months of (up to 18) NaI detectors positioned alongside roadways in the Northern Virginia suburbs of the Washington, DC area.  Users can register for [bdc.lbl.gov] at the website, but manual approval by an administrator is required. 
[NoVArray ArXiv](https://arxiv.org/pdf/2003.10524.pdf)

Both datasets are available to researchers who register on the respective websites.

### [VAST Challenge 2020](https://vast-challenge.github.io/2020/)

The VAST Challenge is an annual
competition utilizing data visualization and analytics. While the aim of the
competition may be driven by data visualization, the datasets provided can be
scientifically valuable as an alternative open data source.

### [Functional Map of the World](https://www.iarpa.gov/challenges/fmow.html)

fMoW was an IARPA challenge to develop classification algorithms for imagery
data. The data is still available in TIFF and JPEG formats
[here](https://github.com/fMoW/dataset). The challenge
website provides some context on
goals and additional resources for using imagery data. A paper describing the dataset
in detail can be found on [arXiv](https://arxiv.org/abs/1711.07846).

### [xView Detection Challenge](http://xviewdataset.org/)

This is a publicly available dataset of satellite imagery provided by the Defense
Innovation Unit Experimental (DIUx) and the National Geospatial-Intelligence Agency
(NGA). XView builds on the work of other imagery challenges
in developing classification and detection algorithms. A pre-trained model is already
provided using TensorFlow and PyTorch.

### [SpaceNet](https://spacenetchallenge.github.io/)

SpaceNet is a commercial satellite imagery
dataset with existing labels for developing machine learning classification algorithms.
The dataset is publicly available on [AWS](https://registry.opendata.aws/spacenet/).

### [Cars Overhead with Context](https://gdo152.llnl.gov/cowc/)

COWC is a training dataset with value to machine learning
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

## Data Modes

This section briefly defines the data modalities described in the [data table](#data-modes):

* **Audio** - Recorded audio data collected at a detector location. This could be collected as a physical data source or as recordings providing clarification and context to other data streams.

* **Biota** - Ecological data describing experimental or detection locations and the wildlife in the surrounding area.

* **EM** - Electromagnetic observations.

* **Imaging** - Visual imaging data (i.e. static pictures). These can be satellite imagery or ground-level pictures from detectors and ground cameras.

* **Infrasound** - Low-frequency sound recordings not normally audible to humans.

* **Radiation** - Data collected from detectors that measure different types of radiation.

* **Seismo-acoustic** - Low-frequency recordings traditionally from geophysical sources. One detector example would be a seismograph.

* **Video** - Recorded video imaging from a detector.

* **Hyperspectral** - Visual and near infrared light imagery, measured in many channels, as opposed to the three-channel RGB visual.


***

## Data Tools

Several advanced computing software packages have been developed that may be useful to
ETI research efforts. These machine learning packages are written for use with Python 3:

1. "[Shadow](https://shadow-ssml.readthedocs.io/en/latest/) is a PyTorch based library
for semi-supervised machine learning." It contains several training algorithms and can
be installed via `pip`. Online documentation includes several examples of using the
package and API information.

1. "[MIMOSAS](https://github.com/nonproliferation/mimosas) (Multimodal Input Model Output
Security Analysis Suite) is a supervised machine learning pipeline developed for
classification of multimodal data to inform nuclear security and proliferation detection
scenarios." It has a modular framework with the ability to pre-process data as well as train
and test models. MIMOSAS is compatible with [MINOS](MINOS.md) data and can be installed from
source. Additional information can be found [here](https://complexity.berkeley.edu/mimosas/).

1. "[Becquerel](https://github.com/lbl-anp/becquerel) is a Python package for analyzing nuclear 
spectroscopic measurements." The core functionalities are reading and writing different spectrum 
file types, fitting spectral features, performing detector calibrations, and interpreting 
measurement results. It includes tools for plotting radiation spectra as well as convenient 
access to tabulated nuclear data, and it will include fits of different spectral features. 
It is intended to be general-purpose enough that it can be useful to anyone from an undergraduate 
taking a laboratory course to the advanced researcher.
