# BBB-Permeability-Prediction-Model
Machine Learning-based prediction model for blood-brain barrier Permeability prediction of drug candidates

**Introduction:**

Welcome to our repository, here we provide machine learning model to efficiently predict the blood-brain barrier permeability of target drug compounds in early stage drug discovery process. 

**Dependencies:**

  - python=3.7
  - rdkit
  - chembl_webresource_client
  - seaborn
  - scikit-learn
  - pickle5
  - jupyter
  - molvs
  - python-graphviz
  - pydotplus


**Execution:**

Use Jupyter notebook to execute the code, download all the provided input files and models BBB.pkl model file before execution. 

Prepare your input file containing SMILES in .csv format and name the column as “SMILES”.

Make sure the paths of model, .pkl file and input files before executing the code file named as BBB_Prediction_model.ipynb.

**Out Put:**

Our model generates output in binary value (1 or 0), where 1 indicates compound to be permeable, while 0 indicates non-permeable.


**Authors:** 

Maninder Singh, Bilal Shaker, Jin Hee Lee, Sunghwan Choi, Sanghee Yoon, Shaherin Basith, Minghua Cui, Sunil Ahn, Haerim Han, Min SunYeom* and Sun Choi*
