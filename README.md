# CrowdsourcingRelevanceScales
repository for the paper "On the Effect of Relevance Scales in Crowdsourcing Relevance Assessments for Information Retrieval Evaluation."


This repository contains the crowdsourced judgments used in the IPM'21 paper titled "On the Effect of Relevance Scales in Crowdsourcing Relevance Assessments for Information Retrieval Evaluation."

## Citation
If you use this resource, please cite our paper:

*Kevin Roitero, Eddy  Maddalena, Stefano Mizzaro, and Falk Scholer. On the Effect of Relevance Scales in Crowdsourcing Relevance Assessments for Information Retrieval Evaluation. Information processing and Management (IPM).*



### BibTeX

```bibtex
@article{roitero2021scales,
author = {Roitero, kevin and Maddalena, Eddy and  Mizzaro, Stefano and  Scholer, Falk},
title = {On the Effect of Relevance Scales in Crowdsourcing Relevance Assessments for Information Retrieval Evaluation.},
journal = {Information processing and Management (IPM)},
year={2021}
}
```

## Data

The dataset, contained in the .csv file contains the following information:
 - `topic_id`: The ID of the topic.
 - `unit_id`: The ID of the HIT.
 - `document_id`: The name of the document.
 - `gold`: The indication of whether the document is a gold one.
 - `doc_pos`: The position of the docuemnt in the set of documents as seen by the worker.
 - `worker_id`: The encrypted worker ID (to allow anonymity).
 - `relevance_score`: The score as submitted by the worker.
 - `normalized_relevance_score`: The normalized relevance score (if available).
 - `cumulative_time`: The time spent by the worker to assess the statement.
 - `comment`: The comment left by the worker as a justification for the submitted score.
 - `trec`: The score as submitted by TREC (if available).
 - `sormunen`: The score as submitted by Sormunen (if available).
 - `relevance_scale`: The relevance scale used by the workers to perform the assessment.
