# Academic-Papers-Topic-Modeling

## Overview
Academic research is growing at an unprecedented rate, with thousands of new papers being published every day across various fields of study. This wealth of information can be overwhelming for researchers trying to stay updated with the latest developments in their domains. To address this challenge, our project focuses on the automatic generation of topics or clusters for academic papers based on their metadata.

## Problem Statement
The primary problem we aim to solve is the efficient organization and exploration of large academic research datasets. Traditional methods of searching and categorizing papers often fall short when dealing with such vast amounts of information. Researchers need a more effective way to discover relevant papers and understand the overarching themes and topics within their research area.

## Solution
Our solution leverages cutting-edge natural language processing (NLP) techniques, specifically BERT-based models, to perform topic modeling on academic papers. By analyzing metadata such as titles, abstracts, authors, categories, and keywords, our system can automatically group papers into clusters that represent coherent research topics. These clusters serve as a map for researchers, guiding them to the most relevant and recent papers in their field of interest.

## Metadata

This dataset is a mirror of the original ArXiv data. Due to the large size of the full dataset (1.1TB and growing), this specific dataset provides only a metadata file in JSON format. Each entry in the metadata file contains the following information for an academic paper:

- `id`: ArXiv ID (used for accessing the paper)
- `submitter`: The person who submitted the paper
- `authors`: List of authors for the paper
- `title`: Title of the paper
- `comments`: Additional information such as the number of pages and figures
- `journal-ref`: Information about the journal in which the paper was published
- `doi`: Digital Object Identifier (DOI) for the paper
- `abstract`: The abstract of the paper
- `categories`: Categories or tags in the ArXiv system
- `versions`: Version history of the paper
