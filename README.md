# Python Practice

A collection of Jupyter notebooks for students to practise Python for scientific computing. Each notebook covers one topic: short explanations and runnable examples first, then exercises to try on your own.

New notebooks will be added over time.

## Notebooks

| Notebook | Topic |
|---|---|
| [`numerical_plotting_student.ipynb`](numerical_plotting_student.ipynb) | Plotting functions numerically with numpy and matplotlib |

## Getting started

**Option 1: Google Colab (nothing to install)**

1. Go to [colab.research.google.com](https://colab.research.google.com) and choose *File → Open notebook → GitHub*.
2. Paste this repository's URL and pick a notebook.
3. Choose *File → Save a copy in Drive* before you start, so your work is saved to your own account.

**Option 2: Run on your own computer**

```bash
git clone https://github.com/kaeonikc/python_practice.git
cd python_practice
pip install numpy matplotlib jupyter
jupyter notebook
```

You can also open the `.ipynb` files in VS Code with the Jupyter extension.

## How to work through a notebook

- Run the cells in order from top to bottom. Later cells often use variables created earlier.
- Read each example, run it, then change a value and run it again to see what happens.
- Some exercises have a checking cell below them that prints ✅ or ❌. Run the helper cell at the start of the exercise section first.
- Some exercises ask you to reproduce a figure shown above the code cell.
- Written answers go in the markdown cells marked for you to double-click and type in.
- If something breaks, try *Kernel → Restart & Run All* (in Colab: *Runtime → Restart and run all*).

## About this material

These notebooks were created by the instructor with help from [Claude](https://claude.ai), an AI assistant made by Anthropic. Claude helped with:

- **Designing the exercises:** choosing what each exercise practises, putting them in order from easy to challenging, and writing the answer-checking cells.
- **Writing the teaching content:** explanations, example code and the target figures students reproduce.

## Author

Chakkrit, Chiang Mai Rajabhat University (CMRU)
