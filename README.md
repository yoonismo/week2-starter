# Week 2 starter

Practice repository for **Week 2: From Experiments to Observational Data**.
Full instructions: <https://yoonismo.github.io/causal-computing/week2.html>

## What is in here

| File | Purpose |
|---|---|
| `week2.ipynb` | The code from the Week 2 page (Labs 1–3), in the same order |
| `star_practice.ipynb` | Practice on your own: repeat Labs 2 and 3 with the Tennessee STAR class-size experiment |
| `requirements.txt` | The packages the automatic check installs |
| `.github/workflows/ci.yml` | The automatic check: runs both notebooks on GitHub's computer after every push |

## Before you start

Week 2 needs three packages that Week 1 did not: `pandas` (you installed it in Week 1 Lab 3), `causaldata` and `statsmodels`. Activate the course environment and install them (this works from any folder):

```bash
source ~/ECON481/.venv/bin/activate      # macOS
~\ECON481\.venv\Scripts\activate          # Windows (PowerShell)
uv pip install pandas causaldata statsmodels
```

Run only the `activate` line for your system.

Both notebooks download their data from the internet, so you need a connection.

## Steps

1. Click **Use this template** → **Create a new repository**, then clone your copy to your computer, as in Week 1 Lab 3.
2. Run `week2.ipynb` in order along with the Week 2 page, and answer the questions in it.
3. Work through `star_practice.ipynb`. Each `# TODO` cell has a check cell right after it.
4. Clear all outputs, then `git add`, `git commit` and `git push`. The **Actions** tab should turn green.
