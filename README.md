# covid-19-kaggle Documentation

## Our team:
We are an international team of passionate data scientist and AI engineers at Digital Product School at the Center for Business Creation and Innovation at Technical University of Munich, Germany. [Afsane Asaei](https://github.com/afiDPS), [Anubhav Jain](https://github.com/anubhav1997), and [Diana Amiri](https://github.com/dian-ai)

## Goal:
By participating in this challenge, we hope to contribute to this global effort against Covid19 pandemic. Our aim is to provide valuable insights regarding the questions of [Task 3](https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge/tasks?taskId=567) for the doctors and researchers. We plan to do text data mining on scientific literatures. This method has been proven to be a good strategy to handle fast growing accumulation of scientific papers, which is a valid case at this moment due to the world-wide pandemic situation of Covid-19. Therefore, a sequence of steps needs to be done to find the most relative articles and snippets to the corresponding key questions. Our general approach includes feature engineering with TFIDF and PCA, topic modeling with unsupervised learning, and text classification with KNN to ease the process of finding the most relative answer.

## [Dataset description](https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge):
In response to the COVID-19 pandemic, the White House and a coalition of leading research groups have prepared the COVID-19 Open Research Dataset (CORD-19). CORD-19 is a resource of over 52,000 scholarly articles, including over 41,000 with full text, about COVID-19, SARS-CoV-2, and related coronaviruses. This freely available dataset is provided to the global research community to apply recent advances in natural language processing and other AI techniques to generate new insights in support of the ongoing fight against this infectious disease. There is a growing urgency for these approaches because of the rapid acceleration in new coronavirus literature, making it difficult for the medical research community to keep up.

## Our Approach:
* For data analysing
  - Defining influential factors based on specific features of a defined task is crucial as data grows and the complexity increases. Hence our group decided to label the provided large dataset based on the **language** of the article, if the article is related to **COVID-19**, **genomic sequence** of virus, and whether it has discussions on **receptor surface of proteins** of target virus. We believe this labeling helps us to narrow down the noise in the dataset, which means that we drop the articles that are not in this criteria, and it affects the performance of the classifier.
  <br/>
  
  
* For pre-processing