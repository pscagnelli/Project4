# Code Review

[X] README.md included

[ ] Slides NOT included

[X] Code included

## Clean Code:

* Code needs some brush up: try to place all libraries on top of the notebook, add structure and remove redundant/duplicated library imports. Also, try not to reassign variables (e.g. **geniusCreds**) multiple times. 
* Probably the easiest thing to do to clean up code a little bit is to remove a bunch of cells that do not serve any purpose in the final analysis and were needed to draft solutions
* To further increase readability of the functions you can include docstrings to explain the purpose, input and output of the function, package helper functions into a separate .py file or organize them on top of the notebooks. As you are reusing the same functions across several notebooks, it makes sense to package them in a .py file. I was not sure if billboard is a local .py file missing or the external library that you used somewhere - it is helpful if the goal of importing the library is stated for rare or specific libraries. 
* If the documents are not very short, avoid putting the contents of the whole document as an index into your document-topic matrix. consider adding an ID, etc.


## Project Documentation

* There are a few things that can be done to add a little more color to the README.md file: you can add structure, headings, bold/italics. Adding the link to the API you refer to should look good as well. 
* A big part of README.md is to give a summary of the analysis: a conclusion and a set of supporting evaluation metrics.
* Consider explaining the progression from one notebook to another - you can use informative file names or write out the structure in the README.md file. Also, consider using Markdown cells and - maybe - a few inline comments to explain the logic of your code, especially in the modeling part - to explain the choice of methods (why you do NMF, why you ) and hyperparameters (e.g. number of topics).

## Proper Data Science

* Consider doing some high-level EDA to get the feel of the data, even some basic stuff like a bar chart of songs per genre is super helpful. Visualizations are generally a great addition to an NLP projects be it a simple EDA or visualizing topic clusters in a lower dimensional space.
* It is helpful to add some analysis of topics you came up with - it can be just naming the topics or using metrics such as topic coherence. It seems you are doing analysis per artist - what is the data science question you want to answer - it is great to see this train of thought in the notebook.
