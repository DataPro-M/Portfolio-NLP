# DataPro 
__An Aspiring Data Scientist__

## [Project 1: Student Plagiarism Detection](https://github.com/DataPro-M/66daysofdata_NLP/tree/main/day21)

<img src="https://user-images.githubusercontent.com/79440491/142719095-89ebeebe-8689-4b3d-9ba3-291f0f7ab0cb.png"  height="350"/>


To score ratings, this project ran student work through a language model that was trained on original text data.
A higher score indicates that the work is more predicted based on the training data, and therefore it is more likely to be plagiarized. 
* **Python libraries used:** nltk, pandas, scipy
* **Input:** A Corpus of Plagiarised Short Answers
* **Output:** Plagiarism Detector model

<img src="https://user-images.githubusercontent.com/79440491/142719104-da9892d3-5f6c-4612-9c8c-f6153e6e3989.png"  height="350"/>

<img src="https://user-images.githubusercontent.com/79440491/142719118-c348ccac-b956-48b5-a93e-99da5be3544e.png"  height="350"/>

> The plagiarized words are represented by the darker colored pixels.
> This approach allows determining whether sections of a document have been plagiarized much easier.

`Containment score:` a plagiarism similarity measurement

<img src="https://user-images.githubusercontent.com/79440491/142719149-124db61a-2b07-458f-b869-5876808029fe.png" /> 

`Longest Common Subsequence` a plagiarism similarity measurement

<img src="https://user-images.githubusercontent.com/79440491/142719156-3956a311-225c-4131-b74c-8c5c47d2c1eb.png" /> 

_**Note:** The most difficult type of plagiarism to identify is `heavy answers`, which are based on the original material but heavily rewritten._

### `Multi-class Classification`
![image](https://user-images.githubusercontent.com/79440491/142719050-8292d8db-c8fe-4182-8270-065bab619471.png)
![image](https://user-images.githubusercontent.com/79440491/142719056-a79294c6-4156-4e30-9aa7-e6d1348028dc.png)
![image](https://user-images.githubusercontent.com/79440491/142719057-7dd01f0d-a3e1-4e05-a701-1fc4ad1c84e8.png)






