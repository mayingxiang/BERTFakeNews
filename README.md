# Fake News Detection with BERT

![download](README.assets/download.jpeg)

Video recording of the overview: https://youtu.be/yVEhmXw2xYQ

## Introduction

### Why should people care about whether a piece of news is fake?

- **You deserve the truth.** You are smart enough to make up your own mind - as long as you have the real facts in front of you.
- **Fake news destroys your credibility**. If your arguments are built on bad information, it will be much more difficult for people to believe you in the future.
- **Fake news can hurt you**, and a lot of other people. Purveyors of fake and misleading medical advice like Mercola.com and NaturalNews.com help perpetuate myths like vaccines cause autism and HIV and AIDS aren't related. These sites are heavily visited and their lies are dangerous.
- **Real news can benefit you**. For example, if you are planning on voting in an election, you want to read valid and factual information on a candidate so you can vote for the person who best represents your ideas and beliefs.

### What is BERT?

BERT, which stands for Bidirectional Encoder Representations from Transformers, is a transformer model in which every output element is connected to every input element, and the weightings between them are dynamically calculated based upon their connection. Historically, language models could only read text input sequentially -- either left-to-right or right-to-left -- but couldn't do both at the same time. BERT is different because it is designed to read in both directions at once. This capability, enabled by the introduction of Transformers, is known as bidirectionality. 

### Goal of the project

Develop an application that can binarily detect Fake News using BERT Model and Pythorch.



## Pipeline

![Screenshot 2022-12-07 at 4.47.41 AM](README.assets/Screenshot%202022-12-07%20at%204.47.41%20AM.png)

### Dataset 

![Screenshot 2022-12-07 at 5.18.38 AM](README.assets/Screenshot%202022-12-07%20at%205.18.38%20AM.png)

Source: https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset



### Steps to implement Trasfer learning

![Screenshot 2022-12-07 at 5.06.13 AM](README.assets/Screenshot%202022-12-07%20at%205.06.13%20AM.png)



### Model fine-tuning

![Screenshot 2022-12-07 at 4.54.52 AM](README.assets/Screenshot%202022-12-07%20at%204.54.52%20AM.png)

**Freeze the entire architecture** and add a few neural network layers. Train the new model.



### Model Performance

![Screenshot 2022-12-07 at 5.20.51 AM](README.assets/Screenshot%202022-12-07%20at%205.20.51%20AM.png)



## Next Steps

* Develope a Multi-Class Classifier to classify news articles into sub-categories.

* Increase the number of epochs while trainning the model.

  

## Relevant Links

[1] Fake news detection using parallel BERT deep neural networks. https://doi.org/10.48550/arXiv.2204.04793

[2] Fake News Detection Using BERT Model with Joint Learning. https://link.springer.com/article/10.1007/s13369-021-05780-8

[3] Fake News Detection using BERT Model Python. https://towardsai.net/p/l/fake-news-detection-using-bert-model-python

[4] BERT Model for Fake News Detection Based on Social Bot Activities in the COVID-19 Pandemic. https://ieeexplore.ieee.org/document/9666618

[5] Fake News: Develop Your Fact. https://researchguides.ben.edu/c.php?g=608230&p=4219917