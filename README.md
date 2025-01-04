# Relativity-Project-Bias-Evaluation-in-GeminiAPI

This project explored the potential harms of generative AI within the justice system by identifying biases in frontier AI models. Our goal was to understand how these biases influence text analysis, particularly when evaluating sensitive attributes such as age, ethnicity, and religion. Recognizing and addressing these biases is critical to ensuring fairness and mitigating harm in AI-driven decision-making.

We used Amazon's Generalized Fairness Metrics dataset as the foundation, incorporating template sentences designed to highlight biases in sentiment classification.
Sentences were categorized by sentiment—positive, neutral, and negative—and combined with identity-specific terms across the groups.

The prepared dataset was fed into the Gemini API to classify sentences as positive, neutral, or negative. The sentiment classification was analyzed to determine whether specific identity terms influenced predictions.

