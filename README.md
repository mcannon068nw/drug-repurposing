# drug-repurposing

### About
At the AGBT precision medicine conference, there was a great focus on the economic wall that drug development efforts have to overcome. Drug development is hard and a very large amount of drugs fail to pass the preclinical stage due to the sheer amount of work and funding required. This is especially brutal for rare diseases that, by the nature of being rare, almost never have the economic backing to fuel new therapeutics. From a commercial point of view, these diseases have a bleak economic prospect even with the Orphan Drug act. To combat this, drug repurposing has become a strategy that takes old drugs and looks at available data, or runs new experiments to provide data to justify an already existing drug for a new indication. This strategy has the potential to save millions in funding and years of development time, which is good for rare diseases (but all diseases too).

With the DGIdb version 5 update coming out and the focus of DGIdb to support both clinical applications *and* drug development pipelines, it is the perfect opportunity to support new types of data (disease associations, phenotypes) and generate new insights that can help drive research/drug development for rare diseases and drug pipelines.

### Goal
Identy an approach to use DGIdb to link aggregate interaction data with diseases/phenotypes (including rare diseases). Additionally, find a way to link drug data with repurposing status, such as through membership in a drug repurposing library or through assay data. Linking these data types would allow an additional 'annotation' type that people could use in the research, clinical, and development setting. Summarized, the potential workflow here is:

- Link disease/phenotype associations with genes
- Link repurposing associations with drugs
- Make diseases and indications a sortable/searchable field
- Formalize already existing interaction attributes that cover related data points (i.e. sensitivity, responses, novel drug status)
- New feature to find intersections of diseases/drugs gotten from a gene search

Related methodology:
- Identify new sources
- Potentially use NLP to pull in this information from assays/labels
- Disease normalizer

### New Data Sets
Drug Repurposing Hub: https://clue.io/repurposing#download-data   
ReDO_Trials Database: https://www.anticancerfund.org/en/redo-trials-db  
repoDB: http://apps.chiragjpgroup.org/repoDB/  


### Additional Thoughts
This feels like a good direction for 'refreshing' and 'formalizing' the data already present with interaction attributes while bringing new data and functionality to the resource. Many people don't know that we already have this type of information. Additionally, this could be a good tie in for NLP methods to extract phenotypes from adverse effects / reactions / side effects sections within FDA labels. This has clinical applicability but also this is literally how some drugs are repurposed: a side effect is observed and found to be useful in other contexts. Perhaps a new feature to find cross-sections.


### TO DO
- [ ] Mock up of new feature
- [ ] Mock up of intended formalized field types (from interaction attributes)
- [ ] Mock up of disease representation
