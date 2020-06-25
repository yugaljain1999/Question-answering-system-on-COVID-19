# Question-answering-system-on-COVID-19
This repository is focussing on question answering system based on research articles related to COVID-19. I was working on this project with my friend, he collected 20,000 research articles on COVID-19 and then preprocessed that data. Further, I have applied BM25 cosine similarity to extract top 10 documents according to given context and query. And, then we applied sci-bert which is basically language pretraining model to analyze scientific or bio-medical dataset. As we had bio-medical dataset, so we gone with sci-bert because it can easily understand embeddings of bio-medical or scientific dataset rather than using simple BERT-MODEL.

# How to run this repo?
1. Clone the repository.
2. Download data from [here]('https://drive.google.com/file/d/1Swdd9D5KfBrkTPv9yJZl_T-Rr9eRu8mg/view?usp=sharing') and store it in cloned repository.
3. Run this command: pip install requirements.txt
4. Run Notebook1 and then Notebook2 
5. Finally, you will get answer related to given context and a query.

Feel free to contribute , and if you like it, click on star button.
Looking forward to add a unsupervised way to generate question-answers from a paragraph instead using labelled data, because of high label cost.
