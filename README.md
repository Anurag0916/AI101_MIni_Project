# Maximum loan Amount Estimation
predicts the maximum loan amount with based on  property feature using linear regression
## Team and roles
|Member|Entry no.|Role|
|-|-|-|
|Nikita Choudhary|2026MCB1550|Documentation Lead|
|Anurag Beri|2026AIB1018|Execution lead|
|Aashish Kumar|2026EEB1312|PPT Lead |
|Kushagra Gupta|2026EEB1370|Video Lead|
## Project structure
```
AI101_MIni_Project/
├── data/
│  └── loan_approval_dataset.csv
4200+rows,applicant financials
├── loan_prediction.ipynb
entry point and model pipeline
├── requirements.txt
└── README.md
```
## Setup
Tested on python 3.10 and 3.11 (Windows,macos)
```
git clone https://github.com/Anurag0916/AI101_MIni_Project.git
cd AI101_MIni_Project
python-m venv venv
venv\Scripts\activate(#for Windows)
# For Macos and Linux:source
venv/bin/activate 
python -m pip install -r requirements.txt
```
## How to run?
1. Run the setup in your terminal
2. run jupyter notebook in your terminal
3. open loan_prediction.ipynb in the browser interface
4. click cell > run all
5. The script prints the data summary,outputs the correlation heatmap,and displays the model accuracy metrics(MAE,MSE,R2)
6. expected runtime: Under 1 minute

## Links 
## AI Use Disclosure 
Large Language models(Gemini) were used to debug preprocessing pipeline errors in scikit-learn(column Transformer and pipeline implementations),add code documentation/comments,and to draft the intial structure of this README file.all generated code and text were reviewed,modified for accuracy,and are fully understood by the team
