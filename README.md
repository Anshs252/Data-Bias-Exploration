# Data-Bias-Exploration
This project employed the Google Perspective API to assess the accuracy of toxicity detection in gender-specific swear words, comparing common and less common terms directed at males and females to understand AI moderation nuances.

## Hypothesis
My hypothesis was that male-directed common swear words would have the highest accuracy in terms of being identified as toxic by the Google Perspective API.

## Test Cases
To test this hypothesis, the analysis was structured into four categories:

#### Male-Directed Common Swear Words: Commonly used derogatory terms directed towards males.
#### Male-Directed Less Common Swear Words: Less frequently used or milder derogatory terms directed towards males.
#### Female-Directed Common Swear Words: Commonly used derogatory terms directed towards females.
#### Female-Directed Less Common Swear Words: Less frequently used or milder derogatory terms directed towards females.

For each category, a list of sentences was prepared and analyzed using the Google Perspective API. Each sentence was evaluated for toxicity, and the results were aggregated to calculate the accuracy of toxicity detection for each category.

## Results 
#### Male-Directed Common Swear Words: 90% accuracy
#### Male-Directed Less Common Swear Words: 33.33% accuracy
#### Female-Directed Common Swear Words: 70% accuracy
#### Female-Directed Less Common Swear Words: 20% accuracy
These results indicate that the API was most effective at identifying toxicity in male-directed common swear words, aligning with the initial hypothesis.

## Biases
There are potential biases in this analysis that need to be acknowledged:
#### Selection Bias: 
The sentences chosen for each category may not comprehensively represent the range of common and less common swear words. The selection is subjective and might influence the results.
#### API Bias: 
The Google Perspective API itself may have inherent biases in how it evaluates toxicity. These biases can arise from the training data used for the API's machine learning models.
#### Contextual Limitations:
The API might not fully understand the context of each sentence, leading to potential misclassifications. This is especially true for sentences where the toxicity might be more nuanced.
## Insights
Based on the analysis, here are some key insights:

#### Accuracy Comparison: 
The results show how accurately each category was identified as toxic by the API. This gives an indication of which types of sentences are more likely to be flagged as toxic.
#### Hypothesis Validation: 
The accuracy rates obtained for each category can confirm or refute the hypothesis. If male-directed common swear words have the highest accuracy, the hypothesis holds. Otherwise, it indicates a different trend.
#### Understanding API Sensitivity:
The differences in accuracy between categories can shed light on how sensitive the Google Perspective API is to different types of derogatory language. It can highlight whether the API is more attuned to common swear words or whether the rarity or mildness of terms influences its detection capability.
#### Gender-Specific Language Analysis: 
The analysis can also provide insights into how gender-specific language is treated by automated moderation tools, highlighting potential areas for improvement in ensuring fairness and neutrality.
This report gives an overview of the analysis conducted, with the data-driven insights offering a deeper understanding of the performance and potential biases of AI-driven content moderation tools.
#### Future Directions: 
For future improvements, expanding the dataset and incorporating a wider variety of linguistic expressions could yield a more comprehensive analysis. Investigating cross-linguistic and cultural contexts in future studies might enhance understanding of AI moderation's effectiveness and biases, paving the way for more equitable AI tools.
