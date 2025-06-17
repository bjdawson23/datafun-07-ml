# datafun-07-ml
Intoduction to Predictive ML Project
Branton Dawson

## Dataset

Intro to machine learning (ML). At a high-level, there are three general categories of ML: supervised, unsupervised, and reinforcement learning. We'll employ a type of supervised learning, simple linear regression, to train a model and use the resulting model (a "best-fit" straight line) to make predictions.

## 1. Virtual Environment Management (Windows PowerShell)

1. **Create a virtual environment**
   ```powershell
   py -m venv .venv
   ```

2. **Activate the virtual environment**
   ```powershell
   .\.venv\Scripts\activate
   ```

3. **Upgrade pip, setuptools, and wheel**
   ```powershell
   py -m pip install --upgrade pip setuptools wheel
   ```

4. **Install required packages**
   ```powershell
   py -m pip install --upgrade -r requirements.txt
   ```

---

## 2. Running Python Scripts

- Activate your `.venv` and ensure all required packages are installed.
- Verify all external packages in your scripts are listed in `requirements.txt`.

**Run Python scripts:**
```powershell
py demo_script.py
py do_stats.py
py draw_chart.py
py greet_user.py
```

---

## 3. Repeatable Workflow Checklist

When resuming work on your project, follow these steps:

1. [Pull latest changes](https://github.com/denisecase/pro-analytics-01/tree/main/03-repeatable-workflow)
2. Activate virtual environment
3. Install dependencies
4. Run Python scripts
5. Modify and test code
6. Add, commit, and push changes to Git

---

## 4. Git Add-Commit-Push CheatSheet

```powershell
git clone https://github.com/youraccount/yourrepo
git add .
git commit -m "custom message"
git push -u origin main
git pull origin main
git push
```

#### Learn Jupyter and EDA
<https://nwmissouri.instructure.com/courses/69377/assignments/1099285>


---

## P7 Predictive ML Project

### Steps

```
pip install -U spacy
python -m spacy download en_core_web_sm

py -m pip install --upgrade pip build setuptools wheel 
py -m pip install --upgrade ipykernel jupyterlab
```
--Start a New Jupyter Notebook
--Chart a Straight Line (Part 1)
--Predict Avg High Temp in NYC in January (Part 2)
--Predict Avg High Temp in NYC in January (Part 3)
--Add Insights (Part 4)
- The visualization helps us understand how NYC temperatures change over time, how well your model fits the data, and whether there are any unusual temperature events or trends worth further investigation.   
- The y-axis is limited to 10–70°F, focusing the visualization on the most relevant temperature range and making outliers or extreme values more apparent. 
- Any points far from the trend line or the main cluster may indicate outliers or unusual weather events. 
- The scatterplot shows how temperature varies across different dates, allowing you to visually assess seasonal trends, patterns, or anomalies in NYC temperature data.
- 
--Optional Bonus



       distribute storytelling as we scroll through the notebook. 

