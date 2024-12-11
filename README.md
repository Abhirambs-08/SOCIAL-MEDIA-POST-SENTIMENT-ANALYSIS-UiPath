# SOCIAL MEDIA POST SENTIMENT ANALYSIS
## ABSTRACT

In today's digital era, social media platforms like Twitter have become essential sources of public opinion and sentiment on various trending topics. Analyzing these sentiments is crucial for individuals, businesses, and organizations to make data-driven decisions. However, manually collecting, processing, and analyzing social media data is time-consuming and prone to errors. This project leverages robotic process automation (RPA) using UiPath Studio combined with artificial intelligence (AI) via ChatGPT to automate the sentiment analysis of Twitter posts.

The system begins with a user-friendly input dialog box, where users provide the name of a trending topic. Using UiPath’s browser automation capabilities, the system retrieves the latest Twitter posts related to the topic by interacting with Google and Twitter’s web interface. An Extract Table activity is employed to capture the post content, which is then preprocessed using activities like For Each Row in DataTable and Assign. Preprocessing involves cleaning the text to remove emojis, special characters, and non-English content, ensuring the data is in an analyzable format.

For sentiment analysis, the system employs ChatGPT by automating interactions with its web interface. Using Type Into, Click, and Get Text activities, the processed text is sent to ChatGPT with a relevant prompt, and the AI-generated sentiment output is captured. The final sentiment—categorized as positive, negative, or neutral—is displayed to the user via a message box.

This system demonstrates the seamless integration of RPA and AI to perform real-time sentiment analysis, making it a powerful tool for market research, political analysis, customer feedback evaluation, and more. By automating repetitive tasks and utilizing advanced AI capabilities, the project minimizes human intervention, enhances efficiency, and ensures accurate sentiment extraction. Future extensions of the project could involve API-based data retrieval for improved performance and scalability.