# COMP8420-DocBot
 
# DocBot: Intelligent Document Discovery
## Overview
In large enterprises, navigating extensive data warehouses to locate specific files and their respective paths can be a daunting task. This project addresses this real-world challenge by developing an Intelligent Question Answering (QA) system designed to enhance document discovery. The system aims to predict the correct file path, including folders and subfolders, when provided with a filename, thereby streamlining data retrieval processes in complex data environments. The output also gives the top 3 outputs with the highest probabilities as the folder names the files are located in.

## Project Scope
Data warehouses in large organizations store vast amounts of information across numerous folders and subfolders. Employees often face difficulties in locating the exact file they need, leading to inefficiencies and wasted time. The complexity of these data warehouses necessitates a robust solution that can accurately predict the paths of specific files based on minimal input, such as a filename or a short description.

## Methodlogy
*. DistilBERT: Chosen for its efficiency and effectiveness in question-answering tasks. DistilBERT, a smaller and faster variant of BERT, retains a significant portion of BERT's performance while requiring fewer computational resources.
*. Synthetic Data Generation: Created using a Kaggle-based dataset, transforming product names into FAQs. The synthetic dataset serves as the foundation for training the model, ensuring it can handle a variety of user queries.
