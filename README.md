## Classifying Amazon products as Defective / Non-defective Based on Customers' reviews using Natural Language Processing

Classification is a technique used in machine learning to identify which category or class an item belongs to. In the context of Amazon reviews, classification could be used to predict whether a review is positive or negative. This can be useful for identifying the overall sentiment of customer reviews and understanding how customers feel about a particular product. The algorithm can be trained on a large dataset of customer reviews, where each review is labeled as either defective or non-defective. The training data can be collected from Amazon's website, where customers provide feedback on the products they have purchased.

Once the model is trained, it can be used to classify new customer reviews as defective or non-defective. To do this, the algorithm will analyze the text of the review using Natural Language processing and identify features that are indicative of a defective product. For example, if a review contains words like "broken," "defective," or "faulty," the algorithm may be more likely to classify it as defective. On the other hand, if a review contains words like "good," "great," or "excellent," the algorithm may be more likely to classify it as non-defective.

The algorithm can then make a prediction for each new review, and the results can be used to identify defective products and take appropriate action, such as recalling the product or offering a refund to the customer. By using machine learning, this approach can quickly and accurately classify large numbers of reviews, allowing Amazon to improve the quality of its products and customer satisfaction.

### Dataset

The Datasets used in the project contain the reviews for 4 appliances from Amazon’s Appliances category - Blenders, Coffee Makers, Slow Cookers and Toaster Ovens. Apart from the original columns, an additional ‘Defect’ column is created to classify the data as defective.

### Data Preprocessing

Unstructured text data is one of the most important sources of information in the modern world. Text analytics applications include collecting thoughts from social media data, discovering customer satisfaction from product evaluations or feedback, and more. To find insights from text data i.e., reviews in our case, we need to preprocess the data before we train the classification or regression models. Text preprocessing includes removing stop words, numbers, URLs’, punctuations etc.,

Since “Defect” is a dependent feature in our dataset and our focus is to classify the products as defective or non-defective, we kept only “No Defect” and “Performance Defect” data by removing “Safety Hazard” reviews.

<img width="600" alt="image" src="https://github.com/UmaBetageri/Amazon-Reviews-Classification/assets/134670470/aac86571-52e6-47bc-b9e0-fec6f6299bcd">


