## Code for the paper "Detecting cyberbullying on social networks"

This repository makes available the code for data preprocessing and data generation based on the dataset provided by Noman Ashraf et al. at https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8507480/.

We examined a cyberbullying-labeled dataset of 2000 YouTube comments, manually extracted 3044 keywords (932 unique), and manually extracted 1106 key phrases related to cyberbullying. To do this, we used the distilbert-base-uncased language model provided by huggingface.io to calculate cosine similarity between key phrases to determine similarity thresholds for clustering semantically related expressions. 

Both the code and the generated datasets are made available in this repository.

This  jupyter notbook can be used directly. All requirements are coded in the jupyter cells. We recommend using virtual environment (python3 -m venv myven)

The paper was submitted to ... on ...

### NOTE: This work is licensed under CC BY-ND until the work is published, at which time the MIT license takes effect.

Attribution-NoDerivs 
CC BY-ND

This license lets others reuse the work for any purpose, including commercially; however, it cannot be shared with others in adapted form, and credit must be provided to you.