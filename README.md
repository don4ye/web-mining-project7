# Article Summarization and Sentiment Analysis

## **Project Overview**
This project applies web mining and Natural Language Processing (NLP) techniques to analyze a news article on the Israel-Hamas conflict. The goals include:
- Performing sentiment analysis on the article and its summaries.
- Generating concise summaries using tokens and lemmas.
- Visualizing sentiment scores and interpreting results.

## **Objectives**
1. Extract text from the article's HTML.
2. Perform token-based and lemma-based sentiment analysis.
3. Generate histograms to visualize sentiment distributions.
4. Create summaries of the article and compare their polarity scores.
5. Reflect on the differences between the summaries and their quality.

## **Tools and Libraries**
The following tools and Python libraries were used:
- **spaCy**: For text tokenization, lemmatization, and sentence splitting.
- **TextBlob**: For sentiment analysis and polarity scoring.
- **BeautifulSoup**: For extracting text from HTML.
- **Matplotlib**: For visualizing sentiment scores in histograms.

## **Workflow**
### **1. Article Extraction**
- The HTML content of the article was extracted and saved to `israel_hamas_war_article.html`.
- The article's plain text was extracted and saved to `israel_hamas_war_article_text.txt`.

### **2. Token-Based Analysis**
- Sentiment scores were calculated for sentences using token-based polarity.
- A histogram visualized the distribution of token-based sentiment scores.
- A token-based summary was created using a cutoff score.

### **3. Lemma-Based Analysis**
- Sentiment scores were calculated using lemma-based polarity.
- A histogram visualized the distribution of lemma-based sentiment scores.
- A lemma-based summary was created using a cutoff score.

### **4. Summary Comparison**
- The polarity scores and number of sentences in both summaries were compared.
- Reflections were provided on which summary better represented the article.

## **Results**
- **Polarity Score of the Full Article**: *0.0*
- **Polarity Score of the Token-Based Summary**: *0.0*  
- **Polarity Score of the Lemma-Based Summary**: *0.2467*  
- **Number of Sentences in the Lemma-Based Summary**: *10*

## **Visualizations**
- Histograms were generated to visualize sentiment score distributions:
  - Token-based sentiment scores.
  - Lemma-based sentiment scores.

## **Conclusion**
The lemma-based summary proved to be more concise and impactful due to its focus on high-polarity sentences. This approach effectively highlighted key aspects of the article while maintaining readability.

## **How to Run the Project**
1. Clone the repository:
   ```bash
   git clone https://github.com/don4ye/web-mining-project7.git
   cd web-mining-project7
