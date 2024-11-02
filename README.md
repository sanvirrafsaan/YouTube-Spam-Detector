# YouTube-Spam-Detector
Detection of YouTube Spam Comments

**Overview**
YouTube, with its vast reach and billions of daily interactions, serves as a significant platform for information and entertainment. However, this popularity has attracted spammers, who post irrelevant or promotional comments that disrupt user experience. The objective of this project is to develop an automated classifier that accurately flags spam comments, improving the quality of interactions on YouTube videos. This project leverages natural language processing techniques and machine learning to identify spam comments with a high degree of accuracy.

**Project Highlights**

Objective: To classify YouTube comments as "spam" or "non-spam" to improve content quality on the platform.
Dataset: Kaggle dataset containing 1369 labeled YouTube comments, present in file test.csv
Approach: Text-based feature engineering using TF-IDF and Logistic Regression model to achieve a high-performance classifier.

**Methodology**

Data Preprocessing
- Verified dataset integrity by checking for missing values—none were found, ensuring a clean start.
- Leveraged TF-IDF vectorization to convert comment text into numerical feature vectors, capturing term relevance and frequency while reducing dimensionality. This approach produced a vocabulary of 2821 unique words.
- Feature Engineering with TF-IDF
- Utilized the TF-IDF (Term Frequency-Inverse Document Frequency) vectorizer to transform each comment into a meaningful vector representation
  
**Model Development**
- Model: Logistic Regression, chosen for its simplicity, interpretability, and effectiveness in binary classification tasks.
- Training and Testing: Split the data into 80% training and 20% testing sets to ensure robust model evaluation.
- Performance: Achieved 97% accuracy on the test set, demonstrating high model effectiveness in identifying spam comments.
- Real-Time Prediction Capability
- Integrated a feature for user input, allowing anyone to test the model by entering custom text to receive an instant spam or non-spam prediction.
  
**Results**

The model attained a 97% accuracy, signifying strong predictive performance. This high accuracy indicates that the TF-IDF-based Logistic Regression model is proficient in distinguishing between legitimate comments and spam, even in the diverse and noisy environment of YouTube comment sections.

**Key Learnings**

Feature Selection for Text Data: Understanding how different text representations, such as TF-IDF, enhance model performance was crucial to this project.
Model Optimization: Balancing simplicity with effectiveness led to the selection of Logistic Regression, which provided both interpretability and strong performance.
Interactive Prediction: Adding an input feature for real-time predictions improved the user experience and made the model more versatile.
Conclusion

This project demonstrates a practical application of NLP and machine learning in social media moderation. The resulting classifier can be easily adapted for real-world spam detection systems and enhanced with additional layers, such as deep learning models or ensemble techniques, for further improvement.

**Future Directions**
- In the Future, I plan to experiment with more advanced techniques such as word embeddings or transformer models to capture semantic nuances in comments.
- I will also work on extending the project to handle multi-label classification (e.g., offensive content, irrelevant content, etc.) for more comprehensive comment moderation.
