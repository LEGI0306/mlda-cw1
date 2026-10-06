\# Online Shoppers Purchasing Intention (MLDA CW1)



Predicting whether an e-commerce session ends in a purchase (binary classification).



\## Dataset

Sakar, C. and Kastro, Y. (2018) Online Shoppers Purchasing Intention Dataset.

UCI Machine Learning Repository. https://doi.org/10.24432/C5F88Q

Licence: CC BY 4.0. 12,330 sessions, 18 features, target: `Revenue`.



\## Setup

&#x20;   python -m venv .venv

&#x20;   .venv\\Scripts\\activate

&#x20;   pip install -r requirements.txt



\## Run the notebook

&#x20;   jupyter notebook notebooks/01\_eda.ipynb



\## Run the app (added in Week 6)

&#x20;   streamlit run app/Home.py



\## Structure

\- data/raw/ original CSV (unchanged)

\- data/processed/ cleaned data

\- notebooks/ analysis notebooks

\- app/pages/ Streamlit pages

\- src/ reusable code

\- report/ written report

