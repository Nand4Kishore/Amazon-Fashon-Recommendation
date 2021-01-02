# Amazon-Fashon-Recommendation
About the Dataset:
Dataset was generated using amazon product advertising API (https://webservices.amazon.com/paapi5/documentation/)

This dataset consists of collection of all the women's tops sold through amazon website. The data contains ~184,000 products.


Objective:
To recommend products that are similar to the a particular product.

Tasks Performed:

1. The data is cleaned and pre-processed using standard NLP techniques. I have used tokenization,stemming ,stop-words removal .
2. For this data we have removed  duplicate products and also those products whose title differes by less than 3 words.
3. Convert titles into vectors using bag of words and then calculating euclidian distance to find the top similar products.
4. Convert titles into vectors using TF-IDF and then calculating euclidian distance to find the top similar products.
5. Convert titles into vectors using average Word2Vec and then calculating euclidian distance to find the top similar products.
6. Conversting brand and color of the product to vectots using TF IDF and calculating the euclidian distance to find the top similar products.
7. Calculating image similarity using CNN with keras.
8. Comparing results of step 3,4,5,6,7
9. Using TF IDF vector of title,brand,color and the vectorized image and assigning weights to each vector before combining it into a single sparse vector and then calculating the eculidian distances to find the  top similar products.
