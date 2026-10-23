# Frontiers in AI and Data Science (6CM521)

Course material for the module **6CM521 Frontiers in AI and Data Science**: lecture slides, lab sheets and Python notebooks, week by week.

**➡️ Course website: [ctsallis.github.io/frontiers_in_ai_and_data_science](https://ctsallis.github.io/frontiers_in_ai_and_data_science/)**

The notebooks run **in your web browser** on the course website. You do not need to install Python.

## Contents

1. [About the module](#about-the-module)
2. [What you need](#what-you-need)
3. [Your first five minutes](#your-first-five-minutes)
4. [How the material is organised](#how-the-material-is-organised)
5. [Course map: week by week](#course-map-week-by-week)
6. [Assessment](#assessment)
7. [Saving your work](#saving-your-work)
8. [Notebooks that need extra setup](#notebooks-that-need-extra-setup)
9. [If something goes wrong](#if-something-goes-wrong)
10. [Working on your own computer (optional)](#working-on-your-own-computer-optional)
11. [For instructors](#for-instructors)

## About the module

The module covers data science and artificial intelligence (AI), from data preparation to current topics such as generative AI and AI agents:

- preparing and exploring data with Python and pandas
- finding patterns and association rules
- regression, classification, ensembles, K-nearest neighbours and clustering
- generative AI, large language models (LLMs) and prompt engineering
- reinforcement learning
- neural networks, deep learning and explainable AI (XAI)
- agentic AI and retrieval-augmented generation (RAG)

By the end of the module you should be able to:

1. explain the fundamental concepts of machine learning and AI;
2. apply data mining tools to a problem and interpret the results;
3. choose an AI or machine learning approach for a problem and justify your choice.

## What you need

- **A computer with a recent web browser**: Chrome, Edge, Firefox or Safari. A phone or tablet is too small to work on comfortably.
- **PowerPoint and Word** (or another program that opens `.pptx` and `.docx` files) for the slides and lab sheets, and a **PDF reader**.
- **Basic Python.** If you are new to Python, start with the Week 1 notebooks.
- For a few notebooks: a free account or a key (see [Notebooks that need extra setup](#notebooks-that-need-extra-setup)).

## Your first five minutes

1. Open the [course website](https://ctsallis.github.io/frontiers_in_ai_and_data_science/). You see a file browser on the left.
2. Double-click **Lectures**, then **Semester 1**, then a week folder, e.g. **Week 1**.
3. Open a notebook (a file ending in `.ipynb`) with a double-click. Or try this one: [Week 1: Python Crash Course](https://ctsallis.github.io/frontiers_in_ai_and_data_science/lab/index.html?path=Lectures/Semester%201/Week%201/2%20Lecture%20Demos/01-Python%20Crash%20Course.ipynb).
4. Check that the kernel in the top-right corner says **Python (Pyodide)**. If the website asks you to select a kernel, choose **Python (Pyodide)**.
5. Click the first code cell and press **Shift + Enter** to run it. The first run takes a few seconds while Python loads in your browser. To run the whole notebook, use **Run → Run All Cells**.

**Slides, lab sheets and PDFs** cannot be opened inside the website (they show as unreadable text). Right-click the file and choose **Download**, then open it on your computer. The links in the [course map](#course-map-week-by-week) download them directly.

## How the material is organised

All material is in `Lectures/Semester 1/` (on GitHub: [`content/Lectures/Semester 1/`](https://github.com/ctsallis/frontiers_in_ai_and_data_science/tree/main/content/Lectures/Semester%201)). There is one folder per week; some topics take two weeks (e.g. `Week 13-14`). `Week General` holds the assessment and extra examples.

Every week folder uses the same numbered sub-folders. A week only has the ones it needs.

| Folder | What is inside | What to do with it |
|---|---|---|
| `1 Lecture` | Lecture slides | Download and read before or after the lecture |
| `2 Lecture Demos` | Notebooks shown in the lecture | Run them and change the code to see what happens |
| `3 Tutorial` | Lab sheets, exercise notebooks and their data files | Your main practice for the week |
| `4 Tutorial Answers` | Solutions | Check your work **after** you have tried the exercises |
| `5 Source Files` | Original or older versions kept for reference | You can skip these |
| `6 Further Reading` | Papers and extra reading | Optional |

> **Note:** the website sorts folders alphabetically, so `Week 10` appears before `Week 2`. Follow the order in the course map below. There is no `Week 12` folder.

## Course map: week by week

Work through the weeks from top to bottom. In each week, read the lecture slides first, then do the practice in the order shown. Links to notebooks open them on the course website; links to slides, lab sheets and PDFs download the file.

| Week | Topic | Lecture | Practice (in this order) |
|---|---|---|---|
| 1 | What AI and data science are; Python basics | [1.1 Introduction (slides)](https://ctsallis.github.io/frontiers_in_ai_and_data_science/files/Lectures/Semester%201/Week%201/1%20Lecture/1.1%20Introduction%20to%20Frontiers%20in%20AI%20and%20Data%20Science%20%28Lecture%29.pptx) | [Python Crash Course](https://ctsallis.github.io/frontiers_in_ai_and_data_science/lab/index.html?path=Lectures/Semester%201/Week%201/2%20Lecture%20Demos/01-Python%20Crash%20Course.ipynb) · [Lab sheet](https://ctsallis.github.io/frontiers_in_ai_and_data_science/files/Lectures/Semester%201/Week%201/3%20Tutorial/Lab.docx) · [Exercises](https://ctsallis.github.io/frontiers_in_ai_and_data_science/lab/index.html?path=Lectures/Semester%201/Week%201/3%20Tutorial/02-Python%20Crash%20Course%20Exercises.ipynb) · [Solutions](https://ctsallis.github.io/frontiers_in_ai_and_data_science/lab/index.html?path=Lectures/Semester%201/Week%201/4%20Tutorial%20Answers/03-Python%20Crash%20Course%20Exercises%20-%20Solutions.ipynb) · [Reading: Strong and Weak AI](https://ctsallis.github.io/frontiers_in_ai_and_data_science/files/Lectures/Semester%201/Week%201/6%20Further%20Reading/Flowers%20-%20Strong%20and%20Weak%20AI%20-%20Deweyan%20Considerations.pdf) |
| 2 | Data preprocessing with pandas | [1.2 Data Preprocessing (slides)](https://ctsallis.github.io/frontiers_in_ai_and_data_science/files/Lectures/Semester%201/Week%202/1%20Lecture/1.2%20Data%20Preprocessing%20%28Lecture%29.pptx) | Eight pandas notebooks, in order: [01](https://ctsallis.github.io/frontiers_in_ai_and_data_science/lab/index.html?path=Lectures/Semester%201/Week%202/3%20Tutorial/01-Introduction%20to%20Pandas.ipynb) · [02](https://ctsallis.github.io/frontiers_in_ai_and_data_science/lab/index.html?path=Lectures/Semester%201/Week%202/3%20Tutorial/02-Series.ipynb) · [03](https://ctsallis.github.io/frontiers_in_ai_and_data_science/lab/index.html?path=Lectures/Semester%201/Week%202/3%20Tutorial/03-DataFrames.ipynb) · [04](https://ctsallis.github.io/frontiers_in_ai_and_data_science/lab/index.html?path=Lectures/Semester%201/Week%202/3%20Tutorial/04-Missing%20Data.ipynb) · [05](https://ctsallis.github.io/frontiers_in_ai_and_data_science/lab/index.html?path=Lectures/Semester%201/Week%202/3%20Tutorial/05-Groupby.ipynb) · [06](https://ctsallis.github.io/frontiers_in_ai_and_data_science/lab/index.html?path=Lectures/Semester%201/Week%202/3%20Tutorial/06-Merging%2C%20Joining%2C%20and%20Concatenating.ipynb) · [07](https://ctsallis.github.io/frontiers_in_ai_and_data_science/lab/index.html?path=Lectures/Semester%201/Week%202/3%20Tutorial/07-Operations.ipynb) · [08](https://ctsallis.github.io/frontiers_in_ai_and_data_science/lab/index.html?path=Lectures/Semester%201/Week%202/3%20Tutorial/08-Data%20Input%20and%20Output.ipynb) |
| 3 | Exploratory data analysis (EDA) | [1.3 EDA (slides)](https://ctsallis.github.io/frontiers_in_ai_and_data_science/files/Lectures/Semester%201/Week%203/1%20Lecture/1.3%20Exploratory%20Data%20Analysis%20%28Lecture%29.pptx) | [Demo: Ecommerce Purchases](https://ctsallis.github.io/frontiers_in_ai_and_data_science/lab/index.html?path=Lectures/Semester%201/Week%203/2%20Lecture%20Demos/01-Data%20Preprocessing%20Demo%20%28Ecommerce%20Purchases%29.ipynb) · [Lab sheet](https://ctsallis.github.io/frontiers_in_ai_and_data_science/files/Lectures/Semester%201/Week%203/3%20Tutorial/Lab.docx) · [Titanic EDA](https://ctsallis.github.io/frontiers_in_ai_and_data_science/lab/index.html?path=Lectures/Semester%201/Week%203/3%20Tutorial/01-Titanic%20EDA%20Example.ipynb) |
| 4 | Frequent patterns, association rules, correlation | [1.4 Mining Frequent Patterns (slides)](https://ctsallis.github.io/frontiers_in_ai_and_data_science/files/Lectures/Semester%201/Week%204/1%20Lecture/1.4%20Mining%20Frequent%20Patterns%20%28Lecture%29.pptx) | [Market Basket Analysis](https://ctsallis.github.io/frontiers_in_ai_and_data_science/lab/index.html?path=Lectures/Semester%201/Week%204/3%20Tutorial/01-Market%20Basket%20Analysis%20%28Online%20Retail%29.ipynb) · [Correlation Analysis](https://ctsallis.github.io/frontiers_in_ai_and_data_science/lab/index.html?path=Lectures/Semester%201/Week%204/3%20Tutorial/02-Correlation%20Analysis.ipynb) · [Apriori exercise](https://ctsallis.github.io/frontiers_in_ai_and_data_science/lab/index.html?path=Lectures/Semester%201/Week%204/3%20Tutorial/03-Association%20Rules%20with%20Apriori%20-%20Exercise.ipynb) · [Solution](https://ctsallis.github.io/frontiers_in_ai_and_data_science/lab/index.html?path=Lectures/Semester%201/Week%204/4%20Tutorial%20Answers/03-Association%20Rules%20with%20Apriori%20-%20Solution.ipynb) |
| 5 | Regression | [1.5 Regression (slides)](https://ctsallis.github.io/frontiers_in_ai_and_data_science/files/Lectures/Semester%201/Week%205/1%20Lecture/1.5%20Regression%20Problems%20%28Lecture%29.pptx) | [Lab sheet (Weeks 5–8)](https://ctsallis.github.io/frontiers_in_ai_and_data_science/files/Lectures/Semester%201/Week%205/3%20Tutorial/Lab.docx) · [Lab example solutions](https://ctsallis.github.io/frontiers_in_ai_and_data_science/lab/index.html?path=Lectures/Semester%201/Week%205/4%20Tutorial%20Answers/Lab%20Example%20Solutions.ipynb) |
| 6 | Classification and decision trees | [1.6 Classification (slides)](https://ctsallis.github.io/frontiers_in_ai_and_data_science/files/Lectures/Semester%201/Week%206/1%20Lecture/1.6%20Classification%20Problems%20and%20Decision%20Tree%20Induction%20%28Lecture%29.pptx) | [Demo: Decision Tree (Play Golf)](https://ctsallis.github.io/frontiers_in_ai_and_data_science/lab/index.html?path=Lectures/Semester%201/Week%206/2%20Lecture%20Demos/01-Decision%20Tree%20Worked%20Example%20%28Play%20Golf%29.ipynb) · [Lab sheet](https://ctsallis.github.io/frontiers_in_ai_and_data_science/files/Lectures/Semester%201/Week%206/3%20Tutorial/Lab.pdf) |
| 7 | Ensemble methods and K-nearest neighbours | [1.7 Ensembles and K-NN (slides)](https://ctsallis.github.io/frontiers_in_ai_and_data_science/files/Lectures/Semester%201/Week%207/1%20Lecture/1.7%20Ensemble%20Methods%20and%20K-NN%20%28Lecture%29.pptx) | [Demo: Random Forests](https://ctsallis.github.io/frontiers_in_ai_and_data_science/lab/index.html?path=Lectures/Semester%201/Week%207/2%20Lecture%20Demos/Random%20Forests%20Demo.ipynb) · [K-NN practice](https://ctsallis.github.io/frontiers_in_ai_and_data_science/lab/index.html?path=Lectures/Semester%201/Week%207/3%20Tutorial/K-NN%20Practice%20Example.ipynb) |
| 8 | Clustering | [1.8 Clustering (slides, PDF)](https://ctsallis.github.io/frontiers_in_ai_and_data_science/files/Lectures/Semester%201/Week%208/1%20Lecture/1.8%20Clustering%20Problems%20%28Lecture%29.pdf) | [Demo: K-Means](https://ctsallis.github.io/frontiers_in_ai_and_data_science/lab/index.html?path=Lectures/Semester%201/Week%208/2%20Lecture%20Demos/K-Means%20Clustering%20Demo.ipynb) |
| 9 | Generative AI and prompt engineering | [1.9 Generative AI (slides)](https://ctsallis.github.io/frontiers_in_ai_and_data_science/files/Lectures/Semester%201/Week%209/1%20Lecture/1.9%20Generative%20AI%20and%20Prompt%20Engineering%20%28Lecture%29.pptx) | [Demo: Self-Attention](https://ctsallis.github.io/frontiers_in_ai_and_data_science/lab/index.html?path=Lectures/Semester%201/Week%209/2%20Lecture%20Demos/Self-Attention%20from%20Scratch.ipynb) · [Lab sheet](https://ctsallis.github.io/frontiers_in_ai_and_data_science/files/Lectures/Semester%201/Week%209/3%20Tutorial/Lab.docx) · [LLM API solution](https://ctsallis.github.io/frontiers_in_ai_and_data_science/lab/index.html?path=Lectures/Semester%201/Week%209/4%20Tutorial%20Answers/LLM%20API%20Example%20Solution.ipynb) ¹ |
| 10 | Reinforcement learning | [1.10 Reinforcement Learning (slides)](https://ctsallis.github.io/frontiers_in_ai_and_data_science/files/Lectures/Semester%201/Week%2010/1%20Lecture/1.10%20Reinforcement%20Learning%20%28Lecture%29.pptx) | Practice is in Week 11 |
| 11 | Reinforcement learning lab | Slides are in Week 10 | [Lab sheet](https://ctsallis.github.io/frontiers_in_ai_and_data_science/files/Lectures/Semester%201/Week%2011/3%20Tutorial/Lab.docx) · [Frozen Lake](https://ctsallis.github.io/frontiers_in_ai_and_data_science/lab/index.html?path=Lectures/Semester%201/Week%2011/3%20Tutorial/FrozenLake_RL_Exploration.ipynb) |
| 13-14 | Neural networks, deep learning and explainable AI (XAI) | [1.13 Neural Networks and XAI (slides)](https://ctsallis.github.io/frontiers_in_ai_and_data_science/files/Lectures/Semester%201/Week%2013-14/1%20Lecture/1.13%20Neural%20Networks%2C%20Deep%20Learning%20and%20XAI%20%28Lecture%29.pptx) | [Assessment labs: reading list](https://ctsallis.github.io/frontiers_in_ai_and_data_science/files/Lectures/Semester%201/Week%2013-14/3%20Tutorial/Lab.docx) |
| 15-16 | Object detection and XAI in practice | Slides are in Week 13-14 | [YOLO v3 object detection](https://ctsallis.github.io/frontiers_in_ai_and_data_science/lab/index.html?path=Lectures/Semester%201/Week%2015-16/3%20Tutorial/01-Object%20Detection%20with%20YOLO%20v3.ipynb) · [Explainable AI](https://ctsallis.github.io/frontiers_in_ai_and_data_science/lab/index.html?path=Lectures/Semester%201/Week%2015-16/3%20Tutorial/02-Explainable%20AI%20with%20a%20Random%20Forest.ipynb) |
| 17-18 | Agentic AI; a RAG and MCP case study | [1.17 Agentic AI (slides)](https://ctsallis.github.io/frontiers_in_ai_and_data_science/files/Lectures/Semester%201/Week%2017-18/1%20Lecture/1.17%20Agentic%20AI%20for%20Business%20and%20Software%20Engineering%20%28Lecture%29.pptx)<br>[1.18 RAG and MCP (slides)](https://ctsallis.github.io/frontiers_in_ai_and_data_science/files/Lectures/Semester%201/Week%2017-18/1%20Lecture/1.18%20A%20Case%20Study%20of%20a%20RAG%20and%20MCP%20LLM%20System%20%28Lecture%29.pptx) | [Reading: LoRA and QLoRA](https://ctsallis.github.io/frontiers_in_ai_and_data_science/files/Lectures/Semester%201/Week%2017-18/6%20Further%20Reading/LoRA%20and%20QLoRA%20Fine-Tuning%20%28Student%20Presentation%202024%29.pdf) |
| General | Assessment and extra examples | [Assessment brief 2026-27](https://ctsallis.github.io/frontiers_in_ai_and_data_science/files/Lectures/Semester%201/Week%20General/3%20Tutorial/Assessment%20Brief%206CM521%202026-2027.docx) | [QLoRA fine-tuning](https://ctsallis.github.io/frontiers_in_ai_and_data_science/lab/index.html?path=Lectures/Semester%201/Week%20General/3%20Tutorial/QLoRA%20Fine-Tuning%20Llama%203.2%20for%20Customer%20Support.ipynb) ² · [YOLOv8 training](https://ctsallis.github.io/frontiers_in_ai_and_data_science/lab/index.html?path=Lectures/Semester%201/Week%20General/3%20Tutorial/YOLOv8%20Object%20Detection%20on%20a%20Custom%20Dataset.ipynb) ² |

¹ Needs a free API key; see [Notebooks that need extra setup](#notebooks-that-need-extra-setup).

² Does not run in the browser; read it with its saved outputs. See [Notebooks that need extra setup](#notebooks-that-need-extra-setup).

## Assessment

- The assessment brief for 2026-27 is in **Week General → 3 Tutorial → Assessment Brief 6CM521 2026-2027.docx**. It describes the two topics, the datasets, the deliverables, the marking scheme and the deadline.
- The **Week 13-14 lab sheet** is a reading list for the assessment work (evaluation, fine-tuning, segmentation and LLM resources).
- The two notebooks in **Week General → 3 Tutorial** are worked examples of fine-tuning a vision model and a language model.
- Last year's brief (2025-26) is kept in `Week General/5 Source Files` for reference only. **Use the 2026-27 brief.**

## Saving your work

- When you change a notebook on the website, your changes are saved **in your browser only**. They are not uploaded anywhere.
- Your changes stay on the same computer and browser, but they are lost if you clear your browsing data or use a private window.
- **To keep a copy, download it:** right-click the notebook in the file browser and choose **Download**.
- To keep the original unchanged, make your own copy first: right-click the notebook and choose **Duplicate**, then work in the copy.

## Notebooks that need extra setup

Most notebooks need nothing extra. Some install small libraries in their first cell (a `%pip install …` line); this happens automatically and takes a few seconds.

| Notebook | What it needs |
|---|---|
| Week 9 → LLM API Example Solution | Your own free API key from [OpenRouter](https://openrouter.ai/keys). Without a key, the notebook shows the requests instead of sending them. |
| Week 15-16 → Explainable AI with a Random Forest | Nothing, but the first cell takes about a minute to install the libraries. |
| Week General → QLoRA fine-tuning and YOLOv8 training | A computer with an NVIDIA GPU, plus a Hugging Face or Roboflow account. They **do not run in the browser**: read them on the website with their saved outputs, or download them and follow the instructions at the top of each notebook. |

## If something goes wrong

- **A cell shows an error about a missing name or variable:** run the earlier cells first, or use **Run → Run All Cells**.
- **The notebook seems stuck:** use **Kernel → Restart Kernel**, then run the cells again from the top.
- **The website asks you to choose a kernel:** choose **Python (Pyodide)**.
- **You want the original notebook back:** if you made a copy (Duplicate), the original is unchanged. Otherwise, right-click in the file browser and choose **Clear Browser Data**: this brings back the original version of every file and **deletes all your changes**, so download anything you want to keep first.
- **Still stuck?** Ask your tutor in the lab, and say which week and notebook you were using.

## Working on your own computer (optional)

You do not need this, but you can run the notebooks with your own Python:

1. Install Python 3 and Jupyter, for example with [Anaconda](https://www.anaconda.com/download).
2. Download the notebook **and the data files in the same folder** (they are read from the notebook's folder).
3. Open the notebook in Jupyter and run it. The `%pip install` lines in the first cell install what the notebook needs.

One exception: **Week 15-16 → Explainable AI with a Random Forest** installs two packages from its `wheels` folder in a way that only works on the website. On your own computer, run `pip install lime anchor-exp xai optuna shap eli5` instead of its first code cell.

## For instructors

- The website is built from the `content/` folder with [JupyterLite](https://jupyterlite.readthedocs.io/). Every change merged into `main` rebuilds the site (`.github/workflows/deploy.yml`).
- This README is also copied to the website, so its links are full web addresses, not relative paths.
- New weeks go in `content/Lectures/Semester 1/Week N/` and use the numbered sub-folders above. Add a row to the course map when you add a week.
- Notebooks must run with the **Python (Pyodide)** kernel: only pure-Python packages from PyPI or packages included in Pyodide, data files next to the notebook, and no system commands.
