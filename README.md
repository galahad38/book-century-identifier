# Book Century Identifier

## What it does:
A classification model that predicts the century in which a book was written using Bag-of-Words algorithm (Natural Language Processing)

Sometimes GitHub is unable to Preview Code Blocks for Jupyter Notebooks. If this happens, you can just view my [Notebook](https://nbviewer.org/github/galahad38/book-century-identifier/blob/main/building-the-naive-bayes-model.ipynb).

## How to build it yourself:

1. Install [Python](https://www.python.org/downloads/):
2. Install non-standard Python libraries:
     launch command prompt and run this command:
     ```console
     C:\Windows\system32\ pip install ipykernal, jupyterlab, notebook, numpy, pandas, scikit-learn
     ```
3. Download the [dataset](https://github.com/galahad38/book-century-identifier/blob/main/books_db.csv) and [Jupyter Notebook](https://github.com/galahad38/book-century-identifier/blob/main/building-the-naive-bayes-model.ipynb). Ensure that they are in the same folder.
4. Launch Jupyter Notebook from the Start Menu, and navigate to the folder containing the dataset and Jupyter Notebook you just downloaded.
5. Go to Cell -> Run All.
6. Profit!

## How to interpret it:
The final score.mean() tells you how good of a model it is. The closer this value is to 1, the better the predictive power of the model.
In other words, the closer the value is to 1, the more accurately the model is able to predict the Century in which the text was written, based on the grammatical structure, vocabulary, and grammar.

## My instance and the insights derived:
I got a Weighted F1 Score of 81.6%. This is not bad, but also I would like to get this number to be as high as I can, so there is definitely scope for improvement.

## Future Scope:
I am satisfied with the outcome of this project. However it is simplistic and undoubtedly a prototype with huge scope for improvement:
1) I can more programmatically source my data, say by downloading all of the books available on [Project Gutenberg](https://www.gutenberg.org/).
2) I can clean the data a bit better, and perform Feature Selection in order to remove words without dictionary meaning.
3) When creating the Document-Term Matrix, I can also incorporate N-Grams as features.
4) I can implement a way for the user to input some text data and obtain a predicted Century value, making it actually usable and not just an object of curiosity.
