# Conversation Summarization with Large Language Models

## Project Overview
This project implements a conversational AI that uses Google’s T5 model as an "expert" over BART, the "generator," to enhance Chain of Thought capabilities. The model is trained and evaluated on the SAMSUM Dataset, aiming to improve the interpretability and efficiency of automatic conversation summarization.

## Key Features
- **Chain of Thought Prompting**: Leveraging the T5 model to guide the BART generator through complex reasoning paths.
- **Evaluation Metrics**: Utilizes ROUGE-1, ROUGE-2, and ROUGE-L for performance assessment.

## Model Architecture
### Expert (T5)
- Description of the model configuration, training details, and role as an "expert".

### Generator (BART)
- Description of the model configuration, training details, and role as a "generator".

## Dataset
The SAMSUM Corpus involves short message summarization, aimed at transforming dialogues into concise summaries.

## Results
- **ROUGE-1**: 47.8
- **ROUGE-2**: 24.38
- **ROUGE-L**: 40.3933
