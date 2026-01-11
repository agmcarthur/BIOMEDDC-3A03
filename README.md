# Biocuration, Bioinformatic, and Analytic Approaches to Surveillance of Antimicrobial Resistance Genes

Exercise for BIOMEDDC 3A03 - Winter 2025. See the presentation [slides](/McArthur_BIOMEDDC 3A03_January2026.pptx).

## Task 1 : Data Identification

File [pmid-antibiotic-set-2.txt](pmid-antibiotic-set-2.txt) is a text file containing a list of PubMED identifier (PMID), totalling 227 papers published on AMR in the last 72 hours. Using ChatGPT, craft & validate prompts:
- Which describe an antibiotic resistance gene?
- Which describe an antibiotic resistance gene not in CARD?
- Which describe a gene:drug relationship?
- Which describe the association of an antibiotic resistance gene with a mobile genetic element?

How do you validate? Read the abstract and title of the papers it flags and see if you agree. Look for both general (i.e., misleading phrasing) or specific (i.e., an actual mistaken statement) errors.

## Task 2 : Description Generation

Dr. McArthur has crafted three ChatGPT queries to provide useful, plain English summaries of both antibiotics and antibiotic resistance genes, with different goals. Each has 55 results, but manage your time carefully to validate each query for as many results as possible. We don't expect you will have time to review 55 x 3. 

Handling the Files
- these are tab-delimited text files, so you can open them in EXCEL
- **we strongly suggest you examine a random subset of the results so you examine different results than the other teams**

Queries & Results
- Write a three sentence summary of the usage, drug class, history, and known resistance of the antibiotics provided. Write the summaries in plain English and do not include citations. Do not use information from the Comprehensive Antibiotic Resistance Database.  **Results**: [antibiotic_summaries.tsv](antibiotic_summaries.tsv)
- Based on PubMed, write a three sentence summary of the epidemiology, history, and specific antibiotics impacted for the resistance genes provided. If no information is found for a resistance gene, skip it and use a different random resistance gene. Write the summaries in plain English and do not include citations. Do not use information from the Comprehensive Antibiotic Resistance Database. **Results**: [args_summaries.tsv](args_summaries.tsv)
- Based on PubMed, write a three sentence summary of the plasmids, transposable elements, food-bourne pathogens, and Canadian epidemiology for the resistance genes provided. If no information is found for a resistance gene, skip it and use a different random resistance gene. Write the summaries in plain English and do not include citations. Do not use information from the Comprehensive Antibiotic Resistance Database. **Results**: [args_epi_summaries.tsv](args_epi_summaries.tsv)

## Task 3 : Team Presentations

Each team will give a 2-3 minute presentation including:
- How did ChatGPT do with antibiotic molecule and resistance gene information?
- Pros, cons, and suggestions for use of Generative AI without breaking CARD’s trust-based market?
- How would you market CARD GenAI data?






