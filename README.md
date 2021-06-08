# Inventory report on the possibility to update the ESAS database for the North Sea

## Introduction 

This repository was set up in the context of the "Inventory report on revitalizing the ESAS-database for the North Sea" project initiated by Rijkswaterstaat. The goal of the project was:

- to create an inventory report on existing _seabird at sea_ datasets collected in the North Sea for future inclusion in the ESAS database
- to draw a data sharing agreement among data suppliers
- to support the migration of the ESAS database from JNCC to ICES Data Centre and updating the outdated ESAS v5 dataset with Belgian, Dutch and German data.

In July 2020, a questionnaire was officially distributed among various potential data providers of seabird at sea data, which consist of the Joint ICES/OSPAR/HELCOM Working Group on Birds (JWGBIRD) consortium members, supplemented by additional researchers and institutes proposed by INBO, Bureau Waardenburg (BUWA), Forschungs- und Technologiezentrum Westküste (FTZ) and Rijkswaterstaat (RWS), including potential data providers for the North Sea, Baltic Sea and Irish Sea. The goal of this questionnaire was to create an inventory of resources of seabird at sea data in Europe.

## Content

This repository includes:

- a [pdf version of the questionnaire](https://github.com/inbo/esas-revitalize/blob/master/references/questionnaire.pdf)
- the [raw dataset](https://github.com/inbo/esas-revitalize/blob/master/data/raw/input_data_without_email.csv) with the questionnaire answers
- the [Rmarkdown code](https://github.com/inbo/esas-revitalize/tree/master/src) needed to clean the raw data and to generate statistics and tables
- the [cleaned dataset](https://github.com/inbo/esas-revitalize/blob/master/data/processed/cleaned_data.csv) and [generated tables and figures](https://github.com/inbo/esas-revitalize/blob/master/data/processed) for the inventory report

## Repo structure 

The repository structure is based on [Cookiecutter Data Science](http://drivendata.github.io/cookiecutter-data-science/). 

```
├── README.md             : Description of this repository
├── LICENSE               : Repository license
├── esas-revitalize.Rproj : RStudio project file
├── .gitignore            : Files and directories to be ignored by git
│
├── data
│   ├── raw               : Source data, input for Rmarkdown script
│   └── processed         : Cleaned data, tables and figure
|
├── references            : pdf version of questionnaire
│
└── src                   : Rmarkdown scripts to clean data and generate tables/figure
```
