# BusinessDay-Sentiment-Analysis

**Project Overview**

Sentiment Analysis on BusinessDay Newspaper to uncover the emotional tone of the populate on the nation's economy from 2021 to 2025. To analyze the polarity scores representing the emotional under-tone of the citizenry on Nigerian's economy within the aforementioned period.

**Introduction:**

**About BusinessDay**

BusinessDay is a leading Nigerian business and financial daily newspaper. BusinessDay serves a diverse readership including policymakers, business leaders, investors, and professionals. It's reputation for credible journalism and its focus on data-driven reporting make it an influential voice in shaping public and economic discourse in Nigeria. Thus, being our data source on Nigeria's economic matters.

By analyzing the emotional tone of the national media we uncover critical insights into the collective mood, public sentiment, and underlying economic and social tensions within the country.

**1. Methodology**
* Data collection: scraping of BusinessDay articles:[https://businessday.ng/tag/bdlead/?amp]
  * Scraped 819 BusinessDay articles from 2021 - 2025
* Preprocessing steps:
  *Data cleaning, tokenization, removed stop works
* Scraping Tool used: **Selenium**
  
**Features Extracted**
   * Title
   * Author
   * Date published
   * Full articles' contents

 **2. Preprocessing & Sentiment Analysis**
    **Preprocessing**
    
      * Removed stopwords, and punctuation
      * Converted text to lowercase
      * Carried out tokenization and lemmatization
      
 **Sentiment Model**
 
    * Tool Used: TextBlob
      
 **Tools & Libraries**
   * Python 3.13
   * Selenium
   * Pandas
   * NLTK, TextBlob
   * Matplotlib, Seaborn
     
  **Polarity Scores are categorized into the following:**
 
   * Positive
   * Neutral
   * Negative

**Key Findings:**
 * Overall, about 6,604 articles were scraped, out of which 20.02% tended towards a Positive emotional tone, implying a good outlook of the nation's economy by this chunk.
 * While, 78.45% was Neutral, indicating middle positioning of emotional tone of the articles(neither positive nor negative).
 * Only 1.5% was Negative.

**Conclusion**

  Based on our findings, the emotional tone from 2021-2025 is significantly Neutral, which is rather geared towards uncertainty and ongoing development in the nation's economy.
  
