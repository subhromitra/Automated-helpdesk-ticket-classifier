# Automated helpdesk system

## Project description :

This project is about building an automated helpdesk system for reducing the speed of customer service time & increasing efficiency of workflow. 

### What is a helpdesk ?
A help desk, in the context of IT, is a department inside an organization that is responsible for answering the technical questions of its users. Most major IT companies have set up help desks to respond to questions from their customers. The questions and their answers are usually transferred using e-mail, telephone, website, or online chat. Additionally, there are internal help desks aimed at offering the same form of help, but only for the employees within the organization.

### How can Machine learning help ?

Machine learning can help in finding patterns in the text from complaints filed. These patterns help in classifying the tickets without any human intervention.

### Dataset :-

The dataset can be found here: https://privdatastorage.blob.core.windows.net/github/support-tickets-classification/datasets/all_tickets.csv

**Note :-** All labels have been made anonymous by the dataset providers.

### Task :-

Classify category, urgency & impact of a customer complaint.

### Project Workflow :-

The general workflow for this project is visualized using the following pic :-

![workflow image](https://raw.githubusercontent.com/subhromitra/Automated-helpdesk-ticket-classifier/master/workflow.JPG)

**Tokenization :-** Splitting sentences (string) to sequence of words (list)

**Text Normalization (expansion) :-** Expanding words like I'm to I am , wouldn't to would not. 

**Lemmatization :-** Converting words back to their root form , e.g :- better converted to good , geeze converted to good. This is done to reduce no.of unique tokens without distorting info conveyed by the sentence.

### Prerequisites:

```
* Numpy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Keras (Tensorflow backend)
* Jupyter notebook
```
Download the zip file, extract the .ipynb files & run the files. 


