# Bioinformatics: wealth of African countries

## Overview

- Bioinformatics tools used for research
- Challenges of the different bioinformatics tools in Africa
- Challenges of research in Africa e.g. funding, infrastructure, electricity and equipment
- Bioinformatics in Africa and initiatives to promote it e..g H3BioNet, H3Africa, ASBCB, EANBiT, NBGN

## Questions and hypothesis 
**Search term**: "Country" AND (Bioinformatics OR "Computational Genomics" OR "Computational Biology")

"Country" AND ("Bioinformatics" OR "Computational Genomics" OR "Computational Biology" OR "Genomic Sequencing" OR "Proteomics" OR "Metagenomics" OR "Trascriptomics" OR "Phylogenetics" OR "Genetic Analysis" OR "Molecular Modeling")


- Check the number of publications using bioinformatics tools in different African countries for scientific research
- Are they primary or review papers 
- Was the research conducted locally 
- In the primary papers, were the tools sourced locally? Or from abroad?
- In the primary papers, is there local institutional collaboration?
- What was done in the collaborating country
- How many of these articles focus on bioinformatics?
- How are data generated from bioinformatics research managed and shared?
- Are there issues with internet connectivity or access to computational resources?
- What disease or local problems was addressed ?.
- What area of bioinformatics that is commonly used in addressing problems e.g. RNA-Seq, Chip-Seq, WGS, GWAS, scRNA-Seq etc
- Countries that published in Africa according to region e.g. West, East, North and Southern Africa 
- Institutions with the top bioinformatics publication 
- Bioinformatics Labs and infrastructure across Africa
- Affiliation or funding: Local or International 


### Methods

An excel workbooks containing all African countries were used for literature mining and carrying out the analysis. The workbook contains the following sheets:
1) Search strategy (where the search terms can be located, use it to mine literature and fill the spaces provided)
2) Country_All (This should have the country name and all the articles downloaded from PubMed)
3) Country_Analysed (This should have countries name and only the articles that passed the criteria and which was analysed) 
4) Coded (Contains the definition of terms and how article was score for each questions that was asked). 

PubMed was searched for articles pertaining to bioinformatics or computional biology using the **Search term**: "Country" AND (Bioinformatics OR "Computational Genomics" OR "Computational Biology"). Full text and additional metadata were retrieved from the PubMed Central (PMC) database for the open access subset of articles.


#### Flow diagram

## Analysis  
Bibliometrics or network analysis, to quantitatively analyze research patterns, collaborations, and impact.


## Discussion
Challenges for using bioinformatics in research in Africa 
- Labs
- Bioinformatics skills 
- Collaboration
- Funding
- Future

## Recommendation

  - Policy interventions and 
  - Resource allocation in the field of bioinformatics in Africa.


### Reference



### Reproducing

Prerequisites:

- Ubuntu: 20.04 (x64)
- Python: 3.8.3
- R: 3.6.3

Install the minimal requirements for reproduction and download required data:

```bash
pip install -r setup/requirements.txt
Rscript helpers/restore.R
cd data
./download.sh
```
