# Incident reassignment and resolution time

Public repository: https://github.com/marttp/ai-programming-foundations-project

The submission is on `main`. The [incident-workflow branch](https://github.com/marttp/ai-programming-foundations-project/tree/incident-workflow) preserves the development history.

Each row in the source is a ticket update. The notebook reconstructs one observation per incident and compares resolution time across reassignment groups. Downloaded from [Kaggle](https://www.kaggle.com/datasets/vipulshinde/incident-response-log), the unchanged CSV is the Incident Management Process Enriched Event Log by Claudio Amaral, Marcelo Fantinato, and Sarajane Peres (see the [UCI record and CC BY 4.0 attribution](https://doi.org/10.24432/C57S4H)).

With Python 3.11, run `python -m pip install -r requirements.txt`, then `python -m notebook data_workflow.ipynb` and choose Run All.
