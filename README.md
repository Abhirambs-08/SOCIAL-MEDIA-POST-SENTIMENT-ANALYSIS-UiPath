# SOCIAL MEDIA POST SENTIMENT ANALYSIS
## ABSTRACT

In today's digital era, social media platforms like Twitter have become essential sources of public opinion and sentiment on various trending topics. Analyzing these sentiments is crucial for individuals, businesses, and organizations to make data-driven decisions. However, manually collecting, processing, and analyzing social media data is time-consuming and prone to errors. This project leverages robotic process automation (RPA) using UiPath Studio combined with artificial intelligence (AI) via ChatGPT to automate the sentiment analysis of Twitter posts.

The system begins with a user-friendly input dialog box, where users provide the name of a trending topic. Using UiPath’s browser automation capabilities, the system retrieves the latest Twitter posts related to the topic by interacting with Google and Twitter’s web interface. An Extract Table activity is employed to capture the post content, which is then preprocessed using activities like For Each Row in DataTable and Assign. Preprocessing involves cleaning the text to remove emojis, special characters, and non-English content, ensuring the data is in an analyzable format.

For sentiment analysis, the system employs ChatGPT by automating interactions with its web interface. Using Type Into, Click, and Get Text activities, the processed text is sent to ChatGPT with a relevant prompt, and the AI-generated sentiment output is captured. The final sentiment—categorized as positive, negative, or neutral—is displayed to the user via a message box.

This system demonstrates the seamless integration of RPA and AI to perform real-time sentiment analysis, making it a powerful tool for market research, political analysis, customer feedback evaluation, and more. By automating repetitive tasks and utilizing advanced AI capabilities, the project minimizes human intervention, enhances efficiency, and ensures accurate sentiment extraction. Future extensions of the project could involve API-based data retrieval for improved performance and scalability.

## Problem Statement
Analyzing public sentiment on Twitter poses several challenges due to the nature of the platform and its data. The vast volume of real-time tweets makes manual analysis impractical and time-consuming. Additionally, Twitter posts often contain emojis, slang, abbreviations, and non-English content, requiring substantial preprocessing to extract meaningful insights. Current methods of sentiment analysis often involve complex machine learning models or manual workflows, which are either resource-intensive or susceptible to human error. These challenges hinder the effective use of Twitter data for sentiment analysis, creating a need for an automated system that integrates data extraction, cleaning, and analysis into a seamless process.

## Objectives
The primary objectives of this project are as follows:

 - Automate Data Retrieval: Enable the system to automatically collect the latest Twitter posts related to a user-provided trending topic using UiPath Studio.

 - Preprocess Data: Develop a preprocessing pipeline to clean the extracted data by removing emojis, special characters, and non-English text.

 - Perform Sentiment Analysis: Integrate ChatGPT to analyze the cleaned Twitter data and determine its sentiment.

 - Provide User-Friendly Output: Display the sentiment results in a concise and clear format, ensuring the system is accessible to non-technical users.

 - Enhance Efficiency: Minimize human intervention by automating repetitive tasks, reducing time and effort.
