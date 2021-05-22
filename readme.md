# Code Samples for the Springer Article on Causal Inference

## Structure:
This repository provides several notebooks, the structure is the following:
1. EDA: EDA.ipynb
2. Structure Learning: StructureLearning.ipynb
3. Categorical Models: Categorical.iypnb
4. Continuous Models: Continuous.ipynb
5. Complete Model and Inference: Complete.ipynb

## prerequisites:
The Notebooks are intendende to be run with Python3. While none of the "newer" features, e.g. Type Hinting have been used, older versions (< 3.6) might be problematic in combination with some of the 3rd party libraries:
### 3rd party libraries:
Besides the usual "Data Science Stack" (numpy, pandas, sklearn), mostly pgmpy and networkx for graph visualization
A version pinned requirements.txt file is provided.
To recreate such an environment, do  - with python3-venv installed -
'''
python3 -m venv caus_inf_env
source caus_inf_env/bin/activate
pip install -r requirements.txt
'''

