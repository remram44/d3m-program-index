# Data-driven discovery of models (D3M) program index

A list of D3M-related tools and their repository URLs

## Pipeline infrastructure and tools

[d3m core package](https://gitlab.com/datadrivendiscovery/d3m)

[TA3-TA2 API](https://gitlab.com/datadrivendiscovery/ta3ta2-api)

[simple-TA3](https://gitlab.com/datadrivendiscovery/simple-ta3)

[D3M dashboard](https://gitlab.datadrivendiscovery.org/d3m/dashboard)

## TA1 Components

[BYU Primitives](https://github.com/byu-dml/d3m-primitives) (MIT 131bbaa)

BYU-DML machine learning algorithms or primitives created for DARPA's D3M project. These primitives are wrapped to fit within the D3M ecosystem.

[Common Primitives](https://gitlab.com/datadrivendiscovery/common-primitives/)

A collection of primitives and pipelines from multiple teams.

[Cornell Primitives](https://github.com/cyangcornell/d3m-primitives)

A collection of Cornell primitives with executable examples.

[Distil (New Knowledge/Uncharted TA1)](https://github.com/NewKnowledge?utf8=%E2%9C%93&q=d3m-wrapper&type=public&language=) (MIT)

A collection of TA1 d3m-wrappers around [New Knowledge](https://github.com/NewKnowledge/) base libraries for  the D3M program.

[JHU Primitives](https://github.com/neurodata/primitives-interfaces) (Apache db6cc0d)

A collection of JHU Python interfaces for TA1 primitives in the D3M project.

[RPI Primitives](https://github.com/zijun-rpi/d3m-primitives)

RPI primitives for D3M project. Executable pipelines are included.

[ICSI Primitives](https://github.com/ICSI-RealML/realML) (GPL??? a0509b6)

ICSI kernel learning and matrix primitives for the D3M project. 

[ISI Data Cleaning Primitives](https://github.com/usc-isi-i2/dsbox-cleaning), [ISI Featurization Primitives](https://github.com/usc-isi-i2/dsbox-featurizer) (MIT 3cb5146)

A collection of ISI primitives for data cleaning and featurization.

[BBN Primitives](https://gitlab.datadrivendiscovery.org/BBN/d3m-bbn-primitives/tree/d3m.api2019.1.21.a)

BBN primitives and pipelines for D3M project. 

[CMU Find Projections Primitives](https://github.com/autonlab/find_projections), [CMU Fastlvm Primitives](https://github.com/autonlab/fastlvm) (Apache cb881c0 and GPL 742ae84)

A collection of CMU primitives for D3M project.

[Perspecta Labs Primitives](https://gitlab.datadrivendiscovery.org/plin/lupi_primitive/tree/v3.0.0)

Perspecta Labs primitives and pipelines for D3M project.

[MIT Primitives](https://github.com/Featuretools/ta1-primitives)

Wrapper around the [Featuretools](https://github.com/featuretools/featuretools/) library for automated feature engineering for D3M project.

[SRI Primitives backend](https://github.com/linqs/psl) (Apache 19720e0)

Developed and maintained by UCSC. Here is a website with more details: PSL (https://psl.linqs.org)

[Michigan Primitives](https://github.com/dvdmjohnson/d3m_michigan_primitives) (MIT c7d2bd1)

A collection of University of Michigan primitives, with executable pipelines for many.

## TA2 Systems

[ISI DSBox System](https://github.com/usc-isi-i2/dsbox-ta2) (MIT 11ae3bc)

ISI's template-based automated machine learning system.

[SRI TPOT System](https://github.com/daraghhartnett/tpot) (GPL 696ba7e)

SRI's fork of the TPOT system which has been made compliant with D3M primitives.

[TAMU System](https://gitlab.com/TAMU_D3M/Winter_2018_tamuta2) (404!!!)

TAMU's automated machine learning system.

[UC Berkeley Aika](https://gitlab.com/aika/aika) (empty!!!)

A framework to enable reproducible AutoML research. (TBD)

[CMU TA2 System](https://github.com/saswatiray/cmu-ta2) (Apache 667bfa5)

CMU's TA2 system for DARPA D3M program

[Brown/MIT TA2 System](https://gitlab.datadrivendiscovery.org/zshang/alpine-meadow) (empty!!!)

Alpine Meadow: Brown/MIT TA2 System (TBU)

[AlphaAutoML](https://gitlab.com/ViDA-NYU/alphaautoml), [TA2](https://gitlab.com/ViDA-NYU/d3m/ta2) (BSD-3)

NYU's AlphaAutoML and TA2 Systems

[Stanford TA2 System](https://github.com/HazyResearch/d3m-model-search) (404!!!)

Stanford TA2 system for DARPA D3M Program

## TA3 Systems

[Tufts Snowcat](https://gitlab.datadrivendiscovery.org/cliu/tufts-ta3-winter-19-demo) (MIT??? 9d95471)

Source code of branch "winter-19-demo"

[Brown/MIT TA3 System](https://gitlab.datadrivendiscovery.org/ezgraggen/vizdom) (empty!!!)

Vizdom: Brown/MIT TA3 System (TBU)

[NYU's TA3 System](https://gitlab.com/ViDA-NYU/d3m/ta3) (BSD-3)

NYU's TA3 system written in TypeScript, using Express and React.

[Uncharted Distil](https://github.com/uncharted-distil) (Apache 2b65978)

Uncharted's Mixed-Initiative Model Discovery System for Subject Matter Experts.

[Purdue ModSquad](https://github.com/d3m-purdue) (Apache??? a10c69a)

Purdue's Model Evaluation User Interface

## DataMart

DataMarts are data search engines. Given a problem and an dataset, those system can provide additional, relevant data and augment the initial dataset to enable the construction of a better model.

### NYU's DataMart system

* [Publicly-accessible address](https://datamart.d3m.vida-nyu.org/)
* [Source code](https://gitlab.com/ViDA-NYU/datamart/datamart) (BSD-3)
* [Data augmentation examples](https://gitlab.com/ViDA-NYU/datamart/datamart/tree/master/examples) through the API
* Python packages: [datamart](https://pypi.org/project/datamart/), [datamart-materialize](https://pypi.org/project/datamart-materialize/), [datamart-augmentation](https://pypi.org/project/datamart-augmentation/)

### USC ISI's DataMart system

* [Source code](https://github.com/usc-isi-i2/datamart/tree/development) (MIT b7995b3)
* [College Debt example](https://github.com/usc-isi-i2/datamart/blob/development/example/college_example/college_example.ipynb)
* [FIFA Man of the Match example](https://github.com/usc-isi-i2/datamart/blob/development/example/fifa_example/fifa_example.ipynb)
* [REST example](https://github.com/usc-isi-i2/datamart/blob/development/example/rest_example/example.md)
