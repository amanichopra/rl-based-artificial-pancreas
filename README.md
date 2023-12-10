# RL-Based Artifial Pancreas

Closed-loop systems have become more and more popular for T1 diabetics, allowing insulin pumps to automatically regulate blood sugar through constant communication with a CGM sensor. Most of these systems already use RL. In this project, we experiment with additional data from wearables like Apple Watch to enable even better blood sugar control. This code repository is structured as follows.

- Preprocessing & EDA: `eda_preprocessing.ipynb`, `applehealthdata.py`
- Building a Regression-based Transition Model: `tx_model.ipynb`
- RL Algorithms: `dqn.ipynb`, `policy_gradient.ipynb`
- Simulations Using UVA/PADOVA T1 Diabetes Simulator: `simglucose.ipynb`