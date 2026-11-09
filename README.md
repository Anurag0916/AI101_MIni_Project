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

**1. Clone the repository**
```bash
git clone https://github.com/Anurag0916/AI101_MIni_Project.git
cd AI101_MIni_Project
```

**2. Create and activate a virtual environment**

Windows:
```bash
python -m venv venv
venv\Scripts\activate
```

macOS / Linux:
```bash
python3 -m venv venv
source venv/bin/activate
```

**3. Install the dependencies**
```bash
python -m pip install -r requirements.txt
```

## How to run

1. Start Jupyter from the project folder:
   ```bash
   jupyter notebook project.ipynb
   ```
2. In the notebook, choose **Kernel → Restart & Run All** (or press `Shift+Enter` through each cell in order).
3. The notebook loads the dataset from `data/`, trains the linear regression model and prints the evaluation metrics and plots.


## Links 
## AI Use Disclosure 
Large Language models(Gemini) were used to debug preprocessing pipeline errors in scikit-learn(column Transformer and pipeline implementations),add code documentation/comments,and to draft the intial structure of this README file.all generated code and text were reviewed,modified for accuracy,and are fully understood by the team
