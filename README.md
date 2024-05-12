# Sentiment Analysis on Reddit Data using ClinicalBERT

## Introduction

This project employs sentiment analysis on Reddit posts and comments related to diabetes using ClinicalBERT. By fine-tuning this pre-trained model, we aim to gauge community sentiment, especially concerning clinical trials. Additionally, personalized messages are generated based on sentiment analysis results.

## Setup Instructions:

1. **Generate Reddit API Credentials:**
   Obtain API credentials from Reddit and replace them in the code.

2. **Replace OpenAI API Key and Organization:**
   Obtain an API key from OpenAI and specify your organization details in the code.

3. **Accessing Datasets and Models:**
   All datasets and pre-trained models are included in the provided folder.

4. **Running the Code:**
   Simply run the provided notebooks after setting up credentials and dependencies.

## Methodology:

- **Data Collection:** Gathered posts and comments using relevant keywords.
- **Labeling Data:** Utilized VADER sentiment analysis for labeling.
- **Model Fine-Tuning:** Fine-tuned ClinicalBERT using labeled data.
- **Sentiment Analysis:** Applied the model to diabetes subreddit data.
- **Message Generation:** Crafted personalized messages for positive sentiments.

## Challenges:

1. **Unlabeled Data:** Overcame by employing VADER for labeling.
2. **Model Training Time:** Addressed due to ClinicalBERT's complexity.
3. **Interdependencies:** Handled through iterative development and experimentation.

## Examples:

- **Data Collected:** Sample post from Clinical Trials subreddit.
- **Analysis Performed:** Sentiment analysis results.
- **Messages Generated:** Personalized messages for clinical trials enthusiasts.

## Ethical Considerations:

1. **Privacy and Data Usage:** Ensured compliance with Reddit's policies.
2. **Bias Mitigation:** Mitigated biases to ensure fair representation.
3. **Consequences of Messaging:** Ensured messages were accurate and respectful.

## Conclusion:

This project showcases the power of sentiment analysis in understanding community attitudes towards diabetes and clinical trials on Reddit. Despite challenges, it provides actionable insights and encourages community engagement.

