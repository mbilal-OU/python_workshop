# Python for Biologists — Workshop Tutorial

**Muhammad Bilal**
Department of Biological Sciences, Oakland University, Rochester MI

---

hey everyone! this is the complete workshop tutorial notebook.

everything is in one place — no jumping between files.
open the notebook, start from the top, and work through it at your own pace.

---

## the notebook covers

| section | what you learn |
|---|---|
| Session 1 | variables, data types, strings, lists, loops, functions |
| Session 2 | dictionaries, reading FASTA files, reading/writing CSV |
| Session 3 | pandas for data analysis, making publication-ready plots |
| Mini Project | build a complete sequence analyser from scratch |
| Error Reference | common errors and how to fix them |

biology examples throughout — GC content, genome stats, growth curves, FASTA parsing.
every error shown comes with an explanation and a fix.

---

## how to open the notebook

### option 1 — google colab (easiest, no install needed)

1. go to https://colab.research.google.com
2. click **File > Open notebook > GitHub**
3. paste this URL: `https://github.com/mbilal-OU/python_workshop`
4. open `Python_Workshop_Biology.ipynb`

### option 2 — run on your own computer

```bash
# install what you need
pip install jupyter notebook pandas matplotlib

# get the files
git clone https://github.com/mbilal-OU/python_workshop.git
cd python_workshop

# start jupyter
jupyter notebook
```

then click `Python_Workshop_Biology.ipynb`.

---

## before you start

**run cells from top to bottom**
jupyter runs cells in the order you tell it to.
if you skip cells, later ones might fail because earlier code never ran.
if things break, go to Kernel > Restart & Run All.

**errors are normal**
everyone gets them. even experienced programmers. when you see a red error box,
read what it says — Python usually tells you exactly what's wrong.
the Error Reference section at the bottom of the notebook covers the most common ones.

**type the code yourself**
copy-paste works but typing it helps you remember it.
and changing values to see what happens is honestly the best way to learn.

---

## what you need installed

for most of the notebook, just Python + Jupyter is enough.

for Session 3 (pandas and plotting):

```bash
pip install pandas matplotlib
```

---

## files in this repo

```
Python_Workshop_Biology.ipynb   <- the main tutorial (start here)
data/
  example_sequences.fasta       <- sample FASTA file to practice with
  example_data.csv              <- sample growth curve data
README.md
requirements.txt
```

---

## questions?

if something doesn't make sense, ask in class.
if you find a mistake, let me know.

good luck :)
