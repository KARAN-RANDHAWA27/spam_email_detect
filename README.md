# Spam Email Classifier

This project is created by **Karan Randhawa**. It is a machine learning application that classifies email messages as **Spam** or **Ham (Not Spam)**. The working model is deployed and accessible online in this Hugging Face Space: [Spam Email Classifier](https://huggingface.co/spaces/karan2720/Spam-Email).

## Project Overview

The Spam Email Classifier is built using **Python** and **Scikit-learn**. It leverages natural language processing techniques to analyze email text and predict whether a message is spam or not. The project demonstrates a complete machine learning workflow, from data preprocessing to model deployment with an interactive web interface.

### Key Features

- **Real-time Spam Detection:** Enter any email text, and the model predicts instantly.
- **Machine Learning Pipeline:** Combines text vectorization (`CountVectorizer`) and classification (`Multinomial Naive Bayes`) for seamless prediction.
- **Interactive UI:** Built with **Gradio**, allowing users to interact with the model easily through a browser.
- **Deployed Online:** Hosted on **Hugging Face Spaces**, making the model accessible publicly without any setup.
- **Accurate Predictions:** Trained on labeled email datasets to distinguish spam messages effectively.

### How It Works

1. **Text Preprocessing:** Raw email text is transformed into numerical feature vectors using `CountVectorizer`, which counts the occurrence of each word in the text.
2. **Model Prediction:** A Multinomial Naive Bayes classifier predicts whether the message is spam based on the text features.
3. **Pipeline Integration:** Both preprocessing and prediction are combined in a scikit-learn **Pipeline**, allowing the model to accept raw text directly.
4. **Web Interface:** Users can input email messages into a textbox on the Hugging Face Space UI and receive immediate predictions.

### Technologies Used

- **Python 3**
- **Scikit-learn** (Machine Learning)
- **Gradio** (Interactive Web UI)
- **Hugging Face Spaces** (Deployment)
- **Pickle** (Model Serialization)

### How to Use

1. Visit the deployed space: [Spam Email Classifier](https://huggingface.co/spaces/karan2720/Spam-Email)
2. Type or paste an email message in the textbox.
3. Click **Submit** to see whether the email is **Spam** or **Ham**.

### Future Improvements

- Add **preprocessing enhancements** such as removing stopwords, punctuation, and handling different languages.  
- Train with a **larger dataset** for improved accuracy.  
- Include a **confidence score** or probability for predictions.  
- Extend the model to detect **phishing attempts** and other email threats.
