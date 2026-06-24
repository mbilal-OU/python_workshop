# Python Workshop for Biologists

hey everyone, welcome to the workshop materials!

this is a beginner Python course designed specifically for biology students.
no prior coding experience needed.

---

## what we cover

| session | notebook | topics |
|---|---|---|
| 0 | `00_common_mistakes.ipynb` | errors and how to fix them - read this anytime something breaks |
| 1 | `01_welcome_and_basics.ipynb` | variables, data types, strings, basic maths |
| 2 | `02_lists_and_loops.ipynb` | lists, for loops, if/else |
| 3 | `03_functions_and_dicts.ipynb` | writing functions, dictionaries |
| 4 | `04_file_handling.ipynb` | reading/writing FASTA and CSV files |
| 5 | `05_pandas_and_plotting.ipynb` | data analysis with pandas, making plots |
| 6 | `06_mini_project.ipynb` | putting it all together - build a sequence analyser |

---

## how to run these notebooks

### option 1 - google colab (no install needed, recommended)

1. go to https://colab.research.google.com
2. File > Open notebook > GitHub
3. paste: `https://github.com/mbilal-OU/python_workshop`
4. open any notebook

### option 2 - run on your own computer

```bash
# install jupyter
pip install jupyter notebook pandas matplotlib

# download the workshop
git clone https://github.com/mbilal-OU/python_workshop.git
cd python_workshop

# start jupyter
jupyter notebook
```

then click on any `.ipynb` file.

---

## recommended order

if you're completely new to Python, go in order: session 1, 2, 3, 4, 5, 6.

each session builds on the previous one.

`00_common_mistakes.ipynb` is a reference - open it whenever something breaks.

---

## a few tips

**errors are normal.** everyone gets them. even experienced programmers get errors constantly.
when you see a red error box, read what it says - Python usually tells you exactly what's wrong.

**run cells from top to bottom.** jupyter runs cells in the order you tell it to.
if you skip cells and run a later one, it might fail because earlier code never ran.
if things are behaving weirdly, go to Kernel > Restart & Run All.

**type the code yourself.** copy-paste works but you'll learn faster by typing it.
making mistakes and fixing them is how programming skills actually get built.

**change things.** once you get a cell running, try changing values and see what happens.
that's the best way to understand what the code is actually doing.

---

## what you'll be able to do after this workshop

- read and parse FASTA files
- calculate GC content, sequence length, base composition
- work with experimental data in CSV format
- filter and sort data
- make publication-quality figures
- write reusable functions
- automate repetitive tasks

---

**Muhammad Bilal**
Department of Biological Sciences, Oakland University
Rochester, Michigan, USA
