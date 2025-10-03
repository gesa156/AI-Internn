# AI-Internn

I developed a machine learning model to classify emails as "spam" or "ham" (non-spam). The project was built using the "Spam or Not" dataset from Kaggle, which can be found here: "https://www.kaggle.com/datasets/lightningforpython/spam-or-not"

My motivation for choosing this topic stems from a strong interest in cybersecurity. Filtering spam is a fundamental and practical application within this field, as it serves as a first line of defense against phishing, scams, and malware.

I began by loading the dataset and then focused on cleaning the text data, which involved removing unnecessary elements like special characters, and common stop words to prepare it for effective analysis. To understand the data's characteristics, I performed an exploratory data analysis. This included looking at the count of samples per category, identifying the most frequent words, and examining category-specific words to see what vocabulary typically distinguishes spam from ham.

For the training part, I chose the Naive Bayes algorithm due to its proven effectiveness and high accuracy in text classification problems, particularly for distinguishing between spam and ham emails. Naive Bayes works by calculating the probabilities of word occurrences in a specific category, based on the assumption of conditional independence between words. This makes it suitable for fast and accurate text analysis, such as emails, where word patterns clearly differ between categories. After training the model, I created a simple prediction function that allows users to input new email text and receive a response indicating whether it is "spam" or "ham." This function demonstrates the practical utility of the system and its ease of use.

Finally, I evaluated the model's performance by assessing its accuracy and other key metrics. To ensure I had chosen the best approach, I compared several models commonly used with this dataset. Through this comparison, I confirmed that the Naive Bayes model delivered superior performance for this specific task, making it the best choice for our spam classification system.

You can directly open it in Colab from GitHub.
