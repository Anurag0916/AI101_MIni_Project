# Maximum loan Amount Estimation
Predicts the maximum loan amount with based on  property feature using linear regression
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
Tested on Python 3.14(Windows,Macos)
**1. Clone the repository**
```bash
git clone https://github.com/Anurag0916/AI101_MIni_Project.git loan_predictor_team_67
cd loan_predictor_team_67
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
Presentation: (https://1drv.ms/p/c/2014e32ad65baf52/IQAXSX0vh-O2QauVQ9D3mnmqAWqjDCM0dL_1KngNkoAc4DU?e=mjuFYF)
Video: (https://www.youtube.com/watch?v=WYuvF2AlEbQ)
Github Repo: (https://github.com/Anurag0916/AI101_MIni_Project)

## AI Use Disclosure

Claude and Gemini were used for debugging errors in code, create a heatmap and to solve a git pull conflict.​
Gemini was used to generate the first draft of README. Edited By Nikita.​
AI tools were used to create the template of the presentation. Edited by Aashish.​
