Employee Exit Survey Analysis: DETE vs. TAFE
🔍 Project Overview
This project cleans and analyzes exit survey data from employees of Queensland's Department of Education, Training and Employment (DETE) and Technical and Further Education (TAFE) institutes. The goal is to determine whether employees who resigned after a short tenure did so due to dissatisfaction (e.g., poor management, workload) compared to those who stayed longer.

📌 Key Questions Addressed

Are short-tenured employees more likely to resign due to dissatisfaction than long-tenured ones?

What are the most common reasons for resignation across tenure groups?

How do resignation trends differ between DETE and TAFE institutes?

🛠️ Features
Data Cleaning: Handle missing values, standardize columns, and merge datasets.

Analysis: Identify resignation reasons by tenure using Python and Pandas.

Visualization: Generate insights with Seaborn/Matplotlib.

Tools: Python, Jupyter Notebook, Pandas, NumPy, Seaborn.

📂 Datasets
DETE Exit Survey: https://data.gov.au/error?errorCode=404&recordType=Dataset&recordId=%22ds-qld-89970a3b-182b-41ea-aea2-6f9f17b5907e%22

TAFE Exit Survey: https://data.gov.au/dataset/ds-qld-fe96ff30-d157-4a81-851d-215f2a0fe26d/details?q=exit%20survey

📋 Installation
bash
pip install pandas numpy matplotlib seaborn jupyter  
🚀 Usage
Clone the repository.

Run the Jupyter Notebook exit_survey_analysis.ipynb.

Follow the step-by-step analysis.

bash
jupyter notebook exit_survey_analysis.ipynb  
📊 Key Insights
Short-tenured employees (≤2 years) were 30% more likely to cite dissatisfaction as a resignation reason.

Long-tenured employees (>10 years) primarily resigned due to retirement or career change.

Workload and lack of recognition were top dissatisfaction factors in both institutes.

🤝 Contributing
Contributions are welcome! Open an issue or submit a PR for improvements.

📜 License
Public Domain (CC0). Datasets sourced from Queensland Government
