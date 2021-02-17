# Decision-Making-Logic-Taxonomy
It is aimed to discover the decision-making nature of activities, called Decision-Making Logic (DML) level. We use the following DML levels: routine, semi-cognitive and cognitive. For this purpose, first, we compile a DML taxonomy. Using a Latent Dirichlet Allocation Algorithm, we identify most important keywords in the text corpus. Each of the keywords is associated with a DML level. While organizing identified keywords into one of the three DML levels, we consider diverse semantic concepts of business processes: Resources, Techniques, Capacities, and Choices, elements of RTCC framework. We designed contextual variables (see DML_Taxonomy/Decision_Making_Logic_Taxonomy.pdf), based on which experts categorized words into one of the three DML levels and one of the four semantic concepts.

This repository contains the following files: DML taxonomy vocabulary, python file for extracting DML keywords (as an input for python files serve ticket textual descriptions and DML taxonomy), excel file with the calculation of DML based on the motivating example, threshold rules, and illustrative DML taxonomy.

Below, we describe the main stages of DML indentification.

Python code (DML Tickets.py): STAGE 1. DML taxonomy (RTCC) (1.1.) reading and (1.2) stemming. STAGE 2. Tickets corpus reading, preprocessing and English language filtering. STAGE 3. Find and count words in the ticket description that match the DML taxonomy keywords. STAGE 4. Writing of matched words and their number by DML categories of routine, semi-cognitive, and cognitive in the *.csv file. 

Excel *.csv file (DML_Calculation.xlsx): STAGE 6. Calculation of the relative occurrence of the keywords by DML categories. STAGE 7. DML identification.
