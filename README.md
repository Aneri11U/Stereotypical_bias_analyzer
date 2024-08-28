# **Stereotypical Bias Analyzer**

In this project, we analyzed biases across ten domains using four datasets and compiled a comprehensive dataset from publicly available sources. Models such as BERT and RoBERTa were employed to identify significant biases, underscoring the necessity of eliminating bias in natural language processing. Users can input a sentence to determine its bias types.

---

### **Stereotypical Bias**

Stereotypical bias, a pervasive cognitive phenomenon, continues to influence perceptions, decisions, and behaviors across a wide range of human interactions. Given that pre-trained language models are trained on vast real-world datasets, there is concern that these models could inadvertently incorporate and reinforce stereotypical biases.

---

### **Bias Types**

Identifiable bias types from our study & project:

The biases are labeled as follows:

- **Race/Color (0)**
- **Socioeconomic (1)**
- **Gender (2)**
- **Disability (3)**
- **Nationality (4)**
- **Sexual Orientation (5)**
- **Physical Appearance (6)**
- **Religion (7)**
- **Age (8)**
- **Profession (9)**

Enter any sentence related to these labels and check the bias type of the sentence.

<hr>

## Dataset and Model

- **Dataset:** [Bias Identification Dataset](https://huggingface.co/datasets/PriyaPatel/Bias_identification/tree/main)
- **Model:** [Bias Identification Model](https://huggingface.co/PriyaPatel/bias_identificaiton45)

<hr>

**Steps to use this website :**

1) Pip install flask
2) Download the requirement.txt
3) write Python app.py in the cmd after downloading this folder

<hr>

**Here is the algorithm for the text classification and bias detection :**

![image](https://github.com/neha13rana/Stereotypical-Bias-Analyzer/assets/121093178/d0a78462-1f29-4bee-9956-eb7fa17c8a26)

**proposed model of our project :**

Model flow :

![image](https://github.com/neha13rana/Stereotypical-Bias-Analyzer/assets/121093178/a752692e-2b02-4576-9c93-77fe29844681)

![image](https://github.com/neha13rana/Stereotypical-Bias-Analyzer/assets/121093178/977074eb-9b3e-4ff2-ba15-ee78c9597c70)

**Bias Distribution of the dataset :**

![image](https://github.com/neha13rana/Stereotypical-Bias-Analyzer/assets/121093178/f1ab7c8a-0009-4095-82d5-5a3cb315b7f1)

The test dataset yielded an impressive accuracy of 0.9832
for our bias identification model, demonstrating the model’s
effectiveness in accurately recognising instances of biases in a
variety of scenarios. This high degree of accuracy highlights
the model’s resilience and potency in identifying minute
linguistic clues that point to biases in text written in natural
language. 

Input:

![WhatsApp Image 2024-04-29 at 09 59 47_ed824d43](https://github.com/neha13rana/Stereotypical-Bias-Analyzer/assets/121093178/6dc2d597-ba27-4044-b126-1e3e0787c3f8)

Output:

![WhatsApp Image 2024-04-29 at 10 00 03_ee57b731](https://github.com/neha13rana/Stereotypical-Bias-Analyzer/assets/121093178/74f2b060-e010-49fb-b7e5-67fc43b39768)



