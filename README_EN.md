
![](input/logo_en.png){ width=35% }

CENTER OF DIAGNOSTICS AND TELEMEDICINE

# MosMedData XR with signs of the chest organs pathologies type II 

*** 


# About Dataset

> This dataset contains the results of X-ray of the chest with chest organs pathologies signs, as well as without signs (norm). 
The research data were collected in the radiology departments of medical institutions in 
Moscow in the period from 06.05.2022 to 27.05.2022.

# Disclaimer

> This dataset is intended to be used as:
>
> - educational material for medical imaging specialists showing intrinsic radiological signs of chest organs pathologies;
> - a dataset for development, training and testing of AI-based services that;
> - information source for medical specialists and broad audience.
>
> You are free to **share** this dataset, which means you can copy and redistribute the material in any medium or
format, **under the following terms**:
>
> - you must give approproate credit, such as:
>   - authors;
>   - their affiliations;
>   - copyright;
> - permanent link to the dataset.
> - you must share a licence or provide a link to it.
>
You **must not**:
>
> - use this dataset for commercial purposes;
> - distribute the modified material if you remix, transform, or build upon the dataset;
> - apply legal terms or technological measures that legally restrict others from doing anything the license
permits.

![](input/cc.png){ width=25% }

# General Information

***

## Dataset Title

MosMedData XR with signs of the chest organs pathologies type II  

## Internal Code

CHESTPAT

## Annotation Class

2-C

## Keywords

X-ray, XR, chest, cancer, neoplasm, tuberculosis, trauma, pneumonia

## Language

English, Russian

## Funding Sources

Internal funding

## Dataset Version

1.1

## Permanent link

[https://mosmed.ai/datasets/mosmeddata-rg-s-priznakami-patologij-ogk-tip-ii/](https://mosmed.ai/datasets/mosmeddata-rg-s-priznakami-patologij-ogk-tip-ii/)

## Release Date

27.07.2022

# Affiliation and Contributors

## Contributors

>  
- Shulkin I. [1] 
- Ahmetov R. [1] 
- Vladzymyrskyy A. [1] 
- Novik V. [1] 
- Chetverikov S. [1] 
- Bobrovskaya T. [1] 
- Semenov S. [1] 
- Arzamasov K. [1] 
- Kokina D. [1] 
- Kirpichev Yu. [1] 
- Ulyanov I. [1] 
- Filatov M. [1] 
- Popov A. [1] 


## Affiliation

> [1] Research and Practical Clinical Center for Diagnostics and Telemedicine Technologies of the Moscow Health Care Department.

# Data Structure

```
.
|-- dataset_registry.xlsx
|-- README_EN.md
|-- README_RU.md
|-- README_EN.pdf
|-- README_RU.pdf
`-- studies
    |--studyUID_X
   |    |-- seriesUID_X
   |    |    |-- UID_X.dcm
   |    |    |-- UID_X.dcm
   |    |    `-- ...
   |    |
   |    `-- seriesUID_X
   |        |-- UID_X.dcm
   |        |-- UID_X.dcm
   |        `-- ...
   |--studyUID_X
   |    |-- seriesUID_X
   |    |    |-- UID_X.dcm
   |    |    |-- UID_X.dcm
   |    |    `-- ...
   |    |
   |    `-- seriesUID_X
   |        |-- UID_X.dcm
   |        |-- UID_X.dcm
   |        `-- ...
   `--...


```

> - README_EN.md and README_RU.md contain general information about the dataset; they have been saved in Markdown format in English and Russian languages, respectively. README_EN.pdf and README_RU.pdf contain the same information but have been saved in PDF format for the ease of convenience. 
> - dataset_registry.xlsx contains a list of studies included in the dataset, the path to the corresponding file.
> - The studies directory contains studyUID-X directories, each of which contains studies in DICOM format.

# Data Overview

| Property      | Value |
| ---------------- | --- |
| Number of studies, pcs.     | 179       |
| Number of patients, ppl.   | 179        |
| Distribution by sex,ppl (M/ F)   | 87/ 92        |
| Distribution by age, years (min./ median/ max.)   | 18/ 60/ 94        |
| Number of studies in each category, psc. (With pathology/ Without pathology)    | 91/ 88        |

# Sharing and Access Information

## License

> Copyright © 2020 Research and Practical Clinical Center for Diagnostics and Telemedicine 
Technologies of the Moscow Health Care Department. This dataset is licensed under a 
Creative Commons Attribution-NonCommercial-NoDerivs 3.0 Unported (CC BY-NC-ND 3.0) License. 
See LICENSE file or follow the [link](https://creativecommons.org/licenses/by-nc-nd/3.0/) for more information.

## Citation

> Recommended citation:
>
> Datasets of Research and Practical Clinical Center for Diagnostics and Telemedicine Technologies
of the Moscow Health [Electronic resource]. – 2022. – URL: https://mosmed.ai/datasets/mosmeddata-rg-s-priznakami-patologij-ogk-tip-ii/

## Distribution

> This dataset should not be distributed without proper attribution:
>
> - authors;
> - their affiliations;
> - copyright;
> - permanent link to the dataset;
> - license file or link to the license text.



