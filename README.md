# SENTIMENT ANALYSIS OF CUSTOMERS REVIEWS


## INTRODUCTION
In the dynamic landscape of e-commerce, understanding the complex interplay between customer sentiments and purchasing behavior is pivotal for businesses striving to enhance customer satisfaction and optimize marketing strategies. This thesis conducts an extensive analysis of sentiment within the context of women's fashion e-commerce, utilizing lexicon-based sentiment analysis and machine learning models to explore the connections between customer reviews, age groups, and departmental purchases.

## AIMS AND OBJECTIVE
The aim of this analysis is to identify the sentiments from reviews given by different customers of varying age grades and how it impacted purchases in an online fashion store.

## ANALYSIS APPROACH
- Exploratory Data Analysis: The data was collected from Kaggle and EDA was performed on the dataset to identify missing values and eliminate noises in the dataset.
Text conversion and expansion: The initial step involves transforming all letters to lowercase and expanding contracted words like "I'm," "don't,"  "isn't"; this will enhance the organization of the words in the column and facilitate subsequent analysis

- Text Normalization: Leading up to the actual sentiment analysis, a crucial normalization step involves the removal of stop words, punctuation marks, and numbers stop words, such as common words like "and," "the," and "is," were removed as they don't carry significant meaning and can introduce noise to the analysis. Punctuation marks (,,.,!””) were also eliminated to streamline the text and ensure that the focus remains on the actual content of the text. Similarly, the removal of numbers is essential to enhance the text's coherence and to prevent numerical values from interfering with subsequent sentiment analysis

- Lemmatization: The process of lemmatization is a vital aspect of achieving an accurate sentiment from the opinion of customers. Lemmatization involves transforming words to their base or root form, which aids in reducing variations of words to a common representation i.e words like "loving" and "loved" are simplified to their base form "love," ensuring that different forms of a word are treated as the same. This process helps to mitigate the dimensionality of the text, which can lead to more efficient and effective sentiment analyses.
- Polarity-Based Sentiment analysis: This refers to the emotional tone conveyed by words, through examining the polarity of words in the reviews, one could determine whether the sentiments expressed are positive, negative, or neutral. This involves assigning a score to each word based on its sentiment, which helps to gauge the overall sentiment of a review. Words with positive connotations contribute to a positive score, while words with negative associations contribute to a negative score.

- Spacy Sentiment analysis: After analyzing the sentiment using polarity based sentiment, the result did not effectively showcase the customer sentiment's tone, as the words in the neutral category closely resembled those in the negative category. Also, the positive words look ambiguous. 
Consequently, upon researching an alternative sentiment analysis; the Spacy Sentiment approach was adopted for better result because it takes into account the context of the text and I personally like the fact that spacy provides detailed information about how it arrives at its sentiment analysis including the adjective used in the words and the polarity of the sentence at a granular level.


## FINDINGS AND CONCLUSION
The findings of the analysis revealed that the top most used words by customers were Dress, love, fit, size, top, great, colour, look, wear, fabric and the age distribution shows that The dominant age is 36-45 followed by 18-25 while the least is 96-99. This suggests that the store's customers are primarily working-age adults who are financially capable. 
Further deep dive, into the distribution of purchases at different departments shows that tops takes the lead with a whopping 44.6%, dresses make up 26.92% while intimate and jacket categories came behind, standing at 7.39% and 4.40% respectively. The 'Tops' category emerges as a consistent favorite, occupying a substantial portion of purchases across all age groups, ranging from 40% to 51%. This suggests a universal preference for upper-body garments regardless of age. Furthermore, the 'Dresses' department garners notable attention, particularly among the '36-45' and '26-35' demographics, constituting 29% and 30% of purchases respectively.
Analysis of the positive sentiments for women's clothing across various age groups, spanning from '18-25' to '96-99'. The most prominent words within the word cloud result are "great" and "perfect," adopted by customers of all age brackets to express contentment with their clothing purchases. Alongside these, frequently used terms encompass "love," "beautiful," and "color," which signify shared appreciation for aesthetic and appealing aspects of the clothing.
However, intriguing distinctions arise when examining the word cloud among different age groups. Notably, the term "dress" holds prominence in the '26-45' age group, while "sweater" dominates the '46-65' age group. This divergence implies a preference shift, where younger customers lean towards dresses and older individuals gravitate towards sweaters. Furthermore, the word choices of "fit," "fabric," and "comfortable" are more pronounced in the '66-95' age range, while "beautiful," "perfect," and "colour" are dominant within the '18-45' range. This suggests that younger generations prioritize style, whereas older generations emphasize warmth, comfort and appropriate fabric when selecting women's clothing. 
In a nutshell, the analysis found that women of all ages love dresses, but younger customers tend to prefer them more. They also all appreciate a good fit and beautiful colors, but older customers are more likely to prioritize comfort and appropriate fabric.
## RECOMMENDATION
This sentiment analysis offers a perspective on the impact of demographics on customer preferences. It described how the dynamic nature of consumer behavior can equip women's fashion e-commerce retailers with actionable insights to enhance their strategies such as tailoring marketing and promotional strategies that will resonate with specific age groups, personalized recommendations for varying age groups, optimizing inventory management and overall elevating customer experience.
