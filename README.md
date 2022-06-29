# Event Detection
## Event Causality Detection using NLP Techniques
### Semester Project Report Spring 2022


## Description
We are working on the SemEval-2010 task 8 challenge for the classification of the entity pairs. An event is expressed as a sentence involving keywords and actions related to those keywords. The input sentences are marked with target entities e1 and e2. For instance, given a sentence, S: "The financial <e1>crisis</e1> resulted in 12% <e2>unemployment<e2/> in this country", the entity pair is defined as (e1,e2). The sentences in the database are the reflections of events, which include the relationship between the entities (e1 and e2) explicitly with linguistic clues; "results in", "cause", and "because".
  
  
## KeyWords
- Relationship Classification
- Causal Relationship
- CNN+BGRU
- Simple Casual Relation
- SemEval2010 task8


## Dataset
- Reference Paper: [Knowledge-oriented convolutional neural network for causal relation extraction from natural language texts](https://www.sciencedirect.com/science/article/abs/pii/S0957417418305177#!)
- Data: [SemEval2010_task8_all_data.zip](https://drive.google.com/file/d/0B_jQiLugGTAkMDQ5ZjZiMTUtMzQ1Yy00YWNmLWJlZDYtOWY1ZDMwY2U4YjFk/view?sort=name&layout=list&num=50&resourcekey=0-k0OTSIGrF9UAcrTFfInlrw)

## Project Presentation 
  [Presentation](https://github.com/gaganjotshan/Event_Detection/blob/main/Shan%2BAgarwalla-K-NN%20and%20CATENA%20replication-Presentation.pdf)
  
  
## Project Report
  [Report](https://github.com/gaganjotshan/Event_Detection/blob/main/Shan-K-NN%20replication%20Report.pdf)
  
  
## Work Flow
- [1. Creating Training Set](https://github.com/gaganjotshan/Event_Detection/blob/main/notebooks/trainingset_1.ipynb)
- [2. Spliting Training-Validation Set](https://github.com/gaganjotshan/Event_Detection/blob/main/notebooks/split_2.ipynb) 
- [3. Pre-Processing](https://github.com/gaganjotshan/Event_Detection/blob/main/notebooks/Preprocess_3_ref.ipynb) 
- [4. Classification Model](https://github.com/gaganjotshan/Event_Detection/blob/main/notebooks/NeuralClassification_4_ref.ipynb) 
  
  
## Environment
- Python 3.7.13
- scikit-learn 1.0.0
- wget 3.2
- gensim 3.6.0
- psutil 5.4.8
- spacy 2.2.4
- keras 2.8

## Architecture
[CNN + BGRU ](https://github.com/gaganjotshan/Event_Detection/blob/main/BGRU_MEA.png)

  
### Related References:
[CATENA](https://github.com/yashagr911/catena-finall)
[Relation Classification](https://github.com/sahitya0000/Relation-Classification)
  


