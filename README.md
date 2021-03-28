# Hidden Markov Model

The main goal fo this project is to generate new text and predict based on the sequence of words within the dataset.

## Datasets:
For this project, I have used Shakespeare plays dataset. These datsets can be found in the Data sub folder. Below is the link provided:

[Shakespeare-plays](https://www.kaggle.com/kingburrito666/shakespeare-plays)

## Algorithms:
For this project, I have implemented the Hidden Markov Model.

## Explanation:
The implementation for this algorithm is located in the Notebooks folder.

## Hidden Markov Model:
The shakespeare dataset is loaded into pandas and cleaned, each line is tokenized. First and Second order markov chains are built based on tokens. A function written to generate new text based on the words given and another function to predict the text given sequence of words. Hidden Markov Model is memoryless, hence we can observe from the result that the generated text has no meaning or is baseless. It doesn't remember the historical data of past states, considers only previous state.

## Steps to execute:
1. Download the files from the github repository.
2. Get the allines.txt by unzipping the .zip file.
3. Place the file in data folder and place the data folder in notebooks folder. The notebooks folder should also have ipynb file as well.
4. Navigate to terminal and type "jupyter notebook"
5. Navigate to the folder where the notebooks are placed.
6. From the menu icon cell, select the notebook and click on Run all which will run the whole notebook from the first cell.

## Steps to follow:
Probabilistic states and transitions

1. Set up a new git repository in your GitHub account
2. Pick a text corpus dataset such as https://www.kaggle.com/kingburrito666/shakespeare-plays or from https://github.com/niderhoff/nlp-datasets
3. Choose a programming language (Python, C/C++, Java)
4. Formulate ideas on how machine learning can be used to learn word correlations and distributions within the dataset
5. Build a Hidden Markov Model to be able to programmatically
        1. Generate new text from the text corpus
        2. Perform text prediction given a sequence of words
6. Document your process and results
7. Commit your source code, documentation and other supporting files to the git repository in GitHub

### References:
https://medium.com/ymedialabs-innovation/next-word-prediction-using-markov-model-570fc0475f96 </br>
https://towardsdatascience.com/introduction-to-hidden-markov-models-cd2c93e6b781 </br>



