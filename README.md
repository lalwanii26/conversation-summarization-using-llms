# Conversation Summarization with Large Language Models

## Project Overview
This project implements a conversational AI that uses Google’s T5 model as an "expert" over BART, the "generator," to enhance Chain of Thought capabilities. The model is trained and evaluated on the SAMSUM Dataset, aiming to improve the interpretability and efficiency of automatic conversation summarization.

![alt text]([https://github.com/lalwanii26/Cryptography/blob/main/images/RSA%20Trials.png?raw=true](https://github.com/lalwanii26/conversation-summarization-using-llms/blob/main/figures/figure1.png))

## Key Features
- **Chain of Thought Prompting**: Leveraging the T5 model to guide the BART generator through complex reasoning paths.
- **Evaluation Metrics**: Utilizes ROUGE-1, ROUGE-2, and ROUGE-L for performance assessment.

## Model Architecture
### Expert (T5)
- Description of the model configuration, training details, and role as an "expert".

![alt text]([https://github.com/lalwanii26/Cryptography/blob/main/images/RSA%20Trials.png?raw=true](https://github.com/lalwanii26/conversation-summarization-using-llms/blob/main/figures/figure3.png))

### Generator (BART)
- Description of the model configuration, training details, and role as a "generator".

![alt text]([https://github.com/lalwanii26/Cryptography/blob/main/images/RSA%20Trials.png?raw=true](https://github.com/lalwanii26/conversation-summarization-using-llms/blob/main/figures/figure2.png))

## Dataset
The SAMSUM Corpus involves short message summarization, aimed at transforming dialogues into concise summaries.

![alt text]([https://github.com/lalwanii26/Cryptography/blob/main/images/RSA%20Trials.png?raw=true](https://github.com/lalwanii26/conversation-summarization-using-llms/blob/main/figures/figure4.png))

![alt text]([https://github.com/lalwanii26/Cryptography/blob/main/images/RSA%20Trials.png?raw=true](https://github.com/lalwanii26/conversation-summarization-using-llms/blob/main/figures/figure5.png))

## Results
- **ROUGE-1**: 47.8
- **ROUGE-2**: 24.38
- **ROUGE-L**: 40.3933

## Significance and Novelty
- Earlier models do not utilize the long-range memory capabilities of large language models. This causes the outputs generated from these models to suffer from problems like hallucinations and catastrophic forgetting. And even though past approaches achieved great results on many downstream tasks, improving the interpretability of the underlying models remains a major challenge.
- Our approach aims to tackle these problems by introducing the chain-of-thought capability to the model which also helps to improve the model
