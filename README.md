# Text-Classification-ChatGPT
TF-IDF + Logistic Regression model to detect AI-generated text from human text
The project aims to address the Dead Internet Theory, which suggests that, in the future, bots
may outnumber humans on the internet—without us even realizing it. This concern has
intensified with the rapid rise of generative AI tools, making it increasingly difficult to
distinguish between human and AI-generated content.

AI-Generated Text Detection Model
The text classification model was designed to differentiate between AI-generated and
human-written text. A dataset sourced from Kaggle was used for training, consisting of labeled
text samples. The preprocessing involved converting text into numerical representations using
Term Frequency-Inverse Document Frequency (TF-IDF) vectorization. To keep the model
simple and efficient, Logistic Regression was selected as the classification algorithm,
implemented using the Scikit-Learn library. The dataset was split into training and testing sets,
and standard machine learning practices such as data normalization were applied to optimize
performance. The final model was evaluated using accuracy, precision, recall, and F1-score
metrics.
<img width="501" height="393" alt="image" src="https://github.com/user-attachments/assets/98bcae0c-4f3a-4202-9a01-4dc4bdb56e4c" />
