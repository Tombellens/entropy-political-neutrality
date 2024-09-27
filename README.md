# README: Charting the Roles and Careers of Ministerial Advisors - A Data-Driven Approach Using NLP

## Overview
This project presents a novel methodology for studying the roles and careers of Ministerial Advisors (MAs) using Natural Language Processing (NLP) techniques. The focus is on Flemish MAs between 1999 and 2020, using both career data and large-scale textual analysis. The study answers two key research questions:
- **RQ1**: How are the roles of MAs distributed in Flanders between 2000 and 2020?
- **RQ2**: To what extent do career paths correlate with the different types of advisors identified?

This project was completed in the context of the my PhD, and a temporary draft of the paper is included in the repository.

## Key Objectives
1. **Role Distribution (RQ1)**:  
   The paper uses Connaughton’s (2010) typology to categorize MAs into four types—experts, partisans, coordinators, and minders. NLP techniques are applied to 18,887 documents related to 341 MAs to model the axes between political-neutral roles and generalist-specialist roles.
   
2. **Correlation with Career Paths (RQ2)**:  
   The analysis explores whether career backgrounds (e.g., partisan, technocratic, or private-sector) influence the type of roles MAs assume in ministerial offices.

## Methodology
- **Data**:
   - **Dataset I**: Career data of 341 Flemish MAs from 1999 to 2020, with 2,574 coded career positions.
   - **Dataset II**: 18,887 textual documents related to these MAs from various sources (media, parliamentary documents, etc.).
   
- **Natural Language Processing (NLP)**:
   - Classifier entropy is used to model the **political-neutral axis**, measuring the certainty of political partisanship in textual documents.
   - BERTopic is employed to analyze the **specialist-generalist axis**, clustering topic probability vectors to measure the range of topics MAs engage with.

## Key Findings
- **Political-Neutral Axis**:  
   A clear distinction is found between politically active and neutral advisors, with 40% of MAs identified as politically active and 60% as politically neutral based on document entropy.

- **Specialist-Generalist Axis**:  
   Results for this axis were less clear, with issues in the BERTopic model clustering. Around 22% to 32% of MAs were identified as generalists, but further refinement of the model is needed.

- **Correlation with Career Data**:  
   The paper finds a significant correlation between political career paths and document partisanship, confirming that the career backgrounds of MAs influence their roles. However, no significant correlation was found between career paths and the specialist-generalist distinction.

## Conclusion
This study introduces a successful methodology for integrating NLP techniques with traditional political science research on the roles and careers of MAs. While the political-neutral axis provides meaningful insights, further refinement is required for the specialist-general
