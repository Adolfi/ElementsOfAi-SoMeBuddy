# Project Title
SoMe Helper

![image of a cat](/somehelper.png)

## Summary
**SoMe Helper** is an AI-powered tool that helps marketing professionals predict the performance of social media campaigns before publishing. By leveraging historic campaign data, it estimates potential engagement and provides real-time suggestions for optimizing posts — such as changing images, wording, or hashtags — to improve reach and interaction.

## Background
Marketing teams often launch social media campaigns without knowing how well they'll perform, leading to missed opportunities and inefficient spending. This is a common problem across industries where social presence is vital. SoMe Helper aims to bring data-driven predictability to campaign planning, saving time and boosting impact. With social platforms becoming increasingly crowded and competitive, having an edge through AI-backed insight is more important than ever.

## Data and AI techniques
The solution is based on historical data from previous social media campaigns — including metrics such as likes, comments, shares, reach, and posting time. This data is used to train models to predict performance metrics and suggest improvements.

Key techniques include:

- **Natural Language Processing (NLP)** for caption and hashtag analysis
- **Computer Vision** for image content tagging
- **Random Forest**: Ideal for handling high-dimensional, mixed-type datasets (e.g., categorical + numeric) and for identifying important features like hashtags, post timing, and visual elements that influence engagement.
- **XGBoost**: Known for its high accuracy and efficiency, XGBoost handles sparse data and overfitting well, making it suitable for modeling real-world campaign variability and complex non-linear relationships.
- **Reinforcement learning**: To enable the model to continuously improve based on user feedback and evolving platform behavior.

An interactive frontend allows users to tweak input (image/text) and get updated predictions instantly.

## How is it used
SoMe Helper is used by marketing and content teams as part of their campaign preparation workflow. Before going live, users input a draft post and receive an estimated performance score, along with actionable tips to enhance it. The tool is designed to be intuitive, providing real-time feedback that supports both seasoned marketers and junior social media managers.

## Challenges
SoMe Helper doesn't solve all issues around social media success. It can’t account for sudden trends, external events, or platform algorithm changes in real time. Data bias (e.g. limited campaign types or demographics) can affect prediction accuracy. Also, creative content may outperform predictions due to virality or novelty — something difficult to capture in historical data alone.

## What next
Future development could include:
- Integration with live A/B testing to refine predictions
- Support for more platforms (e.g., TikTok, LinkedIn)
- Deeper sentiment analysis and audience targeting suggestions
- Multilingual capabilities for global campaigns
- Personalization based on brand tone and historical user performance

## Acknowledgments
This project is inspired by real-world needs observed in digital marketing and content creation. We also took inspiration from AI project examples in the [Building AI course by University of Helsinki](https://buildingai.elementsofai.com/Conclusion/ai-idea-gallery).
