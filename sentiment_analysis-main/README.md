

SENTIMENT ANALYSIS ON AMAZON PRODUCT REVIEW



# ABSTRACT

This project focuses on sentiment analysis of Amazon product reviews, aiming to understand customer feedback through natural language processing techniques. The core functionality includes scraping product reviews from Amazon, cleaning the textual data, and applying sentiment analysis to categorize reviews as positive, negative, or neutral. The project leverages Python libraries like BeautifulSoup for web scraping, nltk for text preprocessing (stopword removal, lemmatization), and TextBlob for analyzing the sentiment and confidence levels of each review.
The data is cleaned by removing unwanted characters and stop words, converting text to lowercase, and applying lemmatization to standardize the text. After sentiment analysis, the reviews are visualized through various charts, including sentiment distribution bar charts, pie charts, and word clouds, providing insights into common themes and customer sentiment. Additionally, review length distributions and keyword frequency analysis offer deeper insights into customer feedback. The project provides an intuitive interface using Streamlit, allowing users to write their own reviews, or scrape reviews from Amazon URLs for analysis. The streamlined process enhances product sentiment understanding, offering valuable feedback for both customers and businesses.
 


# INTRODUCTION

In the era of e-commerce, customer feedback plays a vital role in shaping consumer decisions and guiding businesses toward improvements. One of the most powerful ways to extract insights from such feedback is through Sentiment Analysis, a process that uses natural language processing (NLP) to determine whether a piece of text expresses positive, negative, or neutral sentiment. This project focuses on implementing sentiment analysis on Amazon product reviews to gauge customer opinions and sentiments.

The system utilizes web scraping to extract reviews from Amazon using BeautifulSoup, and the textual data is cleaned and preprocessed using the nltk library. Techniques such as stopword removal, lemmatization, and tokenization are applied to ensure the data is structured and ready for analysis. Sentiment is then evaluated using the TextBlob library, which assigns polarity scores to classify each review into positive, negative, or neutral categories.

This project also provides a user-friendly interface built using Streamlit, allowing users to analyze reviews by entering their own review, or directly scraping reviews from an Amazon product URL. Visualization tools such as bar charts, pie charts, and word clouds are used to present the distribution of sentiments and the most frequently mentioned keywords. By analyzing this feedback, businesses can better understand customer satisfaction, improve their products, and make data-driven decisions.


# PROBLEM DEFINITION
In today's e-commerce landscape, online product reviews play a critical role in influencing customer decisions. With the vast amount of reviews available for each product, manually analyzing customer sentiment can be both time-consuming and challenging. It becomes essential to automate the process of analyzing these reviews to understand the overall sentiment (positive, negative, or neutral) toward a product.
The project aims to create a web application that can:
o	Automatically scrape customer reviews from Amazon.
o	Preprocess the textual data to clean it.
o	Perform sentiment analysis on the reviews using machine learning and natural language processing techniques.
o	Provide a visual representation of the analysis, including sentiment distribution, confidence scores,and keyword frequency.
        This system will simplify sentiment analysis for product reviews, making it easier for businesses, consumers, and researchers to gain insights into public opinion on various products.




# LITERATURE SURVEY

Sentiment analysis is a key area in natural language processing (NLP) used to assess opinions expressed in text. With the growth of e-commerce, analyzing customer feedback has become essential. This project leverages TextBlob, a lexicon-based tool, to analyze Amazon product reviews. 
## 2.1.1. Sentiment Analysis Approaches 
Initial sentiment analysis relied on manual methods, but with advances in NLP, automated techniques emerged. Basic models like Bag of Words and TF-IDF were common, but now, more advanced models, such as word embeddings (Word2Vec, GloVe), capture word context better. TextBlob, used in this project, is a simple tool for polarity-based sentiment scoring. 
## 2.1.2. Web Scraping for Review Data 
To gather real-world data, web scraping techniques have been employed. In this project, BeautifulSoup extracts reviews from Amazon, a common practice in sentiment analysis research. Ethical considerations like site permissions are important when scraping data. 
## 2.1.3. Text Preprocessing 
Cleaning raw text is crucial for accurate analysis. This project uses standard preprocessing techniques such as lowercasing, removing stopwords, and lemmatization. These steps are supported by literature as necessary to reduce noise in the data. 
## 2.1.4. Sentiment Analysis Tools 
While sophisticated models like LSTM and BERT provide better accuracy, TextBlob is simple and effective for basic sentiment tasks. It assigns polarity and subjectivity scores based on predefined word dictionaries, ideal for small projects like this one. 
## 2.1.5. Visualization of Results 
Visualizing sentiment trends is key to understanding data. This project uses matplotlib and Seaborn for visual representation, including bar charts, pie charts, and word clouds, as these methods are widely used to make sentiment insights clear. 
## 2.1.6. Streamlit for Application Deployment 
Streamlit is used to create a user-friendly interface for the sentiment analysis. It allows users to upload data or scrape reviews directly, making the analysis accessible without coding knowledge. 
## 2.1.7. Challenges 
Challenges include detecting sarcasm and handling mixed sentiments, which tools like TextBlob may struggle with. Multilingual sentiment analysis is another area that requires more advanced methods.



# OBJECTIVES OF THE WORK
•  To automate sentiment analysis: Develop a system that automatically scrapes Amazon product reviews, processes the text, and classifies sentiments into positive, negative, or neutral categories.
•  To clean and preprocess data: Implement data cleaning techniques such as removing stop words, lemmatization, and removing special characters to prepare review data for accurate sentiment analysis.
•  To perform sentiment classification: Use TextBlob for analyzing the polarity and subjectivity of each review, providing a sentiment score to classify customer feedback.
•  To visualize sentiment trends: Provide clear visualizations such as bar charts, pie charts, and word clouds to help users easily interpret the sentiment distribution and keyword frequencies.
•  To create an accessible interface: Build a user-friendly Streamlit web application that allows non-technical users to input text or input product URLs for real-time sentiment analysis.
•  To enhance decision-making: Help businesses and consumers make informed decisions based on customer sentiment, improving product insights and purchase decisions.


# CONCLUSION AND FUTURE ENHANCEMENTS

The sentiment analysis system developed for Amazon product reviews demonstrates an efficient method for extracting valuable insights from customer feedback. By utilizing web scraping, text preprocessing, and sentiment analysis through tools like TextBlob, this project offers users a comprehensive view of the sentiments expressed in reviews. The visualizations generated provide clarity on overall customer sentiment, review length patterns, and keyword frequency, which helps in understanding the factors influencing product satisfaction. The system's streamlined process allows users to make informed decisions based on the aggregated sentiment data.
## 6.1 SUMMARY OF THE WORK
This project focuses on building a sentiment analysis system for Amazon product reviews. The tool allows users to input an Amazon product URL, from which it scrapes customer reviews using web scraping techniques. These reviews are then processed using Natural Language Processing (NLP) methods to clean the text, remove noise, and prepare it for analysis. The sentiment analysis is carried out using TextBlob, which determines the polarity (positive, negative, or neutral) and subjectivity of each review. The system presents results through various visualizations, such as bar charts for sentiment distribution, word clouds for common keywords, and histograms for review length and confidence scores. This enables users to easily understand the overall sentiment trends. The project is built using a Streamlit web interface, making it simple and accessible for end users.Future enhancements include the addition of CSV file uploads for bulk sentiment analysis and the integration of more advanced sentiment models.

# RESULTS
<img width="992" height="482" alt="image" src="https://github.com/user-attachments/assets/45cbc536-a159-4af4-9b40-b16b50e9b53d" />
<img width="964" height="454" alt="image" src="https://github.com/user-attachments/assets/4fc26110-a82c-43ae-93cb-4f1ea96e970f" />
<img width="956" height="391" alt="image" src="https://github.com/user-attachments/assets/097f515e-8c28-48ff-b766-8406f54f18e2" />
<img width="1025" height="493" alt="image" src="https://github.com/user-attachments/assets/ebb8f200-71d0-4350-8381-677bec1795f2" />
<img width="1011" height="442" alt="image" src="https://github.com/user-attachments/assets/37424d2d-a450-470e-a541-806dcec2da96" />
<img width="1017" height="453" alt="image" src="https://github.com/user-attachments/assets/9ca82670-a7f8-4807-8eba-e2c779c5c282" />
<img width="1019" height="548" alt="image" src="https://github.com/user-attachments/assets/48c4372c-3e1c-4eef-ac2d-a5c45c176aa7" />
<img width="1012" height="490" alt="image" src="https://github.com/user-attachments/assets/c36d0ad5-9b0f-4e69-9f0f-ca151fd7fc51" />



## 6.2	FUTURE ENHANCEMENTS
1.	CSV File Upload for Sentiment Analysis:
•	In the next phase, the system will include the ability for users to upload CSV files containing product reviews. This will extend the flexibility of the tool, enabling users to analyze large datasets of reviews that are already collected offline or from other sources.
2.	Multi-Product Comparison:
•	A feature allowing detailed sentiment comparison between multiple products, making it easier for users to evaluate competing products based on customer feedback.
3.	Advanced Sentiment Models:
•	Incorporating more advanced sentiment analysis models like VADER or transformers-based models such as BERT for improved accuracy, particularly in handling complex or mixed sentiments in reviews.


              

# REFERENCES

[1]	•  Pang, B., & Lee, L. (2008). "Opinion Mining and Sentiment Analysis." Foundations and Trends in Information Retrieval, 2(1–2), 1–135.
DOI: 10.1561/1500000011.
[2]	•  Liu, B. (2012). "Sentiment Analysis and Opinion Mining." Synthesis Lectures on Human Language Technologies, 5(1), 1–167.
DOI: 10.2200/S00416ED1V01Y201204HLT016.
[3]	•  Bird, S., Klein, E., & Loper, E. (2009). Natural Language Processing with Python. O'Reilly Media, Inc.
ISBN: 978-0596516499.
[4]	•  Loria, S. (2021). "TextBlob: Simplified Text Processing."
URL: https://textblob.readthedocs.io/en/dev/
[5]	•  Hunter, J. D. (2007). "Matplotlib: A 2D Graphics Environment." Computing in Science & Engineering, 9(3), 90–95.
DOI: 10.1109/MCSE.2007.55.
[6]	•  Waskom, M. L. (2021). "Seaborn: Statistical Data Visualization." Journal of Open Source Software, 6(60), 3021.
DOI: 10.21105/joss.03021.
[7]	•  McKinney, W. (2010). "Data Structures for Statistical Computing in Python." Proceedings of the 9th Python in Science Conference (SciPy 2010), 51–56.
URL: https://doi.org/10.25080/Majora-92bf1922-00a.
[8]	•  Rehurek, R., & Sojka, P. (2010). "Software Framework for Topic Modelling with Large Corpora." Proceedings of the LREC 2010 Workshop on New Challenges for NLP Frameworks.
URL: https://radimrehurek.com/gensim/
[9]	•  Amazon.com. (2023). "Customer Reviews - Amazon."
URL: https://www.amazon.com/

