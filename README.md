# Computational Workflows to Measure the Open Science Practices in the Digital Humanities Domain

This repository contains the workflow and the software used in the paper entitled "Are Digital Humanities really committed to open? An exploratory study on the availability of methodological workflows and open peer review practices", accepted at the [AIUCD Conference 2026](https://www.aiucd2026.unica.it/). The aim of this work is to answer to two specific research questions (RQ1 and RQ2), i.e.:

1. How many publications which describe some data contain an explicit reference to external documentation detailing the process used to create and maintain such data, such as a DMP and/or a detailed workflow depicting the process of data creation?
2. How many DH venues adopts open peer reviewing practices?

We have run an exploratory study considering specific research venues. In particular:

* To address RQ1, we check if data papers published in [Journal of Open Humanities Data (JOHD)](https://openhumanitiesdata.metajnl.com/) include references or mentions to external material appropriately dedicated to either describing the management of the data a paper describes, such as a Data Management Plan (DMP), or detailing precisely the workflow used to produce these data, e.g. published as a particular workflow document or as a computational notebook;

* To address RQ2, we identify the practice of reviewing processes established in some DH venues, including conferences and journals, tracking how many venues adopt open peer review processes instead of the classic ones that prescribe either the sole anonymity of reviewers (single-blind from now on) or the anonymity of both authors and reviewers (double-blind from now on).

For gathering and analysing the data to answer these two RQs, we have developed two distinct workflow described in Jupyter Notebooks that details the automatic and manual steps to run to obtain the data for the analysis and the final graphs detailing specific aspects of the considered DH venues. The Jupyer Notebooks contain appropriate code and natural language documentation to understand the rationale of the workflow and to execute it. In particular:

* [johd.ipynb](blob/main/johd.ipynb) is the workflow for RQ1;
* [dhvenues.ipynb](blob/main/dhvenues.ipynb) is the workflow for RQ2.

The data produced by executing these workflows are available at the following document:

Peroni, S. (2026). Full-text data papers from JOHD and call for papers from DH venues (Version 1.0.0) [Dataset]. Zenodo. https://doi.org/10.5281/zenodo.19758167

For any question or doubt, do not hesitate to contact the author at `silvio` _{dot}_ `peroni` _{at}_ `unibo` _{dot}_ `it`.