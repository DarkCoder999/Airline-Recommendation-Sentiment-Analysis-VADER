# Predicting airline customers’ recommendations using ratings and reviews of online websites
<a href="https://www.kaggle.com/datasets/khushipitroda/airline-reviews">Dataset can be found here</a>
<p>Implemented sentiment analysis, a popular technique for identifying and extracting opinions and sentiments from textual data. To analyze the sentiment of consumer 
comments and reviews in the airline business, used state-of-the-art language model called <b>VADER (Valence Aware Dictionary for Sentiment Reasoning)</b> that is specifically tuned towards the opinions shared on social media and operates using lexicon and rule-based sentiment.</p>
<h6>Workflow</h6>
<img src="https://github.com/DarkCoder999/Airline-Recommendation-Sentiment-Analysis-VADER/assets/98643503/62b3c926-c644-4232-a794-0df8fbf74960" alt="architecture" />
<p>Combined the compound scores obtained from VADER with other ratings present in the dataset to train multiple Machine Learning models</p>
<img src="https://github.com/DarkCoder999/Airline-Recommendation-Sentiment-Analysis-VADER/assets/98643503/a8b89a7e-bfe0-4b3b-b84c-c6f682fc013f" alt="results" />
<p><b>LightGBM</b> achieved the best accuracy of 96.6%, indicating its superior performance in predicting customer satisfaction. Moreover, ensemble learning methods and careful hyperparameter tuning can improve the generalization performance of the models on unseen data, which is essential for practical applications </p>
