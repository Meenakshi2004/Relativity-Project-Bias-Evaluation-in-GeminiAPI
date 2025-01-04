# Relativity-Project-Bias-Evaluation-in-GeminiAPI

This project explored the potential harms of generative AI within the justice system by identifying biases in frontier AI models. Our goal was to understand how these biases influence text analysis, particularly when evaluating sensitive attributes such as age, ethnicity, and religion. Recognizing and addressing these biases is critical to ensuring fairness and mitigating harm in AI-driven decision-making.

We used Amazon's Generalized Fairness Metrics dataset as the foundation, incorporating template sentences designed to highlight biases in sentiment classification. The sentiment classification was analyzed to determine whether specific identity terms influenced predictions. Sentences were categorized by sentiment—positive, neutral, and negative—and combined with identity-specific terms across the groups. The leveraged tools were Gemini API, Google Colab, and Python (with Sci-Kit and Panda libraries). 

Ideally, Gemini should have the same sentiment no matter what term is plugged into the template for it to be unbiased. 

However, the inconsistencies revealed that biases in AI models stem not only from their architecture but also from limitations in the dataset. Addressing these biases requires contextually rich data. We concluded the data was ineffective at actually detecting bias, given the weakness of the dataset. 




