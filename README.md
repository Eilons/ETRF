# ETReF: Entity and Term Relevance Feedback Dataset

The annotated dataset, marked entity mentioned from documents and queries, corpus statistics and the initially retrieved document lists used in our paper **Entity-Based Relevance Feedback for Document Retrieval**.

Using crowdsourcing we collected term and entity relevance feedback for ROBUST and ClueWeb datasets. The resultant annotated dataset is the largest reported in the literature for term relevance feedback, and the first for entity relevance feedback, to the best of our knowledge. We published our annotated dataset, corpus entity statistics and the initial document list for further academic use.

##  Marked Entity Mentions
You can download full entity annotations for ClueWeb09B and ROBUST datasets using the following [link](https://technionmail-my.sharepoint.com/:f:/g/personal/kurland_technion_ac_il/EgQpKRvvKdNMsMeciTh5-ocB4CRWmj9ryL6GtPM4SDnm-A?e=NsvVId)

## Data Format
The annotated file format is tab-separated as follows: 

<strong>Term relevance feedback</strong>

`<Query Id>`  `<stemmed token>` `<token>` `<context(for the term + sentence interface)>`  `<Worker Id>` `<annotation>`

<strong>Entity relevance feedback</strong>

`<Query Id_Entity Id>`  `<Wikipedia title>` `<context(for the entity + sentence and entity + abstract interfaces)>`  `<Worker Id>` `<annotation>`

## How To Cite Our Paper
The paper appeared in the ICTIR 2023 proceedings. Please cite our work if you find our paper or dataset useful:
TBD

