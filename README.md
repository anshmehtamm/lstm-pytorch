# News Category Classifier
 Categorizing news topics using different ML techniqiues (extension for NewsSwipe app). A self project to learn in depth about machine learning, its pitfalls, why the architectures are designed the way they are, and how to improve them.

## Description
This project is an extension for the NewsSwipe app I built in January 2024. (checkout the app [here](https://appetize.io/app/bi3tse7tgin6xi63n46ywxikrq?device=iphone14pro&osVersion=17.2)). The main goal of this project is to categorize news articles into different categories. (e.g. sports, politics, technology, etc.) 


I'm using different machine learning techniques and deep learning to achieve this goal. 

I've only implemented a simple RNN model and a LSTM model from scratch (using only pytorch) till now, and achieving accuracy of 83% and 86% respectively on the test dataset.

*[Currently: Investigating RNN and LSTM, what is the pitfall to learning in the current implementation]*

Planning to implement more complex models and techniques in the future while investigating the pitfalls of each model and documenting them.

Planned models:
- BERT
- GPT

## LSTM Model (crux)
#### Initialization
![Screenshot 2024-12-09 at 10 06 13 PM](https://github.com/user-attachments/assets/79b16b9b-c04a-488b-8003-7ea0fa463aa1)
#### Training Loop
![Screenshot 2024-12-09 at 10 06 21 PM](https://github.com/user-attachments/assets/2148118a-011b-41f6-8d19-6b84ca2a3973)



## Dataset

The dataset used for this project is the "AG News" dataset. It is a collection of news articles from the AG's corpus of news articles on the web. The dataset contains 120,000 training samples and 7,600 testing samples from 42 different classes. 

The dataset can be found [here](https://www.kaggle.com/amananandrai/ag-news-classification-dataset), in which orignal authors implemented a ConvNet on character-level inputs. The paper can be found [here](https://papers.nips.cc/paper_files/paper/2015/file/250cf8b51c773f3f8dc8b4be867a9a02-Paper.pdf).

## Requirements
- Python 3.6+
- Pytorch
- Numpy


