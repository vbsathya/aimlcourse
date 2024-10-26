### Find Impact of Tax Regulartion for a Company

**Sathya Venuraju**

#### Executive summary
    This experiment is trying to find how a tax law change might impact a particular company. Typically a potential tax law change will be published as a news article when it is proposed. The idea is to use natural language processing to understand the news article and identify how it might impact.
#### Rationale
    This will be useful for company tax departments and tax and accounting firms to understand the impact of tax law change well in advance so that they can be prepared for it. It will also help them meet their tax compliance obligation.

#### Research Question
    How successfully we can predict the impact of a tax law change for a given state

#### Data Sources
    1. News articles sourced from a third party tax research product under NDA
    2. Tax form instructions from state tax websites
    3. Electronic tax filing schema from state websites

#### Methodology
    1. Load news articles about tax law change into dataframe
    2. Create short description for each tax form in a given state
    3. Pick a sample set of news articles and ask tax analyst to annotate what tax forms may be impacted by an article
    4. Use NLP techniques to vectorize news articles and tax form description
    5. Use TF-Idf to find similarity between a news article and tax form description to identify impacted forms by an article.
    6. Compare the predicted tax forms to tax forms annotated by subject matter experts to evaluate the metrics

#### Results
    I considered this problem as multi-class classification problem. So I used Precision, Recall and F2 score to evaluate the model. Following is the result.
    Precision: 0.2836
    Recall: 0.4849
    F2 Score: 0.4246

#### Next steps
    Use advanced NLP techniques and transformer based models like BERT to improve the score. See if we can fine tune transformer models by training them using tax form descriptions and other tax domain related text corpus.


#### Outline of project
Link to the notebook that has exploratory data analysis and model creation.
https://github.com/vbsathya/aimlcourse/blob/main/exploratory%20data%20analysis%20and%20initial%20model%20creation.ipynb

##### Contact and Further Information
